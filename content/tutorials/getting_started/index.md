---
title: "Getting Started with BlackCoral"
category: "posts"
date: 2024-10-26
draft: false
tags: []
UID: "1085997576123318284"
---

BlackCoral is a simulated internet environment for practicing cybersecurity. You can interact with the app through Discord bot commands and `kubectl` client for accessing the Kubernetes cluster. 

## Getting Started

1. Start by generating a Kubeconfig with `/connect` and install `kubectl`:

TODO - photo of connect

2. List the base deployments that are created by the BlackCoral server:

TODO - photo of base deployments

3. Interact with the base deployments. Maybe try to hack the vulnerable Redis server after port-forwarding it[TODO - write doc up on redis hack]. If you are able to hack your way to a shell you now have a foothold in the Kubernetes cluster and can use that for further interactions with other deployments without port-forwarding.

4. As well as the default base server deployments, other users can create their own `exposed` deployments. Check out all of the exposed deployemnts port services with `kubectl get svc -n exposed`.

## Running Your Own Deployments

1. TODO

