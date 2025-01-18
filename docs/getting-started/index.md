---
title: Getting Started
nav_order: 2
---

## Welcome to the Kraken Hunter workshop!

This workshop is designed to help you learn how to use Sysdig Secure to detect and prevent threats in your Kubernetes and AWS environments.

We have provisioned a separate EKS cluster and EC2 instance (to serve as a jumpbox/bastion) for each of you. You'll connect to that jumpbox via AWS SSM Session Manager in your browser - and it is preloaded with all the tools that you'll need to interact with your EKS cluster and work through today's labs.

We have also provisioned a user for you within Sysdig Secure. While this Sysdig SaaS tenancy is shared between everyone in the workshop today, your login is tied to a team within it which, in turn, is filtered (via a Zone) to only show you information about your EKS cluster/environment.

{: .note}
> Once you have access to your Sysdig and Cloud environments, you'll be ready to start on the [modules](/docs/modules/)!