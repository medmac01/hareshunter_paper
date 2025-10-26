# HaresHunter Paper

## HARESHUNTER: A Threat Hunting Automation Framework using Collaborative LLM Agents

This repository contains the IEEE paper on HaresHunter, a threat hunting automation framework that leverages collaborative Large Language Model (LLM) agents.

### 📄 Paper

The full paper is available in this repository as [`HaresHunter_IEEE.pdf`](./HaresHunter_IEEE.pdf).

### 🔍 About

HaresHunter is a cutting-edge threat hunting automation framework designed to enhance cybersecurity operations through the use of collaborative LLM agents. The paper presents the architecture, methodology, and evaluation of this novel approach to automated threat detection and hunting.

### 📖 Abstract

Security Operations Center teams face growing challenges as cyber threats become increasingly complex, exceeding the capabilities of manual threat hunting. Current automation solutions provide only partial coverage or require expensive specialized systems, leaving organizations without comprehensive and accessible options for proactive threat detection.
To address these limitations, we introduce HARESHUNTER, a novel framework that leverages Large Language Models and conversational agents to provide end-to-end automation of the Cyber Threat Hunting cycle through two primary modules: the Knowledge Fusion Module, which centralizes threat intelligence with security telemetry data, and the Threat Profiling & Mitigation Module, which deploys three specialized conversational agents (Hypothesis, Investigation, and Mitigation) to hunt and neutralize threats. Our prototype implements base versions of DeepSeek R1 and Codestral to drive our experiments, achieving an 84% hunt success rate across 26 attack scenarios drawn from a public dataset. HARESHUNTER demonstrates an end-to-end threat hunting automation solution with practical applicability in operationally realistic cybersecurity settings.

### 📚 Citation

If you use this work in your research, please cite:

```bibtex
@inproceedings{hareshunter,
  title={HARESHUNTER: A Threat Hunting Automation Framework using Collaborative LLM Agents},
  author={[Mohammed Machrouh, Zakaria Yartaoui, Mohammed Akallouch, Ismail Berrada]},
  booktitle={IEEE},
  year={2024}
}
```

### 📂 Repository Contents

- `HaresHunter_IEEE.pdf` - The complete IEEE paper
- `README.md` - This file


---