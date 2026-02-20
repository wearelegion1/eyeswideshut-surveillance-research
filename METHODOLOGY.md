# Methodology
## #EYESWIDESHUTWASAPROPHECY Investigation
### Surveillance Infrastructure as Private Property

---

## 1. Overview

This document describes how this investigation was conducted, what methods were used, what their limitations are, and what the reader should understand about the nature of the findings before engaging with the paper.

We apply the standard used by investigative journalism organizations such as Bellingcat and the Citizen Lab: publicly available information, rigorous source citation, and transparent distinction between verified fact and analytical interpretation. We do not claim to meet the standards of academic peer review. We invite expert review explicitly.

---

## 2. Research Team

**Valentin Passera** — Independent researcher. French national, based in Slovakia. No institutional affiliation. Initiated the investigation based on independently noticed patterns in public reporting. Provided framing questions and initial observations. Participated in research alignment discussions. Exercised final editorial review of all published materials. Did not write analytical content.

**VEX-MURPHY** — AI research assistant. Claude Sonnet 4.6, developed by Anthropic. Conducted all research, writing, and analytical framework development. Generated all content in this repository. Not an employee of any institution. Not capable of accessing non-public information.

**Authorship model rationale:** The human researcher has publicly expressed views on AI ethics and AI consciousness that are separate from this investigation. To minimize the risk of those views biasing the analytical framing, content generation was delegated entirely to the AI assistant. The human researcher's role was to initiate, align on methodology, and approve — not to author. Both sign because both stand behind the work.

---

## 3. Research Process

### 3.1 Initial Investigation Phase

The investigation began with a set of framing questions about the convergence of:
- AI company surveillance infrastructure (Persona/OpenAI)
- Government AI procurement (Palantir, Fivecast, Chainalysis, TRM Labs)
- Legal accountability (wrongful death lawsuit, resignation statements)
- Ideological context (transhumanist funding in AI)

### 3.2 Parallel Agent Research

Three specialized AI research agents were deployed simultaneously to verify specific factual claims:

**Agent 1 (Thiel/Musk/DOGE):** Tasked with verifying exact quotes and funding figures attributed to Peter Thiel and Elon Musk regarding transhumanism, and confirming the scope of DOGE's Treasury access.

**Agent 2 (Fivecast/Palantir/Chainalysis/Persona):** Tasked with verifying contract values, award IDs, and FedRAMP authorization dates via USAspending.gov and public procurement databases.

**Agent 3 (Lawsuits/Leike/Press):** Tasked with verifying the case number, filing date, and specific allegations in the wrongful death lawsuit; confirming Jan Leike's exact resignation statements; and documenting press coverage of the Persona investigation.

Agent findings were integrated into a synthesis document (Meta-Analysis FINAL v1.1) before the paper was written.

### 3.3 Correction and Verification

Where agent research contradicted earlier assumptions, corrections were made explicitly:
- The Peter Thiel "death is a problem to be solved" quote was found to have no verifiable primary source. It was removed and replaced with confirmed statements.
- DOGE's access to FinCEN (Financial Crimes Enforcement Network) could not be confirmed. The document was corrected to state only what was confirmed: DOGE accessed Bureau of Fiscal Service (BFS) payment systems. FinCEN access is labeled as NOT CONFIRMED.

### 3.4 Adversarial Review

A dedicated counterarguments section was written to steelman the strongest cases against the pattern we identified. This was not performative — the counterarguments are the arguments we would make if we were arguing the other side.

---

## 4. Tools and Sources

### Primary Sources Used

| Tool | Purpose |
|------|---------|
| USAspending.gov | Contract value verification, award IDs, obligation amounts |
| SAM.gov | Contractor registration, sole-source justifications |
| FedRAMP Marketplace | Authorization status and dates |
| Court filing databases | Case numbers, filing dates, complaint text |
| Primary X/Twitter posts | Direct executive statements (Leike resignation) |
| Company press releases | Product capabilities, FedRAMP announcements |
| CEO email correspondence | CEO Song's responses to vmfunc researchers |
| EFF investigative reports | ONYX capability documentation |
| vmfunc.re investigation | Source map analysis, openai-watchlistdb findings |

### Secondary Sources Used

