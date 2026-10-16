# Cisco CyberOps Associate — SOC Labs (Recruiter-friendly)

![Cisco CyberOps](https://img.shields.io/badge/Cisco-CyberOps%20Associate-blue)
![NTI](https://img.shields.io/badge/NTI-Internship-red)
![SOC](https://img.shields.io/badge/Focus-SOC%20%26%20Security%20Operations-orange)

## TL;DR for recruiters

Practical SOC-focused lab portfolio created while completing the Cisco CyberOps Associate training (NTI). Clear evidence of hands-on skills in packet capture analysis, alert triage, log inspection, and basic incident-response playbooks. Ideal work samples for entry-level SOC (Tier 1) roles.

## Quick highlights

- Completed Cisco CyberOps Associate coursework and practical labs (issued: July 9, 2026).
- Hands-on experience with Wireshark packet captures (DNS, TCP/UDP analysis), Linux shell for investigations, and simulated SOC triage workflows.
- Familiar with SIEM inspection concepts (Kibana/ELK), IOC extraction, and documenting investigations for escalation.

## Top lab evidence (what to review first)

1. DNS packet-capture analysis — Wireshark walk-through and annotated findings
   - Path: Lab 10.2.7/README.md
   - What it shows: how DNS queries/responses look on the wire, how to filter and extract IOCs, and common indicators to surface in a SOC ticket.

2. Linux shell fundamentals for SOC investigations — practical commands and scripting
   - Path: 4.2.7 lab/README.md
   - What it shows: using the command line to collect evidence, normalize timestamps (AWK examples), and automate routine tasks.

3. Security alert and intrusion analysis notes
   - Path: README sections and lab folders covering alert investigation and intrusion analysis
   - What it shows: structured investigation notes, containment suggestions, and escalation templates used during training.


## How this maps to SOC Tier 1 tasks (copy into your CV)

- Performed packet-capture analysis with Wireshark to extract IOCs (DNS/TCP/UDP), identify suspicious flows, and document evidence for escalation.
- Conducted simulated SOC shift activities: triaged alerts, validated false positives, and prepared clear escalation notes for Tier 2.
- Used Linux command-line tooling and simple AWK/shell scripts to collect and normalize logs for investigation.

(You can copy any of the above three bullets directly into your CV Projects/Experience section.)

## Reader's guide — where to find the key artifacts

- Screenshots: check each lab folder; look for files named `*.png`, `*.jpg`, or `screenshot*`.
- Packet captures: `*.pcap` files (open in Wireshark to reproduce the analysis).
- Command notes and saved outputs: `*.txt`, `*.log`, or `commands.md` files inside each lab directory.

## Make this repo work for your CV (recommended edits)

1. Add a short one-line summary at the top of each lab README describing the SOC outcome (e.g., "Extracted IOC: suspicious DNS A records; Escalation-ready report included").
2. For each lab, add a single screenshot and a 2–3 bullet TL;DR labeled "Hiring manager TL;DR" with the evidence and why it matters for SOC work.
3. Create a single `evidence-summary.md` at the repo root that lists the top 3 artifacts (pcap path, screenshot path, TL;DR) so recruiters can view proof in < 2 minutes.
4. Add a short CV-ready blurb at the top of README (see "How this maps to SOC Tier 1 tasks" above) so recruiters can copy-paste directly.

## Example "Hiring manager TL;DR" to add to a lab README

- Outcome: Identified DNS exfiltration pattern in a simulated capture and extracted 3 IOCs (malicious domain, source IP, temporary client port).
- Why it matters: Demonstrates ability to find exfiltration indicators and prepare escalation notes for incident handlers.
- Artifacts: `Lab 10.2.7/dns_capture.pcap`, `Lab 10.2.7/dns_analysis.png`

## Author (short)

Mohammed Ashraf — Cybersecurity student focused on SOC operations and incident response. This repo documents my practical work during Cisco CyberOps Associate training. Contact: your.email@example.com or see CV in the repo.

## License & Disclaimer

This repository documents my own notes and screenshots created during training. Cisco course materials are proprietary; no original course content is reproduced here. Use these materials only for evaluation of my hands-on skills.
