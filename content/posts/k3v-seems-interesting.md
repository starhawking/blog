---
title: "k3v as an Approachable Example"
slug: k3v-approachable-example
description: "An approachable, non-trivial, go and k8s project to take apart"
date: 2022-03-28T11:33:56-05:00
type: posts
draft: true
categories:
- General
tags:
- go
- k8s
series:
- take-it-apart
---

# k3v as an Approachable Example

I'm always on the hunt for real world examples to demonstrate various tools and techniques. I find a lot of examples that get posted are either too minimalistic to give a sense of what something looks like in practice. On the other hand, lots of real world projects might leverage something, but actually isolating the relevant bits to present can be tricky or impossible.

I found [k3v](https://github.com/ibuildthecloud/k3v) to be a really interesting example for kubernetes development. It is a PoC, so it is pretty lean, but is otherwise functional. Not only does it consume the k8s api, but it also implements various controllers. It seems to be a really nice example of bringing a somewhat non-trivial idea to life. 

Link: [https://github.com/ibuildthecloud/k3v](https://github.com/ibuildthecloud/k3v)
