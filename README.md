#  Knife



One of the goals of this project has always been consistency and portability. Kubernetes sits on top of the infrastructure and enables you to describe your workload in a common format. Kubernetes makes it easy to move workloads from one place to another, or combine disjointed environments with a shared control plane.

In order to better serve these goals, the Kubernetes community (under the aegis of the CNCF) is
running a Kubernetes Software Conformance Certification program, currently in a pre-launch status. I was able to design scripts which allow you do that more easily. 

This tool helps with conformance testing results for review and certification by the CNCF. The CNCF will formally certify compliant platforms and officially launch the program later this year.

Just like Kubernetes itself, the conformance certification is a living thing. Certification is versioned, and with each new version of Kubernetes, as features are added and the architecture changes, the Certification requirements will change as appropriate. The Kubernetes community, through [SIG Architecture](https://github.com/kubernetes/community/tree/master/sig-architecture), is the change controller and oversees of what it means to be Certified Kubernetes. Work on the mechanics of the conformance tests occurs in [SIG Testing](https://github.com/kubernetes/community/tree/master/sig-testing) and the [Conformance WG](README-WG.md) develops the process and policy around the certification program.

Once the program officially launches later this year, platforms that certify will be able to proudly display the new Certified Kubernetes logo mark on their marketing materials and may also take advantage of a new combination trademark rule the CNCF adopted for Certified Kubernetes providers that keep up to date with their certification. Certification is available for Kubernetes versions 1.7 and higher.

To ensure the pace of innovation in Kubernetes continues and benefits all users, platforms must complete a recertification each year for the current or previous version of Kubernetes to remain certified. This ensures that when you see the Certified Kubernetes mark on a product, you’re not only getting something that’s proven conformant, but also contains the latest and greatest developments from the community.

## Program Information

[Certification Instructions](instructions.md)

[Certified Kubernetes Conformance Program – Terms and Conditions](https://github.com/cncf/k8s-conformance/blob/master/terms-conditions/Certified_Kubernetes_Terms.md)

[Certified Kubernetes Conformance Program – Participation Form](https://github.com/cncf/k8s-conformance/blob/master/participation-form/Certified_Kubernetes_Form.md)

[Certified Kubernetes Conformance Program – Brand Guidelines](https://github.com/cncf/artwork/blob/master/kubernetes/certified-kubernetes/certified-kubernetes-brand-guide.pdf)

[Certified Kubernetes Conformance Program – Marks](https://github.com/cncf/artwork/tree/master/kubernetes/certified-kubernetes/)

## Working Group Information

To participate and contribute to the program itself (including discussion of
issues affecting conformance and certification), join the mailing list and
slack channel. Details: [Conformance WG](README-WG.md).
