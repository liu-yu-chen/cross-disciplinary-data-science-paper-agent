# Cross-Disciplinary Data Science Paper Agent

**A bilingual (English/简体中文) Codex skill for evidence-based, reproducible, cross-disciplinary data science research and paper writing.**

This repository packages the workflow as an installable skill. It guides an agent from project scoping and data audit through literature synthesis, design, model experiments, interpretation, writing, review, and reproducibility. It does not promise automatic publication or replace domain experts, statisticians, ethics review, or human approval at decision gates.

## Languages

- [English skill](cross-disciplinary-data-science-paper-agent/SKILL.md)
- [简体中文技能](cross-disciplinary-data-science-paper-agent/SKILL.zh-CN.md)

The skill metadata is in English for reliable discovery. Both language files carry the same workflow and safeguards. The agent should follow the user's language preference for discussion and deliverables.

## Install

Copy the `cross-disciplinary-data-science-paper-agent` directory into your Codex skills directory (commonly `~/.codex/skills/`). Keep both skill files together. Restart or refresh Codex if the skill list is cached.

## Use

Ask Codex to use `cross-disciplinary-data-science-paper-agent` for a cross-disciplinary data science study or paper. Provide the research domain, available data, target outcome/question, constraints, and intended venue when known. The skill begins with a scoped audit and asks for human decisions at consequential gates.

## Workflow at a glance

1. Initialize project constraints and ethics/data access.
2. Audit data, quality, leakage, and cleaning decisions.
3. Search literature and time-sensitive evidence; build a traceable matrix.
4. Generate and score research topics, then pre-register the design.
5. Engineer features and dynamically justify model candidates.
6. Freeze the experiment plan before model selection; reserve the test set.
7. Evaluate robustness, uncertainty, interpretability, and external validity.
8. Build evidence-linked figures/tables and write the required manuscript structure.
9. Review claims, limitations, references, and the reproduction package.

## License

MIT. See [LICENSE](LICENSE).
