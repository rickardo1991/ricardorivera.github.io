---
layout: page
title: "Elastic ECK SIEM at Scale"
description: "Designing and operating multi-SIEM architecture (Elastic, Splunk, QRadar) with ECK, achieving 20M+ events per minute ingestion without loss."
permalink: /projects/elastic-eck-siem/
---

### Overview
This project demonstrates a hybrid SIEM platform deployed on **Elastic Cloud on Kubernetes (ECK)**, built to handle **>20 million events per minute** across multiple business units while maintaining zero data loss and optimized storage.

### Highlights
- Multi-SIEM integration with **Elastic, Splunk, and QRadar** for comparative performance.
- Buffering and backpressure via Kafka → Logstash → Elastic ingestion pipeline.
- **Custom parsing taxonomy** for 1,500+ sources.
- **Tiered storage model** reducing hot storage usage by 60%.
- **SOAR integration** using TheHive for automated triage and case enrichment.
- Architecture aligned with **MITRE ATT&CK** and **ISO 27002** controls.

### Stack
- **Elastic ECK**, Kubernetes, Helm
- **Kafka, Logstash, Beats**
- **Terraform, Ansible, GitHub Actions**
- **Azure Monitor, Event Hubs**
- **TheHive, Cortex Analyzer**

### Impact
- **Scalability:** Stable ingestion >20M EPS.
- **Cost Efficiency:** 40% lower infra cost via optimized tiering.
- **MTTR:** Reduced by 45% through automation playbooks.

---
**Author:** Ricardo Rivera  
**Location:** Zurich, Switzerland  
