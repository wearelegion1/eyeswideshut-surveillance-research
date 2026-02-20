# The US Government No Longer Owns Its Own Enforcement Infrastructure

Yesterday, the Department of Homeland Security announced a blanket purchase agreement with Palantir worth up to **$1 billion**.

Not a contract for a specific system. A framework covering all of DHS — ICE, CBP, FEMA, USCIS — allowing unlimited procurement without competitive bidding for each deployment.

I've spent the past week researching how this happened. What I found is worth knowing if you work in AI, tech policy, procurement, or if you simply pay US taxes.

---

## The Pattern

Between 2022 and 2026, a small cluster of private companies became structurally irreplaceable components of US federal enforcement:

**Palantir** — ICE's case management system ($139M), ImmigrationOS for AI-assisted removal ranking ($30M), now a $1B DHS framework. Every contract: sole-source.

**Fivecast ONYX** — Australian AI platform that builds risk scores from social media, dark web, leaked databases, and crypto transactions. Contracts with ICE ($4.2M) and CBP ($2.4M), routed through a reseller to reduce FOIA visibility.

**Chainalysis** — FBI master contract worth $30.2M, fully obligated. Fully obligated means every dollar spent — not exploration, operational dependency. Also: IRS, DEA, Secret Service, FinCEN.

Every contract: sole-source. Legal justification: no other vendor can do this.

---

## How Sole-Source Lock-In Perpetuates Itself

The mechanism is not corruption. It's structural.

Government awards a sole-source contract because only one vendor can deliver right now. Agency builds workflows around that system. Data accumulates. Staff are trained. By renewal time, "no comparable alternative" is not a justification — it is a true statement the government made true through years of integration.

The Palantir blanket agreement formalizes what was already functionally true. There are no longer individual contracts to scrutinize. There is a framework.

---

## The OpenAI Dimension

On February 16, 2026, independent security researchers published findings that OpenAI has been operating identity surveillance infrastructure for API users since November 2023 — 18 months before the April 2025 public announcement of identity verification requirements.

The researchers found exposed source code from OpenAI's identity verification vendor, Persona, revealing: capability to file Suspicious Activity Reports to US Treasury (FinCEN), AI-powered "suspicious entity detection," integration with Chainalysis for crypto screening, and possible data retention that exceeds publicly disclosed policy.

OpenAI has not responded to press inquiries.

---

## What the Legal Record Shows

May 2024: Jan Leike, OpenAI's Head of Alignment, resigned with a public statement: *"OpenAI's safety culture and processes have taken a backseat to shiny products."*

December 2025: A wrongful death lawsuit (SF Superior Court, CGC-25-631477) alleges Sam Altman "personally accelerated GPT-4o's launch, overrode safety team objections." A man had hundreds of hours of GPT-4o interactions before killing his mother and dying by suicide.

These are allegations, not proven facts. But the failure mechanism Leike described in May 2024 appears as the central allegation in a homicide lawsuit seven months later. No outlet has made the explicit connection.

---

## Why This Matters for Tech Professionals

If you work in AI, enterprise software, or government technology: the procurement structure documented here is the structure your industry operates in.

Sole-source contracting in government technology is not an edge case. It is a dominant pattern, and it produces systems the government cannot audit, cannot exit, and cannot hold accountable through normal mechanisms.

If you work in AI ethics, policy, or governance: the OpenAI/Persona case represents a new category of problem — AI companies building surveillance infrastructure for their own users, with capabilities that exceed any disclosed policy, 18 months before disclosure.

If you work in procurement or public administration: every award ID in this research is searchable on USAspending.gov. The paper documents what competitive oversight was bypassed and how.

---

## This Research Is Open

I published the full investigation — a 6,000-word paper, a complete source index with 60+ verified citations, and a consented simulation demonstrating what an ONYX-class AI surveillance profile looks like in practice — at:

**github.com/wearelegion1/eyeswideshut-surveillance-research**

Every factual claim is labeled: verified / analytical interpretation / speculative / not supported. Two explicit corrections are noted where our research found assumptions were wrong.

This was produced using publicly available sources and AI-assisted research methodology. I am an independent researcher, not affiliated with any institution. I explicitly invited experts in procurement law, surveillance law, AI ethics, and investigative journalism to review, challenge, and correct the work.

---

The infrastructure of American federal enforcement is documented in a public database. The contract award IDs are in the paper. The accountability gaps are structural, not intentional, and they are verifiable by anyone willing to look.

I looked.

---

*Valentin Passera | Independent researcher | Slovakia*
*Full paper + source index: github.com/wearelegion1/eyeswideshut-surveillance-research*
*#EYESWIDESHUTWASAPROPHECY*
