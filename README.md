# Test Suites and Test Cases
AttackForge helps you to track your security testing performed on any assessment or project.
This is achieved using Test Cases which are assigned to a project, and can be further assigned to individual testers and/or scope assets.

Every Test Case on the project can help to guide you on what needs to be tested, how it should be tested, and help you to store and capture testing evidence and artefacts.

A Test Suite is made up of a collection of Test Cases which are relevent to the Test Suite.

For example, a Test Suite might be "Web Application Pentest" and a Test Case on this Test Suite might be "Verify that request throttling is in place to prevent automated attacks against common authentication attacks such as brute force attacks or denial of service attacks."

AttackForge already comes pre-loaded with many Test Suites from industry methodologies such as OWASP, OSSTMM, NIST and more.

This repository provides additional industry methodologies you can import into your AttackForge tenant.
The following methodologies are supported:

## Red Teaming
- [MITRE ATT&CK Enterprise Version 16.1](https://github.com/AttackForge/TestSuites/blob/main/MITRE/ATT%26CK/ENTERPRISE/mitre_attack_enterprise_16_1.json) - see [recommended mapping](https://support.attackforge.com/attackforge-enterprise/modules/test-suite-builder#import-mappings)
- [MITRE ATT&CK Mobile Version 16.1](https://github.com/AttackForge/TestSuites/blob/main/MITRE/ATT%26CK/MOBILE/mitre_attack_mobile_16_1.json) - see [recommended mapping](https://support.attackforge.com/attackforge-enterprise/modules/test-suite-builder#import-mappings)
- [MITRE ATT&CK ICS Version 16.1](https://github.com/AttackForge/TestSuites/blob/main/MITRE/ATT%26CK/ICS/mitre_attack_ics_16_1.json) - see [recommended mapping](https://support.attackforge.com/attackforge-enterprise/modules/test-suite-builder#import-mappings)
- [OSSTMM Version 3 - Human Security Testing](https://github.com/AttackForge/TestSuites/blob/main/OSSTMM/v3/Chapter%207/osstmm_human_security_testing.json)
- [OSSTMM Version 3 - Physical Security Testing](https://github.com/AttackForge/TestSuites/blob/main/OSSTMM/v3/Chapter%208/osstmm_physical_security_testing.json)

## Artifical Intelligence (AI)
- [MITRE ATLAS Version 4.8.0](https://github.com/AttackForge/TestSuites/blob/main/MITRE/ATLAS/mitre_atlas_4.8.0_testcases.json)

## Desktop Applications
- [OWASP Desktop App Security Top 10 2021](https://github.com/AttackForge/TestSuites/blob/main/OWASP/Top%2010/OWASP-Desktop-App-Security-Top-10-2021.json)

## Operational Technology (OT)
- [OWASP Operational Technology (OT) Top 10 2025](https://github.com/AttackForge/TestSuites/blob/main/OWASP/Top%2010/OWASP-Operational-Technology-(OT)-Top-10-2025)

## Web Application & API
- [OWASP Web Security Testing Guide Version 4.2](https://github.com/AttackForge/TestSuites/blob/main/OWASP/WSTG/v4.2/owasp_wstg.json)
- [OWASP Application Security Verification Standard (ASVS) Version 4 - Level 1](https://github.com/AttackForge/TestSuites/blob/main/OWASP/ASVS/v4/Level%201/owasp_asvs_level_1.json)
- [OWASP Application Security Verification Standard (ASVS) Version 4 - Level 2](https://github.com/AttackForge/TestSuites/blob/main/OWASP/ASVS/v4/Level%202/owasp_asvs_level_2.json)
- [OWASP Application Security Verification Standard (ASVS) Version 4 - Level 3](https://github.com/AttackForge/TestSuites/blob/main/OWASP/ASVS/v4/Level%203/owasp_asvs_level_3.json)
- [OWASP Web Application Security Top 10 2021](https://github.com/AttackForge/TestSuites/blob/main/OWASP/Top%2010/OWASP-Web-Application-Top-10-2021.json)
- [OWASP API Security Top 10 2023](https://github.com/AttackForge/TestSuites/blob/main/OWASP/Top%2010/OWASP-API-Security-Top-10-2023.json)

## Mobile Application
- [OWASP Mobile Application Security Testing Guide (MASTG) Version 2 2025](https://github.com/AttackForge/TestSuites/blob/main/OWASP/MASTG/v2/OWASP-Mobile-Application-Security-Testing-Guide-(MASTG)-Version-2-2025)
- [OWASP Mobile Top 10 2024](https://github.com/AttackForge/TestSuites/blob/main/OWASP/Top%2010/OWASP-Mobile-Top-10-2024.json)
- [MITRE ATT&CK Mobile Version 16.1](https://github.com/AttackForge/TestSuites/blob/main/MITRE/ATT%26CK/MOBILE/mitre_attack_mobile_16_1.json) - see [recommended mapping](https://support.attackforge.com/attackforge-enterprise/modules/test-suite-builder#import-mappings)

## Network Infrastructure, Hardware and IOT
- [OSSTMM Version 3 - Telecommunications Security Testing](https://github.com/AttackForge/TestSuites/blob/main/OSSTMM/v3/Chapter%2010/osstmm_telecommunications_security_testing.json)
- [OSSTMM Version 3 - Data Networks Security Testing](https://github.com/AttackForge/TestSuites/blob/main/OSSTMM/v3/Chapter%2011/osstmm_data_networks_security_testing.json)
- [OSSTMM Version 3 - Wireless Security Testing](https://github.com/AttackForge/TestSuites/blob/main/OSSTMM/v3/Chapter%209/osstmm_wireless_security_testing.json)
- [MITRE ATT&CK ICS Version 16.1](https://github.com/AttackForge/TestSuites/blob/main/MITRE/ATT%26CK/ICS/mitre_attack_ics_16_1.json) - see [recommended mapping](https://support.attackforge.com/attackforge-enterprise/modules/test-suite-builder#import-mappings)

## Cloud Configuration
- [CIS Amazon Web Services Foundation v1.2.0](https://github.com/AttackForge/TestSuites/blob/main/AWS/CIS-Amazon-Web-Services-Foundation-v1.2.0.json)
- [CIS Microsoft Azure Foundation v1.2.0](https://github.com/AttackForge/TestSuites/blob/main/AZURE/CIS-Microsoft-Azure-Foundation-v1.2.0.json)
- [CIS Google Cloud Platform Foundation v1.1.0](https://github.com/AttackForge/TestSuites/blob/main/GCP/CIS-Google-Cloud-Platform-Foundation-v1.1.0.json)
- [Oracle Cloud Infrastructure](https://github.com/AttackForge/TestSuites/blob/main/OCI/Oracle-Cloud-Infrastructure.json)
- [Kubernetes Infrastructure](https://github.com/AttackForge/TestSuites/blob/main/KUBERNETES/Kubernetes-Infrastructure.json)

## CI/CD
- [OWASP Top 10 CI/CD Security Risks 2023](https://github.com/AttackForge/TestSuites/blob/main/OWASP/Top%2010/OWASP-Top-10-CI-CD-Security-Risks-2023.json)

## Low Code/No Code
- [OWASP Low Code/No Code Top 10 2024](https://github.com/AttackForge/TestSuites/blob/main/OWASP/Top%2010/OWASP-Low-Code-No-Code-Top-10-2024.json)

You can load additional testing methodologies in the form of Test Cases which can be imported on your Test Suites using the import options on Test Cases:

<img width="2053" alt="1" src="https://github.com/AttackForge/TestSuites/assets/131424301/f4ce8ce8-4a8f-4757-9d51-700fcdef7036">

<img width="2055" alt="2" src="https://github.com/AttackForge/TestSuites/assets/131424301/94ce1a1d-f190-4553-8e8d-56c1bab5dd18">

<img width="2055" alt="3" src="https://github.com/AttackForge/TestSuites/assets/131424301/b35409a2-3669-42b8-8bbf-f7b6851527f3">

<img width="2054" alt="4" src="https://github.com/AttackForge/TestSuites/assets/131424301/b707f6aa-767b-452e-bf43-3d3afaf1c86c">

<img width="2054" alt="5" src="https://github.com/AttackForge/TestSuites/assets/131424301/7de64779-9442-471c-b085-f0ffe8a4a5ab">

<img width="2052" alt="6" src="https://github.com/AttackForge/TestSuites/assets/131424301/319ef41e-27f0-483f-8ee1-562a0ab5c719">

<img width="2053" alt="7" src="https://github.com/AttackForge/TestSuites/assets/131424301/e4e1d42d-b83c-434f-a133-946ab59cf83a">


