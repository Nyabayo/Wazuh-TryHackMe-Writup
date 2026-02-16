# Wazuh EDR TryHackMe Room Write-up

Welcome to my write-up on Wazuh, an open-source and enterprise-ready endpoint detection and response (EDR) solution. In this repository, I cover the practical steps of deploying Wazuh, managing agents, performing vulnerability assessments, and monitoring security events.

## Table of Contents

- [Introduction](#introduction)
- [Wazuh Server Deployment](#wazuh-server-deployment)
- [Wazuh Agents](#wazuh-agents)
- [Vulnerability Assessment & Security Events](#vulnerability-assessment--security-events)
- [Policy Auditing](#policy-auditing)
- [Monitoring Logons with Wazuh](#monitoring-logons-with-wazuh)
- [Collecting Windows Logs with Wazuh](#collecting-windows-logs-with-wazuh)
- [Collecting Linux Logs with Wazuh](#collecting-linux-logs-with-wazuh)
- [Wazuh API Integration](#wazuh-api-integration)
- [Generating Reports with Wazuh](#generating-reports-with-wazuh)
- [Sample Data Loading](#sample-data-loading)

## Introduction

Wazuh provides an extensive EDR solution that can monitor devices for threats, vulnerabilities, and suspicious activities. This room focuses on deploying and configuring Wazuh agents, performing vulnerability scans, and integrating with Sysmon and auditd for log collection. It is designed for both Linux and Windows environments.

## Wazuh Server Deployment

This section walks you through the process of deploying a Wazuh management server. You'll learn how to configure the server, log in to the web interface, and start managing agents.

## Wazuh Agents

Learn how to deploy agents on various devices to collect logs and security events. The agents offload logs to the Wazuh server for processing and analysis.

## Vulnerability Assessment & Security Events

Wazuh’s vulnerability assessment module allows you to scan the agents for installed applications and versions, comparing them to a database of CVEs to detect potential vulnerabilities. This section covers configuring the vulnerability scanner and analyzing security event logs.

## Policy Auditing

In this section, we explore Wazuh's ability to audit agent configurations against multiple standards and frameworks like NIST, MITRE ATT&CK, and GDPR. It’s essential for compliance monitoring and proactive security assessments.

## Monitoring Logons with Wazuh

Wazuh’s monitoring tools capture both successful and unsuccessful login attempts, providing insights into authentication activities on devices. This section demonstrates how to configure and review login attempts.
<img width="1461" height="395" alt="image" src="https://github.com/user-attachments/assets/699c186b-79cd-4187-8e98-6497543eab66" />

<img width="401" height="411" alt="image" src="https://github.com/user-attachments/assets/5ff4fb50-989e-425a-9185-b910ab6b269c" />


## Collecting Windows Logs with Wazuh

Learn how to collect and analyze Windows event logs, including authentication attempts, network connections, and application behaviors using Sysmon, a key tool for monitoring Windows events.

## Collecting Linux Logs with Wazuh

This section focuses on the collection and analysis of Linux logs, such as Apache2 web server logs, using the built-in log collector module in Wazuh.

## Wazuh API Integration

The Wazuh API allows you to interact with the management server programmatically. This section covers how to authenticate using API tokens and perform operations like retrieving agent statuses and server information.

## Generating Reports with Wazuh

Wazuh’s reporting feature enables you to generate detailed summaries of security events. This section explains how to create reports and download them for further analysis.

## Sample Data Loading

Learn how to load sample data into your Wazuh management server to explore more extensive datasets and test the platform’s capabilities.
