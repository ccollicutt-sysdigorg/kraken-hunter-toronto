---
title: Runtime Threat Detection and CloudTrail
parent: Runtime Threat Detection in Cloud
nav_order: 1
---


## CloudTrail Detections

Now you have logged in with your AWS user. However, you may have noticed that you are not using Multi-Factor Authentication (MFA) to do so. In the real world, you should always use MFA to log in to your AWS account, but in this workshop you don't, simply for ease of use.

But, Sysdig will detect the lack of MFA and alert you on it!

1. Go to **Threats** -> **Events Feed**

2. There, select **AWS** under the **Event Source** filter.

!["cloudtrail-detection"]({{site.baseurl}}/assets/images/aws-no-mfa-alert.png)

3. In the **Events Feed** pane, you'll see a couple of AWS Cloudtrail alerts. One is for the SSM session where you logged in to your bastion host, and the other is for a login with no MFA.

!["cloudtrail-detection-2"]({{site.baseurl}}/assets/images/aws-no-mfa-alert2.png)