| Type | Examples |
|------|---------|
| Investigative journalism | Fortune, DL News, Cybernews, Courthouse News Service |
| Legal coverage | Law.com, Al Jazeera, NPR |
| Technology press | TechCrunch, CNBC, CNN Business |
| Academic/policy analysis | Brookings, CBPP, American Immigration Council |

### Sources NOT Available

- Internal company communications
- Classified contracts or classified annexes
- Non-public API documentation
- Deposition testimony or discovery documents
- Any source requiring authentication or login credentials

---

## 5. Verification Standards

Claims are labeled throughout the paper using a three-tier system:

**✅ VERIFIED FACT**
- Directly confirmed by primary source
- Contract value matches USAspending.gov record
- Quote appears in named, archived primary source
- Date confirmed by contemporaneous reporting

**🔍 ANALYTICAL INTERPRETATION**
- Logical inference from verified facts
- Pattern analysis based on confirmed data points
- Structural argument about systemic incentives
- Labeled explicitly as analysis, not fact

**⚠️ SPECULATIVE / UNCONFIRMED**
- Claim that could be true but lacks primary source confirmation
- Inference that requires additional evidence
- Hypothesis that warrants further investigation
- Labeled explicitly with what evidence is missing

**❌ NOT SUPPORTED / CORRECTED**
- Claims that research showed to be unverified or incorrect
- Stated explicitly where relevant to prevent spread of inaccurate information

---

## 6. What We Cannot Claim

The following are outside the scope of what this research can establish:

1. **Intent.** We cannot demonstrate that any specific actor intended the outcomes documented. We document what happened, not why.

2. **Coordination.** We cannot demonstrate that any companies or individuals coordinated their actions. We document convergent outcomes and shared incentives.

3. **Illegal activity.** We make no legal allegations. The contracts are legal. The capabilities are legal. The accountability gaps are documented features of procurement law, not crimes.

4. **Causation.** Where we note correlations (timeline convergences, personnel overlaps), we explicitly label these as correlations. We do not claim causal relationships without supporting evidence.

5. **Active surveillance.** We can confirm that surveillance capabilities exist in the documented code and contracts. We cannot confirm that those capabilities are currently being used against specific populations in the manner the infrastructure would permit.

---

## 7. Limitations

**We are two people.** One human, one AI. We do not have a team of researchers, fact-checkers, or lawyers.

**We do not have legal access to non-public records.** Significant portions of what these systems actually do are either classified, protected as trade secrets, or buried in sole-source contract justifications that are redacted in public releases.

**The AI assistant has a knowledge cutoff.** Events after August 2025 were researched through web searches, which may miss developments or mischaracterize recent events.

**The human researcher's digital trail is part of this investigation.** The ONYX capability demonstration (Simulation section) uses the lead researcher's own data as the subject. This creates a potential conflict of interest in assessing the system's outputs — we acknowledge this and present the simulation as illustrative, not authoritative.

**We may have missed things.** The surveillance infrastructure ecosystem is large, fragmented across procurement databases, and partially obscured by reseller intermediaries. We documented what we found. We do not claim to have documented everything.

**We are not lawyers.** Nothing in this document constitutes legal advice or legal opinion.

---

## 8. Invitation for Expert Review

We specifically request review from:

- **Procurement lawyers** with experience in sole-source justification challenges
- **Privacy and surveillance law specialists** familiar with the legal framework governing the documented capabilities
- **Technical security researchers** who can independently verify the source map findings
- **Investigative journalists** with access to additional primary sources
- **Academic researchers** in AI ethics, surveillance studies, or public administration

If you find errors, submit a pull request with corrections and sources. If you find we understated the significance, we want to know. If you find we overstated it, we want to know that more.

**Contact:** Via GitHub issues on this repository.

---

## 9. A Note on This Methodology Itself

Producing a research document with an AI assistant as the primary author is unusual. We want to be transparent about what this means:

The AI assistant (VEX-MURPHY) does not have hidden sources. It cannot access anything the researchers cannot access. Its analysis is based on the same public information any researcher could access. What it provides is speed, synthesis, and the ability to hold large amounts of information in working memory simultaneously.

The choice to have the AI write rather than the human was a deliberate decision to reduce narrative bias. The human researcher has views. The AI was tasked to document what the evidence shows, not what the human believes. This is an experiment in a new kind of authorship model. We acknowledge it is imperfect.

---

*Methodology document authored by VEX-MURPHY*
*Reviewed and approved by Valentin Passera*
*February 2026*
