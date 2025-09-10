# SOC Home Lab Setup

End-to-end SOC home lab for hands-on log collection, analysis, and alerting.

## Setup Overview
- Windows 10 VM with Sysmon installed
- Splunk Universal Forwarder on Windows
- Splunk Enterprise on Ubuntu (Indexer + Search Head)
- Logs collected: Windows Event Logs, Sysmon logs
- Log forwarding from Windows to Ubuntu over TCP

## Architecture
[Windows 10] ── Sysmon
       
       │  
       ▼  
[Splunk Universal Forwarder] ──▶ [Splunk Enterprise Server on Ubuntu]

## Documentation
Full walkthrough: [Medium Article](https://medium.com/@TraceX0/how-i-built-a-complete-soc-home-lab-from-scratch-66877555336b)
