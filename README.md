# Azure Sentinel Detection Lab

> **Status: planned.** This repository will fill up as the lab is built.

Phase 2 of my home lab: a detection and response lab in Microsoft Azure, built on Microsoft Sentinel, Microsoft Defender XDR and Microsoft Entra ID. Phase 1 built the same skills on a self-hosted Elastic SIEM; this phase moves them to the Microsoft security stack, the platform named most often in Swiss SOC and detection-engineering job ads.

## Planned scope

- **Detection rules in KQL**, mapped to MITRE ATT&CK and tested with safe simulations
- **Rule tuning:** enable built-in analytics rules, measure the noise, and tune the cause (exclusions, thresholds, watchlists, automation rules) instead of suppressing the symptom, with alert volume before and after
- **Threat hunting** queries in KQL
- **Automated response:** a playbook (Logic Apps) for one alert type
- **Identity detections** from Entra ID sign-in logs
- **Vulnerability management:** scan, prioritise, remediate, re-scan
- **Phishing detection and response**, if a Microsoft 365 test tenant is available

## Related

- Phase 1: [ad-elastic-detection-lab](https://github.com/robert-palka/ad-elastic-detection-lab) (Active Directory + self-hosted Elastic SIEM)
