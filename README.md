<p align="center">
  <img src="https://geeduzbsatvodnlijqfs.supabase.co/storage/v1/object/public/product-media/c059e319-ea19-4aff-9b6c-39797f90a2b4/55f8a434-065c-4e34-af4c-6db711225fb7/logo-1795644317416-0.webp" alt="AgencyDesk Property Management" width="180" height="180" />
</p>

# AgencyDesk Skills — Property Management (Free Sample)

[![skills.sh](https://skills.sh/b/LandrewConsulting/agencydesk-skills-property-management)](https://skills.sh/LandrewConsulting/agencydesk-skills-property-management)
[![Get the full Property Management pack](https://img.shields.io/badge/AgencyDesk_Skills-Get_the_full_Property_Management_pack-28aaaa)](https://landmconsultinginc.com/ai-skills/)
[![Agensi Listing](https://img.shields.io/badge/Agensi-Lease_Abstract-0c182c)](https://agensi.io/skills/lease-abstract)
[![License: MIT](https://img.shields.io/badge/License-MIT-e8a83c)](./LICENSE)

Clerical AI agent skills by **AgencyDesk Skills** (L&M Consulting Inc.). This repository hosts a single free sample from the 7-skill AgencyDesk Property Management pack: **`lease-abstract` (Lease Abstract)** (public free-sample distribution accepted).

Skills follow the open [Agent Skills](https://agentskills.io/) specification. Get the full 7-skill Property Management bundle at the [AgencyDesk Skills Store](https://landmconsultinginc.com/ai-skills/).

## Available Skill

### `lease-abstract` — Lease Abstract

Extracts key terms from a residential or commercial lease (and any supplied amendments or addenda) into a structured clerical review draft:

- **Core lease fields:** captures landlord, tenant, property/unit, effective date, commencement and expiration dates, base rent, security deposit, late fee, notice periods, renter's insurance, pet policy, renewal options, and maintenance/CAM clauses when stated.
- **Exact source citations:** cites document and page or section on every row, and cites both the base lease and any amendment when values differ without resolving conflicts.
- **Explicit gap handling:** labels absent items `Not found in supplied documents` (naming the pages checked) and illegible items `Unclear — unreadable or ambiguous` with zero guessing.
- **Flagged for review & neutral questions:** highlights missing fields and document conflicts and drafts up to five neutral fact-gathering questions for a property manager.

## Installation

Install with the [skills CLI](https://skills.sh/docs/cli):

```bash
npx skills add LandrewConsulting/agencydesk-skills-property-management
```

Or target a specific agent (for example Claude Code or Cursor):

```bash
npx skills add LandrewConsulting/agencydesk-skills-property-management --skill lease-abstract -a claude-code
```

> [!TIP]
> This is a free sample from AgencyDesk Skills. Get the full Property Management bundle and more skills for small businesses and industries at the [AgencyDesk Skills Store](https://landmconsultinginc.com/ai-skills/).

## Example Prompt

```text
Abstract the attached residential lease and First Amendment into a key-terms table with page citations. List any missing standard terms or conflicts between the two documents.
```

## What This Skill Does NOT Do (Clerical Only)

This skill is strictly a clerical document-extraction tool for internal property-management use under qualified supervision:

- Does **not** provide legal advice or opine on whether any lease clause is enforceable, compliant with federal/state/local housing law, favorable, or complete.
- Does **not** make, score, recommend, approve, or deny tenant screening, accommodation, eviction, deposit, or payment decisions.
- Does **not** evaluate consumer reports, draft FCRA adverse-action notices, or determine assistance-animal or reasonable-accommodation eligibility.
- Does **not** repeat Social Security numbers, dates of birth, bank/card numbers, or medical details (all masked as `[on file]`), and must **not** be used as a tenant- or applicant-facing chatbot.
- Every output begins with `Internal use only — Draft for review by a qualified property manager or leasing professional` and requires verification against source documents before any reliance or external use.

## Supported Agents

Compatible with AI agents that support the [Agent Skills](https://agentskills.io/) specification, including **Claude Code**, **Cursor**, **Codex**, **OpenCode**, **Windsurf**, **Cline**, **GitHub Copilot**, **Gemini CLI**, **Roo Code**, and [70+ others](https://github.com/vercel-labs/skills/blob/main/docs/agents.md).

## Skill Structure

```text
skills.sh.json
skills/
  lease-abstract/
    SKILL.md
    references/
      glossary.md
```

## Links

- **AgencyDesk Skills Store (full 7-skill Property Management pack & more):** [https://landmconsultinginc.com/ai-skills/](https://landmconsultinginc.com/ai-skills/)
- **Agensi Listing (`Lease Abstract`):** [https://agensi.io/skills/lease-abstract](https://agensi.io/skills/lease-abstract)

## License

This repository is licensed under the [MIT License](./LICENSE). Skills are provided "as is" without warranty; outputs are clerical drafts only and require review by a qualified property manager or leasing professional before reliance or external use.

---

### More AgencyDesk Skills

Looking for the full 7-skill Property Management pack or more skills for small businesses and industries? Explore all packs at **[landmconsultinginc.com/ai-skills](https://landmconsultinginc.com/ai-skills/)**.

Published by L&M Consulting.
