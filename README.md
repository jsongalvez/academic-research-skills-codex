# Literary MT Research Skills

A focused set of Codex skills for the Literary MT Research project.

This fork removes the general-purpose academic-writing, manuscript-review, publication, systematic-screening, and large autonomous pipeline features of ARS-Codex. It retains only the research workflows useful to developing high-quality Chinese, Japanese, and Korean literary translation into English.

## Install

Copy `.agents/skills/` into the root of the Literary-MT-Research repository, or copy the individual skill directories into your Codex user skills directory. Start a new Codex session. Invoke a skill by name when automatic selection does not activate it.

## Skills

- **literary-mt-research** — repository-aware research routing and session handoff.
- **literary-mt-source-verification** — verify papers, datasets, models, claims, provenance, and licenses.
- **literary-mt-evidence-synthesis** — synthesize evidence, contradictions, and decision implications.
- **literary-mt-experiment-design** — design falsifiable, reader-centered experiments without running them.

## Source of truth

The Literary-MT-Research repository is authoritative for project mission, evidence, claims, decisions, experiment records, and current work. These skills provide procedures; they do not duplicate project records. Read its `AGENTS.md` and `PROJECT_STATE.md` before acting.

## Upstream

Substantially adapted from [ARS-Codex](https://github.com/Imbad0202/academic-research-skills-codex), itself derived from [Academic Research Skills](https://github.com/Imbad0202/academic-research-skills) by Cheng-I Wu. See [UPSTREAM.md](UPSTREAM.md). The original license is retained in [LICENSE](LICENSE).
