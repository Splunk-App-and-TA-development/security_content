---
title: "Ransomware Investigate and Contain"
excerpt: "Carbon Black Response, LDAP, Palo Alto Networks Firewall, WildFire, Cylance"
last_modified_at: 2018-02-04
toc: true
toc_label: ""
tags:
  - Response
  - Splunk SOAR
  - Carbon Black Response
  - LDAP
  - Palo Alto Networks Firewall
  - WildFire
  - Cylance
---

[Try in Splunk SOAR](https://www.splunk.com/en_us/software/splunk-security-orchestration-and-automation.html){: .btn .btn--success}

#### Description

This playbook investigates and contains ransomware detected on endpoints.

- **Type**: Response
- **Product**: Splunk SOAR
- **Apps**: Carbon Black Response, LDAP, Palo Alto Networks Firewall, WildFire, Cylance
- **Last Updated**: 2018-02-04
- **Author**: Philip Royer, Splunk
- **ID**: fc0edc96-ff2b-48b0-9f6f-63da3783fd63

#### Associated Analytic Story
* [Ransomware](/stories/ransomware)


#### How To Implement
This playbook requires the Splunk SOAR apps for Palo Alto Networks Firewalls, Palo Alto Wildfire, LDAP, and Carbon Black Response.

#### Required field
* ComputerName
* Username


#### Reference



[*source*](https://github.com/splunk/security_content/tree/develop/playbooks/ransomware_investigate_and_contain.yml) \| *version*: **1**