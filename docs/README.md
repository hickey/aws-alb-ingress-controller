[![Coverage Status](https://coveralls.io/repos/github/kubernetes-sigs/aws-alb-ingress-controller/badge.svg?branch=master)](https://coveralls.io/github/kubernetes-sigs/aws-alb-ingress-controller?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/kubernetes-sigs/aws-alb-ingress-controller)](https://goreportcard.com/report/github.com/kubernetes-sigs/aws-alb-ingress-controller)
[![Build Status](https://travis-ci.org/kubernetes-sigs/aws-alb-ingress-controller.svg?branch=master)](https://travis-ci.org/kubernetes-sigs/aws-alb-ingress-controller)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fcoreos%2Falb-ingress-controller.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fcoreos%2Falb-ingress-controller?ref=badge_shield)

# AWS ALB Ingress Controller

**NOTE:** The current image version is `v1.0.0`. Please file any issues you find and note the version used.

The AWS ALB Ingress Controller satisfies Kubernetes [ingress resources](https://kubernetes.io/docs/user-guide/ingress) by provisioning [Application Load Balancers](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/introduction.html).

This project was originated by [Ticketmaster](https://github.com/ticketmaster) and [CoreOS](https://github.com/coreos) as part of Ticketmaster's move to AWS and CoreOS Tectonic. Learn more about Ticketmaster's Kubernetes initiative from Justin Dean's video at [Tectonic Summit](https://www.youtube.com/watch?v=wqXVKneP0Hg).

This project was donated to Kubernetes SIG-AWS to allow AWS, CoreOS, Ticketmaster and other SIG-AWS contributors to officially maintain the project. SIG-AWS reached this consensus on June 1, 2018.

## Documentation

Checkout our [Live Docs](https://kubernetes-sigs.github.io/aws-alb-ingress-controller/)!

## Getting started

To get started with the controller, see our [walkthrough](https://kubernetes-sigs.github.io/aws-alb-ingress-controller/guide/walkthrough/echoserver/).

## Setup
- See [controller setup](https://kubernetes-sigs.github.io/aws-alb-ingress-controller/guide/controller/setup/) on how to install ALB ingress controller
- See [external-dns setup](https://kubernetes-sigs.github.io/aws-alb-ingress-controller/guide/external-dns/setup/) for how to setup the external-dns to manage route 53 records.

## Building

For details on building this project, see [BUILDING.md](BUILDING.md).

## License

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fcoreos%2Falb-ingress-controller.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fcoreos%2Falb-ingress-controller?ref=badge_large)
