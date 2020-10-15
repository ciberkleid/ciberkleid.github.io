---
layout: page
theme: Kubernetes Admission Controllers
title: Writing a Kubernetes Validating Admission Webhook
conf1: "[VMware {Code} 2020](https://www.youtube.com/embed/RFQ30mhdf3c)"
conf1_youtube: RFQ30mhdf3c
---

How do you control what goes into your Kubernetes cluster? How do you ensure that your users are following corporate guidelines for Kubernetes usage? How do you do all this without auditing the environment after the infraction occurred? This session by Cora Iberkleid, an Advisory Solutions Engineer at VMware, will explore how to build a validating admission controller for use with a Kubernetes cluster. In this session, you’ll learn how to deploy a Python app that can validate Kubernetes API calls and either approve or deny them. You’ll learn how to setup a Kubernetes webhook and most importantly, you’ll learn why you might want to use an admission controller in your environment.