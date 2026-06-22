# SOAR-EDR-Project
Security, Orchestration, Automation and Response Using Endpoint Detection and Response

## Overview

This project demonstrates a Security Orchestration, Automation, and Response (SOAR) workflow that integrates LimaCharlie (EDR), Tines, and Slack to automate security incident detection, investigation, and response.

The solution continuously monitors endpoint activity through LimaCharlie, which generates alerts when suspicious behavior is detected. These alerts are automatically forwarded to Tines, where automated workflows enrich the event data, perform analysis, and execute predefined response actions. Slack is used as the communication platform to notify security analysts, provide incident details, and facilitate rapid decision-making.

## Key Features

* Real-time endpoint monitoring using LimaCharlie EDR
* Automated alert ingestion and processing
* Security workflow orchestration with Tines
* Instant Slack notifications for detected threats
* Automated incident enrichment and investigation
* Endpoint isolation and response actions
* Reduced manual effort through security automation
* Centralized visibility into security incidents

## Workflow

1. LimaCharlie detects suspicious endpoint activity.
2. Alert data is sent to Tines through API/webhook integration.
3. Tines automatically enriches and analyzes the alert.
4. A notification containing incident details is posted to Slack.
5. Analysts can review the alert and trigger response actions.
6. Automated containment actions such as endpoint isolation can be executed.
7. Incident status and response updates are communicated through Slack.

## Technologies Used

* LimaCharlie EDR
* Tines SOAR Platform
* Slack
* Lazagne(Open source password recovery tool)
* Security Automation Workflows

## Skills Demonstrated

* Security Operations (SOC)
* Endpoint Detection and Response (EDR)
* SOAR Implementation
* Incident Response
* Threat Detection
* Security Automation
* Alert Triage
* API Integration
* Security Monitoring

## Project Goal

The primary goal of this project is to automate the security incident response lifecycle, reducing response times and improving operational efficiency by integrating endpoint detection, workflow automation, and team collaboration platforms.
