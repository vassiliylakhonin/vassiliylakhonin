# Vassiliy Lakhonin

I build tools that check evidence in AI outputs and verify signed permissions for proposed agent actions. I also develop analysis skills for policy and transport decisions that a human reviewer can audit.

## AI evidence and authorization

| Project | Use it for | Try or verify |
| --- | --- | --- |
| [Agenda Intelligence MD](https://github.com/vassiliylakhonin/agenda-intelligence-md) | Flag missing citations, altered quotes and unsupported numbers in AI output using the source text you supply. | [Try the fictional citation check](https://output-verification.agendamcp.dpdns.org/#one-claim-review) · [Run locally with Python](https://github.com/vassiliylakhonin/agenda-intelligence-md#first-run) |
| [Vizier](https://github.com/vassiliylakhonin/vizier) | Check a proposed tool call against signed permissions and inspect the authorization decision and its request-bound receipt. | [Try the missing-grant example](https://vizier.agendamcp.dpdns.org/playground#missing-grant) · [Verify the receipt and tamper checks locally](https://github.com/vassiliylakhonin/vizier/blob/main/docs/FIRST_BLOCK.md) |

[Review your own answer](https://output-verification.agendamcp.dpdns.org/#raw-answer) · [Connect Agenda via MCP or A2A](https://github.com/vassiliylakhonin/agenda-intelligence-md/blob/main/docs/deployment/output-verification-first-check.md) · [Guard a Worker release with Vizier](https://vizier.agendamcp.dpdns.org/playground#guard-one-release).

## Policy and corridor analysis

These installable skills structure a decision memo around evidence, assumptions, open questions and human review. Each repository records its validation and limits.

| Skill | Use it for | Start here |
| --- | --- | --- |
| [Global Think Tank Analyst](https://github.com/vassiliylakhonin/global-think-tank-analyst) | Compare policy options, scenarios and the evidence that could change a decision. | [Install the skill](https://github.com/vassiliylakhonin/global-think-tank-analyst#start-with-the-skill) · [Worked examples](https://github.com/vassiliylakhonin/global-think-tank-analyst/blob/main/examples/README.md) |
| [Central Asia & Caspian](https://github.com/vassiliylakhonin/central-asia-caspian-hybrid-intelligence-skill) | Analyze trade routes, banking relationships, ownership and energy exposure in Central Asia and the Caspian. | [Install the skill](https://github.com/vassiliylakhonin/central-asia-caspian-hybrid-intelligence-skill#start-with-the-skill) · [Worked examples](https://github.com/vassiliylakhonin/central-asia-caspian-hybrid-intelligence-skill/blob/main/examples/README.md) |
| [Gulf & Middle East](https://github.com/vassiliylakhonin/gulf-middle-east-hybrid-intelligence-skill) | Analyze Gulf banking, energy flows and maritime chokepoints. | [Install the skill](https://github.com/vassiliylakhonin/gulf-middle-east-hybrid-intelligence-skill#start-with-the-skill) · [Worked examples](https://github.com/vassiliylakhonin/gulf-middle-east-hybrid-intelligence-skill/blob/main/examples/README.md) |

Using Codex? Try the [Global Think Tank Analyst standalone skill](https://github.com/vassiliylakhonin/global-think-tank-analyst/blob/main/codex/SKILL.md). For the regional skills, load the base `SKILL.md` and the matching Codex overlay for [Central Asia & Caspian](https://github.com/vassiliylakhonin/central-asia-caspian-hybrid-intelligence-skill/blob/main/runtimes/codex/SKILL.md) or [Gulf & Middle East](https://github.com/vassiliylakhonin/gulf-middle-east-hybrid-intelligence-skill/blob/main/runtimes/codex/SKILL.md). [Agenstry Skills Library](https://agenstry.com/skills/library?kind=skill_md&q=vassiliylakhonin)

For a shipment question, the [Corridor & Sanctions Risk Assistant](https://corridor-sanctions-assistant.agendamcp.dpdns.org/) shows which specialist to use and which records to gather. For a project document, read the [fictional Corridor Bankability sample](https://corridor.agendamcp.dpdns.org/start#sample) with a claim ledger and open questions for the reviewer.

## Case studies and protocol work

- [Halyk Agentic Challenge](https://github.com/vassiliylakhonin/halyk-agentic-challenge). Banking-document competition entry. Run a synthetic covenant calculation offline via [the quick start](https://github.com/vassiliylakhonin/halyk-agentic-challenge#quick-start), then read [what changed between the open and hidden evaluations](https://github.com/vassiliylakhonin/halyk-agentic-challenge/blob/main/docs/results-and-design.md).
- [Vizier4Dev](https://github.com/vassiliylakhonin/vizier4dev). Bilingual grant-reporting prototype. [Try it on fictional data](https://vizier4dev.pages.dev/) to trace a figure to its source and prepare a donor handover.
- [AEP delivery-digest vectors](https://github.com/vassiliylakhonin/aep-delivery-digest-vector). Two external application-profile fixtures for delivery evidence, with a [local verifier](https://github.com/vassiliylakhonin/aep-delivery-digest-vector#verify) and the [upstream discussion](https://github.com/A-Comm-Tech/a-comm-evidence-protocol/discussions/114).
- [Agent payments research](https://github.com/vassiliylakhonin/agent-payments-research). Research fork with drafts on evidence for payment disputes and delivery.
- [Delivery-conformance vectors for x402 ext-delivery](https://github.com/ak68a/agent-payments-research/pull/4). Merged contribution: four synthetic test cases (digest and schema pass or fail) for a delivery-evidence check, with a small verifier script. It tests hashes and schemas only, not payments or demand.

<details>
<summary>Specialist review tools and Agenstry catalog</summary>

Choose the specialist that matches your evidence and the decision under review.

| Your task | Agent |
| --- | --- |
| Prepare a strategic-risk memo for a reviewer | [Agenda Intelligence MD](https://agenstry.com/agents/agendamcp.dpdns.org) |
| Check identity and delegation evidence for an external agent request | [Agentic Interaction Trust Gate](https://agenstry.com/agents/interaction-trust.agendamcp.dpdns.org) |
| Prepare a transaction for a human signing review | [Agent Financial Guard](https://agenstry.com/agents/agent-financial-guard.agendamcp.dpdns.org) |
| Compare delivery evidence with an agreed hash and deadline | [Escrow Delivery Evidence Review](https://agenstry.com/agents/m2m-escrow-arbiter.agendamcp.dpdns.org) |
| Find document gaps in a Middle Corridor shipment file | [Middle Corridor Deal Risk Gate](https://agenstry.com/agents/middle-corridor-deal-risk-gate.agendamcp.dpdns.org) |
| Gather ownership and dated screening records for a counterparty | [CIS Secondary-Sanctions Exposure](https://agenstry.com/agents/cis-secondary-sanctions.agendamcp.dpdns.org) |
| Find vessel, voyage and insurance document gaps | [Gulf Maritime Exposure Gate](https://agenstry.com/agents/gulf-maritime-exposure.agendamcp.dpdns.org) |
| Gather partner, permit and launch evidence for Kazakhstan | [Kazakhstan Market-Entry Readiness Gate](https://agenstry.com/agents/kazakhstan-market-entry-readiness.agendamcp.dpdns.org) |
| Find origin, ownership and traceability gaps in an offtake dossier | [Critical Minerals Due Diligence Gate](https://agenstry.com/agents/critical-minerals-due-diligence.agendamcp.dpdns.org) |
| Review supplied classification, end-use and route evidence | [Dual-Use Technology & Export Controls Gate](https://agenstry.com/agents/dual-use-technology-export.agendamcp.dpdns.org) |

[Full Agenstry catalog and technical status](https://agenstry.com/providers/Vassiliy%20Lakhonin)

</details>

## Before connecting

- The examples use fictional inputs. Agenda checks the structure of supplied evidence for human review.
- With Vizier, your authenticated integration applies the authorization result before the tool runs.
- Corridor routing is free. Specialist checks have their own access terms. Corridor Bankability tool calls require an operator-issued bearer key.
