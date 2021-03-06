To reproduce, with `gcloud` configured, clone `kubernetes/kubernetes`, and then

```console
$ git checkout v1.8.1
$ bazel build //build/release-tars
$ cluster/kube-up.sh
$ kubectl create -f c.yaml
$ kubectl logs -f -n sonobuoy sonobuoy
```

I have included `c.yaml` in this PR.
Now wait for `no-exit was specified, sonobuoy is now blocking`.

```console
$ kubectl cp sonobuoy/sonobuoy:/tmp/sonoubuoy ./results
```

Untar and grab `e2e.log`, `junit_01.xml` and `version.txt`.
