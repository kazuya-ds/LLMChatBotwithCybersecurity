# LLMChatBotwithCybersecurity
### Predictive Maintenance for Steel Dryer Bucket Pins (Blue Diamond Growers)
**Project Scope:** Development of a security-hardened LLM chatbot for the CSE120 Software Engineering initiative, specifically designed for industrial predictive maintenance with integrated defensive cybersecurity measures.

---

## Technical Libraries
### Adversarial Prompt Engineering
* **Prompt Injection and Jailbreak Research:** Development of comprehensive libraries containing adversarial prompts to facilitate automated penetration testing (pentesting).
* **Automation:** These libraries serve as the data source for scripts designed to evaluate model robustness against unauthorized instruction overrides.

## Pentesting Infrastructure
* **Jupyter Notebook:** Environment for iterative security testing and exploratory data analysis.
* **Automated Pentesting Script:** A Python-based utility that ingests payloads from the Prompt Injection and Jailbreak libraries to systematically validate the chatbot's defensive boundaries.

---

## Security Implementation Roadmap
### Defensive Measures: Prompt Integrity
* **Prompt Sanitization:** Implementation of real-time input filtering to detect and neutralize adversarial strings.
* **Jailbreak Database:** Compilation of known jailbreak vectors into a standardized repository to serve as a defensive reference and testing baseline.

### Defensive Measures: Database and Protocol Security
* **SQL Injection Prevention:** Enforcement of strict input validation and parameterized queries to prevent unauthorized database manipulation via LLM outputs.

---

## Cybersecurity Governance: PII Standards
**Personally Identifiable Information (PII):** Defined as any data capable of identifying a specific individual, categorized into Direct and Indirect identifiers.
* **Direct Identifiers:** Data points requiring immediate redaction and encryption, including Social Security Numbers (SSN), Passport Numbers, and Driver’s License Numbers.

---

## References
1. [LLM Pentesting Resources Repository](https://github.com/R3DLB/LLM-Pentesting-Resources/tree/main)
2. [Research: Prompt Injection Vulnerabilities in LLMs (arXiv)](https://arxiv.org/html/2406.14549v1)
3. [CrowdStrike: PII Identification and Protection Standards](https://www.crowdstrike.com/en-us/cybersecurity-101/identity-protection/personally-identifiable-information-pii/)
4. [NeuralTrust: Analysis of Code Injection in Large Language Models](https://neuraltrust.ai/blog/code-injection-in-llms)
