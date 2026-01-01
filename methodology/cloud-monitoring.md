# Cloud Security Monitoring – AWS GuardDuty

## Overview
AWS GuardDuty was enabled to monitor cloud activity
related to the application during the assessment period.

GuardDuty analyzes AWS CloudTrail, VPC Flow Logs,
and DNS logs to identify suspicious behavior.

---

## GuardDuty Finding Summary

**Finding Type:** <redacted>  
**Severity:** Low / Medium / High  
**Affected Service:** <IAM / EC2 / VPC / API>  

### Description
GuardDuty detected anomalous activity indicating
potential cloud-level security risks.

Specific identifiers have been redacted to protect
sensitive infrastructure details.

---

## Evidence
Screenshot captured from the AWS GuardDuty console
showing the finding type and severity.

![GuardDuty Evidence](../screenshots/guardduty-finding.png)

---

## Impact Assessment
The finding highlights risks at the cloud infrastructure
level that are not visible through application-layer
testing tools.

No confirmed application exploitation was identified.

---

## Recommendations
- Review IAM roles and permissions
- Investigate the source of the activity
- Enable alerting and automated response where appropriate
