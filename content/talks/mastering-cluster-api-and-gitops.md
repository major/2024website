---
title: "Mastering Cluster API and GitOps: A Deep Dive into Extensible Components for Building Production-Ready Kubernetes Clusters"
description: "Texas Linux Fest 2024"
page_header_bg: "images/background/page-title-bg.jpg"
format: "Workshop"
when: "Friday, April 12, 4:30 PM - 5:45 PM"
where: "Room 3"

speakers:
  - name: "Oluebube Princess Egbuna"
    image: "images/speakers/oluebube-princess-egbuna.jpg"
    link: "speakers/oluebube-princess-egbuna/"
---

There are many different ways you can bootstrap Kubernetes clusters with
various degrees of complexity.

Modern Kubernetes installers automate manual tasks, but generally, the more
they abstract away complexity, the more opinionated they are — and that
restricts your choice. Cluster API is different. It is one of the most flexible
and efficient tools for managing the Kubernetes lifecycle, whether used for
deployments, upgrades, or scaling operations.

While Cluster API is a powerful tool for provisioning Kubernetes clusters, it
doesn't cover everything. Essential add-on components and software, such as
node auto-scalers, CNI, ingress controllers, and other key infrastructure
elements, are not included.

In this workshop, you will delve into how to supercharge Cluster API by
integrating it with various solutions to build production-ready clusters. For
the grand finale, we'll introduce GitOps into the equation using ArgoCD,
enhancing scalability and bolstering security. Join Bube as she unveils how to
unlock the full potential of Cluster API and transform your Kubernetes journey.

There are a lot of resources around Cluster API, but none of them mention how
to get clusters ready for day two ops. This workshop covers everything in terms
of building cluster API clusters with GitOps, including the remaining
components to get full functional clusters, such as CNI, auto-scaling, and how
to configure helm templates for even more automation.

Attendees will be leveraging Kubernetes extensible API through Custom Resources
(CRD) to automate the deployment and management of Kubernetes. Every attendee
will have a dedicated lab through the Instruqt platform. The workshop will
delve into the following projects:

* Cluster API (CAPI)
* ArgoCD
* Cluster auto-scaler (CA)
* Cluster API Addon Provider for Helm (CAAPH)
