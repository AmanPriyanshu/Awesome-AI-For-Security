# Awesome AI for Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, papers, and datasets for applying AI to cybersecurity tasks. This list primarily focuses on modern AI technologies like Large Language Models (LLMs), Agents, and Multi-Modal systems and their applications in security operations.

Found this resource helpful for your security research? Consider adding a star ⭐ to support the ongoing curation effort.

## Contents

- [Related Awesomes Lists](#related-awesomes-lists)
- [Models](#models)
  - [Specialized Security Models](#specialized-security-models)
- [Datasets](#datasets)
  - [Pre-Training Datasets](#pre-training-datasets)
  - [IFT & Capability Datasets](#ift--capability-datasets)
- [Benchmarks & Evaluation](#benchmarks--evaluation)
  - [Vulnerability Assessment](#vulnerability-assessment)
  - [Threat Intelligence](#threat-intelligence)
  - [Offensive Security](#offensive-security)
  - [General Security Knowledge](#general-security-knowledge)
- [Publications](#publications)
  - [Models & Datasets](#models--datasets)
  - [Benchmarking & Evaluations](#benchmarking--evaluations)
  - [Other](#other)
- [Tools & Frameworks](#tools--frameworks)
  - [Adversarial ML](#adversarial-ml)
  - [Security Testing](#security-testing)
  - [Learning Environments](#learning-environments)
- [Security Agents](#security-agents)
  - [Autonomous Agents](#autonomous-agents)
  - [Red Team Agents](#red-team-agents)

## Related Awesomes Lists

Other collections and lists that may be of interest.

- [Awesome AI for Cybersecurity](https://github.com/Billy1900/Awesome-AI-for-cybersecurity) - Earlier comprehensive resource collection, focusing on pre-LLM machine learning applications.
- [Awesome ML for Cybersecurity](https://github.com/jivoi/awesome-ml-for-cybersecurity) - Established resource for traditional ML approaches in security, predating modern LLM era.
- [Awesome AI Security](https://github.com/ottosulin/awesome-ai-security) - Complementary list focusing on AI security rather than AI for security applications.
- [Awesome AI4DevSecOps](https://github.com/awsm-research/Awesome-AI4DevSecOps) - Recent integration of AI technologies within DevSecOps frameworks and methodologies.
- [Awesome-MCP-Security](https://github.com/Puliczek/awesome-mcp-security) - Definitive resource covering all aspects of Model Context Protocol security.

## Models

AI models specialized for security applications and scenarios.

### Specialized Security Models

- [Foundation-Sec-1.1-8B-Instruct](https://huggingface.co/fdtn-ai/Foundation-Sec-1.1-8B-Instruct) - Latest 8B parameter Foundation-Sec model with extended 64k context window, enabling processing of longer security documents and incident reports while maintaining strong performance on cybersecurity tasks.
- [Foundation-Sec-8B-Instruct](https://huggingface.co/fdtn-ai/Foundation-Sec-8B-Instruct) - Instruction-tuned 8B parameter security model, designed as a chat-native copilot for cybersecurity workflows including SOC automation, threat defense, and security engineering.
- [Foundation-Sec-8B](https://huggingface.co/fdtn-ai/Foundation-Sec-8B) - Base 8B parameter model with cybersecurity-specific pretraining, outperforming Llama 3.1 70B on cyber threat intelligence tasks with 10x fewer parameters.
- [Llama-Primus-Base](https://huggingface.co/trendmicro-ailab/Llama-Primus-Base) - Foundation model with cybersecurity-specific pretraining on proprietary corpus.
- [Llama-Primus-Merged](https://huggingface.co/trendmicro-ailab/Llama-Primus-Merged) - Combined model through pretraining and instruction fine-tuning.
- [Llama-Primus-Reasoning](https://huggingface.co/trendmicro-ailab/Llama-Primus-Reasoning) - Reasoning-specialized model enhancing security certification through o1-distilled reasoning patterns.

  
## Datasets

Resources designed for training and fine-tuning AI systems on security-related tasks.

### Pre-Training Datasets

- [Primus-FineWeb](https://huggingface.co/datasets/trendmicro-ailab/Primus-FineWeb) - Filtered cybersecurity corpus (2.57B tokens) derived from FineWeb using classifier-based selection.

### IFT & Capability Datasets
- [Primus-Reasoning](https://huggingface.co/datasets/trendmicro-ailab/Primus-Reasoning) - Cybersecurity reasoning tasks with o1-generated reasoning steps and reflection processes.
- [Primus-Instruct](https://huggingface.co/datasets/trendmicro-ailab/Primus-Instruct) - Expert-curated cybersecurity scenario instructions with GPT-4o generated responses spanning diverse tasks.

## Benchmarks & Evaluation

This section covers frameworks and methodologies for evaluating AI systems within security contexts.

### Vulnerability Assessment

- [AutoPatchBench](https://engineering.fb.com/2025/04/29/ai-research/autopatchbench-benchmark-ai-powered-security-fixes/) - Benchmark for automated repair of fuzzing-detected vulnerabilities, pioneering evaluation standards.
- [SecLLMHolmes](https://github.com/ai4cloudops/SecLLMHolmes) - Automated framework for systematic LLM vulnerability detection evaluation across multiple dimensions.

### Threat Intelligence

- [CTI-Bench](https://huggingface.co/datasets/AI4Sec/cti-bench) - Benchmark suite for evaluating LLMs on cyber threat intelligence tasks.
- [SECURE](https://github.com/aiforsec/SECURE) - Practical cybersecurity scenario dataset focusing on extraction, understanding, and reasoning capabilities.

### Offensive Security

- [NYU CTF Bench](https://github.com/NYU-LLM-CTF/NYU_CTF_Bench) - Dockerized CTF challenges repository enabling automated LLM agent interaction across categories.

### General Security Knowledge

- [CyberSecEval 4](https://meta-llama.github.io/PurpleLlama/CyberSecEval/docs/intro) - Comprehensive benchmark suite for assessing LLM cybersecurity vulnerabilities with multi-vendor evaluations.
- [SecBench](https://huggingface.co/datasets/secbench-hf/SecBench) - Largest comprehensive benchmark dataset distinguishing between knowledge and reasoning questions.
- [MMLU Computer Security](https://huggingface.co/datasets/cais/mmlu/viewer/computer_security?views%5B%5D=computer_security_test) - Standard benchmark with dedicated computer security evaluation subset for general LLMs.
- [MMLU Security Studies](https://huggingface.co/datasets/cais/mmlu/viewer/security_studies?views%5B%5D=security_studies_test) - General benchmark's security studies subset providing broader security knowledge assessment.

## Publications

Academic and industry research on AI applications in security.

### Models & Datasets

- [Foundation-Sec Technical Report](https://huggingface.co/fdtn-ai/Foundation-Sec-8B/blob/main/Technical_Report.pdf) - Detailed methodology for domain-adaptation of Llama-3.1 for cybersecurity applications.
- [Primus Paper](https://arxiv.org/abs/2502.11191) - First open-source cybersecurity dataset collection addressing critical pretraining corpus shortage.

### Benchmarking & Evaluations

- [SecBench Paper](https://arxiv.org/abs/2412.20787) - Multi-dimensional benchmark dataset with unprecedented scale for LLM cybersecurity evaluation.
- [NYU CTF Bench Paper](https://arxiv.org/abs/2406.05590) - First scalable benchmark focusing on offensive security through CTF challenges.
- [SECURE Paper](https://arxiv.org/abs/2405.20441) - Industry-focused benchmark targeting Industrial Control System security knowledge evaluation.
- [CyberMetric Paper](https://arxiv.org/abs/2402.07688) - RAG-based cybersecurity benchmark with human-validated questions across diverse knowledge areas.
- [SecLLMHolmes Paper](https://arxiv.org/abs/2312.12575v3) - Comprehensive analysis revealing significant non-robustness in LLM vulnerability identification capabilities.
- [LLM Offensive Security Benchmarking](https://arxiv.org/abs/2504.10112v1) - Analysis of evaluation methodologies for LLM-driven offensive security tools with recommendations.

### Other

- [OffsecML Playbook](https://wiki.offsecml.com) - Comprehensive collection of offensive and adversarial techniques with practical demonstrations.
- [MCP-Security-Checklist](https://github.com/slowmist/MCP-Security-Checklist) - Comprehensive security checklist for MCP-based AI tools by SlowMist.

## Tools & Frameworks

Software tools that implement AI for security applications.

### Adversarial ML

- [DeepFool](https://github.com/lts4/deepfool) - Simple yet accurate method for generating adversarial examples against deep neural networks.
- [Counterfit](https://github.com/Azure/counterfit) - Automation layer for comprehensive ML system security assessment across multiple attack vectors.
- [Charcuterie](https://github.com/moohax/Charcuterie) - Collection of code execution techniques targeting ML libraries for security evaluation.

### Security Testing

- [garak](https://github.com/leondz/garak/) - Specialized security probing tool designed specifically for LLM vulnerability assessment.
- [promptfoo](https://github.com/promptfoo/promptfoo) - Open-source LLM red teaming tool for finding and fixing vulnerabilities. 100+ attack types, 250k+ users.
- [Snaike-MLFlow](https://github.com/protectai/Snaike-MLflow) - MLflow-focused red team toolsuite for attacking ML pipelines and infrastructure.
- [MCP-Scan](https://github.com/invariantlabs-ai/mcp-scan) - Security scanning tool specifically designed for Model Context Protocol servers.

### Learning Environments

- [Malware Env for OpenAI Gym](https://github.com/endgameinc/gym-malware) - Reinforcement learning environment enabling malware manipulation for AV bypass learning.
- [Deep-pwning](https://github.com/cchio/deep-pwning) - Framework for assessing ML model robustness against adversarial attacks through systematic evaluation.

## Security Agents

AI systems designed to perform security-related tasks with varying degrees of autonomy.

### Autonomous Agents

- [HackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT) - Autonomous pentesting agent with corresponding benchmark dataset for standardized evaluation.
- [Agentic Radar](https://github.com/splx-ai/agentic-radar) - Open-source CLI security scanner for agentic workflows with automated detection.
- [Fraim](https://github.com/fraim-dev/fraim) A flexible framework for security teams to build and deploy AI-powered workflows.

### Red Team Agents

- [HackGPT](https://github.com/NoDataFound/hackGPT) - LLM-powered tool designed specifically for offensive security and ethical hacking.
- [agentic_security](https://github.com/msoedov/agentic_security/) - LLM vulnerability scanner specializing in agentic systems and workflows.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=AmanPriyanshu/Awesome-AI-For-Security&type=Date)](https://www.star-history.com/#AmanPriyanshu/Awesome-AI-For-Security&Date)

## License

[CC0](/LICENSE)
