![GRCMANA](/profile/assets/grcmana_banner.png)

# Trust is market access. Engineer it to hold.

I'm Harry West, Trust Architect: twenty years in cybersecurity, including Global CISO roles. GRCMANA is where I teach GRC Engineering. That means building security and governance that run all year and leave their own evidence, so you can prove trust whenever a buyer, auditor or regulator asks, not just in audit week.

This is where that engineering lives as code. Everything here is free, open source and yours to fork.

## Why this exists

A customer's security questionnaire asks for evidence of your last access review. The review happened. The proof is in someone's inbox, or nowhere.

Enterprise buyers don't read your policies. They sample whether your controls ran, who owned them and what evidence they left.

An evidence trail built by hand decays between audits. One that's engineered holds.

The repos below put an AI agent on the repetitive parts of that work. It works against your own risk register, evidence and approvals, and a named human stays accountable for every decision.

## Start here

| | What it is | Get it |
| :-- | :-- | :-- |
| **[GRC Skills](https://github.com/grcmana/grcskills)** | Agent skills for company context, risk, policies, evidence, audit readiness, AI impact assessments and DPIAs. Covers ISO 27001, SOC 2, Cyber Essentials, UK and EU GDPR and ISO 42001. Works in Claude Code, Codex, Cursor and any agent that supports Agent Skills. | `npx skills add grcmana/grcskills`<br>[grcskills.io](https://grcskills.io) |
| **[GRC OS](https://github.com/grcmana/grc-os)** | A ready-to-run Claude Code workspace. It bundles every skill with operating instructions, guardrails, a private `grc/` workspace, run logs and a worked example company. | `git clone https://github.com/grcmana/grc-os` |
| **[SkillBOM](https://github.com/grcmana/skillbom)** | A bill of materials for the skills your agents run. It records what's in each skill, what knowledge it was built from and its exact content hash, as a signed CycloneDX file. Check an installed copy against it to see whether anything has changed. Works with any Agent Skills repo, not only GRC Skills. | `pip install "git+https://github.com/grcmana/skillbom@v0.0.1"`<br>[skillbom.io](https://skillbom.io) |

**Just been told a customer needs ISO 27001, SOC 2 or Cyber Essentials?** Start with GRC OS. Work through the example company first, then point it at your own.

**Already running a programme?** Install GRC Skills into the project you already work in.

## How they're built

- **Everything is a file.** Markdown and CSV in a `grc/` folder you control, git-ignored by default. No platform, no lock-in.
- **A human signs off.** The skills never fill in approval fields and never tell you you're "compliant" or "certified".
- **Every AI run is logged.** Each run writes a record of what the agent did, so your use of AI is auditable too.
- **Version-aware knowledge, in my own words.** Clause and control IDs with an `as_of` date. No copyrighted standard text.
- **Drafts, not opinions.** Outputs are for review by a competent person. They aren't audit opinions or legal advice.

These are early releases.

I haven't yet published measured results for them. When I do, they'll go out with each release, failures included.

## Go further

| GRC Pulse | The GRC Collective |
| :--- | :--- |
| A weekly newsletter on GRC Engineering, the framework changes that matter, and what buyers actually check. | A free community for practitioners making trust hold all year. Ask questions, compare approaches and learn GRC Engineering alongside people doing the same job. |
| [Subscribe to GRC Pulse →](https://grcpulse.io) | [Join The GRC Collective →](https://www.skool.com/the-grc-hub-by-grcmana-9174/about) |

## Contribute or report a problem

Each repo has issue forms, and pull requests are welcome. Framework corrections matter most: if a clause reference or requirement looks wrong, raise it in [GRC Skills](https://github.com/grcmana/grcskills/issues/new/choose). Found a security issue? Use private vulnerability reporting on the affected repo, as described in its `SECURITY.md`.

## Elsewhere

[grcmana.com](https://grcmana.com) · [LinkedIn](https://www.linkedin.com/in/harrywest/) · [YouTube](https://www.youtube.com/@grcmana)