---
title: LLMjacking
parent: Real-World Attacks
nav_order: 2
---

{: .goal }
>Many attackers are simply looking for financial gain. Large Language Models (LLMs) are expensive to use and often poorly protected, so attackers consider them a worthwhile target, perhaps even low-hanging fruit.
>
> The Sysdig Threat Research Team (TRT) coined the term LLMjacking to describe this kind of attack.
>
>In this module, we will simulate the attack and learn how Sysdig can help prevent and detect the attack.

1. TOC
{:toc}

## Overview

In early 2024, the [Sysdig Threat Research Team (TRT)](https://sysdig.com/blog/llmjacking-stolen-cloud-credentials-used-in-new-ai-attack/) observed a new attack that leveraged stolen cloud credentials in order to target ten cloud-hosted large language model (LLM) services, and coined the term LLMjacking. 

- **It's Expensive to Run LLMs**

Attacks against LLM-based Artificial Intelligence (AI) systems have been discussed often, but mostly around prompt abuse and altering training data. In this case, attackers intend to sell LLM access to other cybercriminals while the cloud account owner pays the bill.

{: .highlight }
>The Sysdig Threat Research Team has calculated that the cost to the victim can be over **$46,000 per day** for a Claude 2.x user. If the attacker has newer models, such as Claude 3 Opus, the cost would be even higher, potentially two to three times as much. 

- **Lack of Visibility into LLM Workloads**

Often, security teams are not aware of what LLMs are being used in their environment, as all a developer needs is to install an LLM library, write a bit of glue code, setup an API key, and they're off to the races. The barrier to accessing LLMs is low, LLM cybersecurity maturity is low, and the cost of their use is high.

- **Low Maturity in LLM Security**

It's early days for LLM security, and the industry is still learning how to secure these systems.

## How the Real-World Attack Worked

**TBD**

## Simulating the Attack

**TBD**

## Getting Visibility into LLM Usage With Sysdig

**TBD**

## Detecting the Attack With Sysdig

**TBD**

## Completed

**TBD**

## Further Reading


- [Growing Dangers of LLMjacking](https://sysdig.com/blog/growing-dangers-of-llmjacking/)
- [LLMjacking: Stolen Cloud Credentials Used in New AI Attack](https://sysdig.com/blog/llmjacking-stolen-cloud-credentials-used-in-new-ai-attack/)
- [Strengthen LLMs with Sysdig Secure](https://sysdig.com/blog/strengthen-llms-with-sysdig/)
- [AI Security Workflow](https://sysdig.com/ai-security-workflow/)
- [Sysdig's AI Workload Security: The Risks of Rapid AI Adoption](https://sysdig.com/blog/sysdigs-ai-workload-security-the-risks-of-rapid-ai-adoption/)
- [AI Workload Security for Cloud Native Applications](https://sysdig.com/blog/ai-workload-security-for-cnapp/)
