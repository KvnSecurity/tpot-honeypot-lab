# T-Pot Honeypot Lab 🍯

This repository contains detections, dashboards, and analysis
for a honeypot deployed using **T-Pot** and integrated with **Elastic Stack**.

## 🛠 Stack
- T-Pot (Cowrie, Dionaea, Suricata, etc.)
- Elastic Stack (Kibana / Elasticsearch)
- GeoIP enrichment enabled

## 🎯 Goals
- Capture real-world attacker behavior
- Detect brute force, scans, and exploitation attempts
- Build reusable Elastic KQL detections and alerts

## 📊 Contents
- `detections/kql/` → KQL hunting queries
- `dashboards/` → Kibana dashboards


⚠️ **Disclaimer:** This honeypot is for research and educational use only.



## Overview

I decided to let this honeypot run for 36 hours to see what information I can gain in that short amount of time.
Within 2 minutes I bagan to get alerts that my honeypot was being attacked.

## This screenshot was captured as soon as I deployed the honeypot
<img width="1774" height="772" alt="Screenshot 2026-01-29 at 11 40 13 PM" src="https://github.com/user-attachments/assets/729df03d-1132-4168-95a5-623b6122abc2" />


## Shortly after the attacks and data began rolling in.

<img width="1791" height="111" alt="Screenshot 2026-01-29 at 11 41 23 PM" src="https://github.com/user-attachments/assets/de2a5b12-58c1-4127-be53-e5c82aca28a4" />

## 24 hours later I decided to log back into the honeypot's dashboard to check for any updates
The amount of alerts caught me off gaurd. I saw over 19,000 honeypot attacks!


<img width="1826" height="517" alt="Screenshot 2026-01-30 at 6 22 53 PM" src="https://github.com/user-attachments/assets/43fc654c-4a8c-47ed-bfad-0bfed7b1a644" />


<img width="3251" height="1049" alt="Screenshot 2026-01-31 at 9 36 35 AM" src="https://github.com/user-attachments/assets/280297e2-8caf-44f3-b647-5bb717d4d993" />

## I then checked again the following morning and found over FORTY THOUSAND attacks!!





