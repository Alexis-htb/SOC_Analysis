# SOC Portfolio Project #1: Incident Triage & Log Analysis - Daikibo Industrials

## 📋 Scenario Background
A major news publication has leaked sensitive private information regarding our client, Daikibo Industrials. Concurrently, a severe production disruption has caused their assembly lines to halt, threatening the smooth operation of global supply chains relying on Daikibo’s products. The client's internal IT team suspects that the security of their newly deployed web-facing status board may have been breached.

## 🎯 Analyst Objectives
As a SOC Analyst assigned to the Incident Response team, my task is to investigate the suspected compromise, establish the attack timeline, and identify the root cause. The core objectives of this investigation are:

1. **Attack Vector Triage:** Determine if the alleged breach was executed by an external threat actor directly from the public internet, specifically ruling out whether the attacker required prior authenticated access to the Daikibo corporate VPN.
2. **Log Forensics:** Ingest and parse the `web_requests.log` artifact. The analysis will focus on filtering, querying, and identifying malicious web traffic patterns within the specific time window of the alleged attack.

## 🛠️ Skills & Concepts Demonstrated
* **Security Operations (SOC):** Incident triage, scoping, and threat vector identification.
* **Log Analysis:** Parsing and analyzing web server logs to detect anomalous behavior and potential web application exploits.
* **Report writing:** Summarizing the information and results obtained while remaining accurate and concise
