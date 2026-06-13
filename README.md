# huntflow
Automated Incident Timeline Reconstruction using Protocol SIFT
# HuntFlow

## Automated Incident Timeline Reconstruction using Protocol SIFT

### Overview

HuntFlow is a Digital Forensics and Incident Response (DFIR) project built using Protocol SIFT. The goal of the project is to help investigators automatically reconstruct attack timelines from forensic evidence such as disk images, event logs, browser artifacts, and system metadata.

Instead of manually correlating evidence from multiple forensic sources, HuntFlow automates the process and generates a chronological timeline of suspicious activities, helping analysts understand incidents more efficiently.

## Problem Statement

Incident responders often spend significant time collecting evidence and correlating timestamps from multiple sources to determine how an attack unfolded.

This process is time-consuming and error-prone.

HuntFlow aims to simplify this process by automatically extracting and organizing forensic events into a structured attack timeline.

## Features

* Automated forensic artifact collection
* Event extraction and timestamp normalization
* Timeline reconstruction
* Attack activity correlation
* Technical and executive summary generation
* Protocol SIFT integration

## Technology Stack

* Python
* Protocol SIFT
* SANS SIFT Workstation
* Model Context Protocol (MCP)
* The Sleuth Kit
* Plaso / Log2Timeline
* Volatility
* YARA
* GitHub
* Markdown

## Example Timeline Output

09:02 - Suspicious PDF downloaded

09:03 - PDF executed

09:04 - PowerShell launched

09:05 - Malware installed

09:06 - External network connection detected

## Inspiration

The project was inspired by the need to reduce the manual effort required for forensic timeline reconstruction. By leveraging Protocol SIFT and DFIR tools, HuntFlow helps analysts focus on investigation and decision-making rather than repetitive data collection tasks.

## Future Improvements

* MITRE ATT&CK mapping
* IOC extraction
* Interactive timeline visualization
* Threat intelligence integration
* Multi-host investigations

## Status

Prototype / Hackathon Submission
