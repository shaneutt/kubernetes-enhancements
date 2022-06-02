# Enhancements Tracking

Enhancement tracking repository for [Kong](https://github.com/kong)'s Kubernetes projects, including:

- Kong Gateway Operator: https://github.com/kong/gateway-operator
- Kubernetes Ingress Controller (KIC): https://github.com/kong/kubernetes-ingress-controller
- Kubernetes Testing Framework (KTF): https://github.com/kong/kubernetes-testing-framework
- Kubernetes Helm Charts: https://github.com/kong/charts

This repository is a analog to [Kubernetes Enhancements](https://github.com/kubernetes/enhancements) where you will find documents which use the upstream [Kubernetes Enhancement Proposals (KEP)][keps] as a guideline to propose changes and improvements in the Kong Kubernetes Ingress Controller (KIC).

In a general sense we try to follow the [upstream KEP template][kep-template] and [rules][kep-readme], but it's more important that we are able to express our _motivations, goals, non-goals, design, and history_ about improvements than it is to rigorously follow any process, so note that you may encounter some variance from upstream and the KIC maintainers consider KEP more of a guideline, so we're not super strict on form.

If you want to write a new KEP the basic process is:

- copy the [upstream KEP template][kep-template]
- focus on Summary, Motivation, Goals, and Non-Goals for the first iteration (we try to avoid technical implementation details when first exploring a new proposal)
- delete any sections not in use (they can be added back later)
- submit a PR with the _bare minimum content required to express what you would like to see improved_

If you want to contribute but you're feeling a bit stuck, feel free to catch us in [#kong on Kubernetes Slack][slack] for help!

[keps]:https://github.com/kubernetes/enhancements
[kep-template]:https://raw.githubusercontent.com/kubernetes/enhancements/master/keps/NNNN-kep-template/README.md
[kep-readme]:https://github.com/kubernetes/enhancements/tree/master/keps#readme
[slack]:https://kubernetes.slack.com/messages/kong
