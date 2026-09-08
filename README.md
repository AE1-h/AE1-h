## Detections that hold up

Cybersecurity — **SOC and detection engineering** first, with binary exploitation
and CTFs as a supporting edge. Built and reasoned about end to end: the rule logic,
the alert triage, and the honest limitations.

### What I work on

- **Detection engineering** — Suricata IDS/IPS, YARA, EVE JSON triage, MITRE ATT&CK mapping
- **Inline prevention** — NFQUEUE-based IPS with receiver-side proof of non-delivery
- **AI output evaluation** — deterministic oracles for LLM-generated IAM policy, AWS/GCP least privilege, mutation-tested graders
- **Binary exploitation** — ROP / SROP, stack pivots, exploit development with pwntools
- **CTFs** — reverse engineering, pwn, crypto, and web

### Selected work

- [suricata-exfil-detection](https://github.com/AE1-h/suricata-exfil-detection) — encrypted-exfiltration detection, inline NFQUEUE prevention, ATT&CK mapping
- [iam-remediation-eval](https://github.com/AE1-h/iam-remediation-eval) — deterministic oracle for LLM-rewritten AWS/GCP IAM policies, graded on escalation and workload integrity
- [YaraRules0x100](https://github.com/AE1-h/YaraRules0x100) — documented, ATT&CK-mapped YARA rules
- [void-htb-writeup](https://github.com/AE1-h/void-htb-writeup) — two-stage SROP exploit and write-up

*Detections are leads, not verdicts — each project states what it does and doesn't prove.*
