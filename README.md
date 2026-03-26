# 🛡️ Toco AI Rules Library

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com)
[![Discord](https://img.shields.io/discord/NubsdbF3MK?label=Discord&logo=discord&color=5865F2)](https://discord.gg/NubsdbF3MK)

Welcome to the official repository for **Toco AI Agent Rules**. 

In the era of Model-Driven Development (MDD), we don't rely on random prompt engineering or "vibe coding". We control AI behavior through strict, hierarchical, and deterministic rule configurations. This repository provides community-tested `.toco` configuration files to help you set up robust constraints for your AI Architect, Planner, and Developer agents.

## 🎯 Why Use These Rules?

- **Enforce Determinism:** Ensure your Developer Agent fills in the 20% glue code securely without breaking the 80% engine-generated structural code.
- **Zero Hallucination:** Prevent AI from inventing non-existent libraries or violating your tech stack constraints.
- **Team Consistency:** Share rules across your organization by committing these templates into your project's version control.

## 📂 Repository Structure

The rules are strictly isolated by Agent roles to prevent context pollution:

```text
├── global/
│   └── common_framework.md     # Global technical specifications & overarching DDD constraints
├── developer/
│   ├── java_spring_rules.md    # Glue-code rules for Java/Spring Boot
│   ├── defensive_coding.md     # Security, null-checks, and boundary conditions
│   └── anti_patterns.md        # Explicit "DO NOT" rules to break AI loops
├── designer/
│   └── read_write_models.md    # Constraints for DTO/VO aggregation and Command/Query separation
└── planner/
    └── task_breakdown.md       # Guidelines for splitting large refactors into atomic APIs
```

## 🚀 How to Use

1. **Select** the rule template that matches your tech stack and current task.
2. **Copy** the `.md` file into the `.toco/` directory at the root of your Toco AI project (e.g., `.toco/developer/rules.md`).
3. **Customize** the constraints (e.g., specific framework versions, internal library names).
4. **Commit** it to your Git repository so your entire team's Toco Agents share the same "brain".

## 🤝 Contribute Your Golden Rules

Have you crafted a rule that completely fixed an AI hallucination? Or a prompt pattern that makes the Developer Agent write flawless concurrent payment logic? 

**We want your rules!** 
1. Fork this repository.
2. Add your rule template to the appropriate folder.
3. Submit a Pull Request.

Let's build the ultimate industrial-grade AI coding standard together.
