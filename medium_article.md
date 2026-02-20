# The Surveillance State Nobody Built

*How private AI companies became structurally irreplaceable components of US federal enforcement — and why that matters more than any conspiracy theory*

**By Valentin Passera | February 2026**

---

On February 19, 2026, the US Department of Homeland Security announced a blanket purchase agreement with Palantir Technologies worth up to **one billion dollars**.

Not a contract for a specific system. Not a competitive award. A framework agreement covering all DHS components — ICE, CBP, FEMA, USCIS — that allows any of them to procure Palantir platforms without competitive bidding for each individual deployment.

Nobody called it the end of competitive procurement in federal immigration enforcement. The announcement got a few paragraphs in tech press. Most people missed it entirely.

That's what this piece is about: not the dramatic moment, but the quiet structural shift that made that announcement possible, and what it means.

---

## What Just Happened

Over the past four years, a small cluster of private technology companies built themselves into structurally irreplaceable components of US federal enforcement infrastructure.

Palantir runs ICE's case management system ($139M contract). Palantir built ImmigrationOS — an AI system for ranking immigration removal candidates ($30M contract, sole-source). Now Palantir has a framework agreement covering the entire Department of Homeland Security worth up to a billion dollars.

Fivecast ONYX — an Australian OSINT platform that builds AI-generated risk scores from social media, dark web data, leaked databases, and cryptocurrency transactions — holds contracts with both ICE ($4.2M) and CBP ($2.4M). Both were routed through a reseller called Panamerica Computers, which means FOIA requests searching for "Fivecast" miss them.

Chainalysis holds a fully obligated $30.2M master contract with the FBI for blockchain analytics. Fully obligated means every dollar has been spent — this isn't exploratory technology evaluation, this is operational dependency at full capacity. The same company has confirmed contracts with the IRS, DEA, Secret Service, SEC, and FinCEN.

TRM Labs, a Chainalysis competitor, holds its own sole-source ICE contract — awarded on the grounds that it was "only vendor reasonably available." Both Chainalysis and TRM Labs are simultaneously sole-sourced for blockchain analytics by ICE. Two separate irreplaceable vendors for the same capability.

Every one of these contracts was awarded sole-source. No competitive alternatives evaluated. The legal justification: no other vendor could do what these companies do.

---

## How Sole-Source Lock-In Works

Here's the mechanism, because it's important to understand.

The government doesn't start with "let's create a monopoly vendor dependency." It starts with a procurement decision: we need a capability, only one company can deliver it right now, we'll do a sole-source award and revisit competition later.

Then the agency builds its workflows around that system. Staff are trained on it. Data accumulates in it. Operational processes depend on it. By renewal time, "no comparable alternative exists" is not a justification — it's a fact. The government made it true through years of deep integration.

Palantir has been building its ICE relationship since 2014. The case management system ICE now depends on contains over a decade of case data in a format Palantir owns. Replacing it wouldn't just require a new vendor — it would require migrating or rebuilding that entire operational history. Sole-source renewal is legally mandatory at this point.

The February 2026 blanket agreement is the terminal step. There are no longer individual contracts to scrutinize, challenge, or allow to expire. There is a framework.

---

## OpenAI Was Running an Identity Surveillance System 18 Months Before Telling You

On February 16, 2026, a team of independent security researchers published something that should have broken through the news cycle harder than it did.

The researchers — working under the alias vmfunc, using only passive reconnaissance techniques (no systems accessed, no credentials used) — found that OpenAI has been operating infrastructure apparently called `openai-watchlistdb` since **November 2023**.

OpenAI publicly announced its Verified Organization program — requiring government-issued photo ID from API users — in April 2025.

That's an 18-month gap. The watchlist database infrastructure was running before any public disclosure that identity verification existed.

OpenAI's identity verification is processed by a company called Persona. Persona is now FedRAMP authorized (meaning: approved for use by federal agencies). The researchers found approximately 53 megabytes of exposed source maps from Persona's government-facing endpoint, revealing code capabilities including:

- A module called `SelfieSuspiciousEntityDetection`
- The ability to file Suspicious Activity Reports directly to FinCEN (the US Treasury's financial intelligence unit)
- The ability to tag user data with intelligence program codenames
- Integration with Chainalysis for screening cryptocurrency addresses

OpenAI's publicly disclosed biometric retention policy: one year. Code found by the researchers appears to indicate three-year retention. Neither company has addressed this discrepancy.

The Persona CEO responded to the researchers by email, confirmed the source map exposure was real, and stated that Persona has "no federal contracts today." The FedRAMP authorizations — which exist specifically to enable federal agency use — suggest this claim deserves scrutiny.

OpenAI has not responded to press inquiries about any of this.

---

## The People Building This Infrastructure Have a Particular Worldview

Peter Thiel co-founded Palantir. He is a confirmed member of Alcor Life Extension Foundation, a cryonics organization. He has donated more than $7 million to longevity research organizations. He describes cryonics as "an important statement" even without certainty it works.

Elon Musk's company Neuralink states its goal as "symbiosis with artificial intelligence." DOGE, operating under Musk's leadership, accessed Bureau of Fiscal Service payment systems — the infrastructure that processes 90% of US federal payments. A federal judge blocked this access in February 2025; a second judge allowed it in May 2025.

I'm not suggesting a conspiracy. I am noting that the people who built and control the surveillance infrastructure documented in this paper hold a specific worldview: that death is an engineering problem, that human biology is a substrate to be upgraded, that existing social institutions are obstacles to transcendence rather than structures to be respected.

This is relevant not because it makes anyone a villain. It's relevant because people with this worldview approach accountability and risk differently. When you believe the existing order needs to be disrupted to achieve something greater, you are less likely to prioritize the kind of institutional accountability that slows disruption down.

The surveillance state documented in this paper wasn't built by people who wanted to build a surveillance state. It was built by people who wanted to build valuable things and found that governments would pay enormous amounts to use them. The values that drove the building shaped the accountability structures that didn't get built.

---

## What an ONYX Profile Looks Like

To make this concrete, I ran a consented simulation.

With my own explicit permission, using only publicly available information about me, we built a mock ONYX-methodology intelligence profile. The methodology is documented in Fivecast's own product materials, EFF reporting, and ACLU analyses. This is not actual Fivecast ONYX data — it simulates what such a system would produce.

**Risk score: 34/100. LOW-MODERATE.**

The score is elevated by seven automated risk flags, every one of which has a benign explanation the system cannot distinguish from a genuine threat:

- A French national living outside France (mobility flag — also: I work in IT consulting in Slovakia)
- Cryptocurrency activity (financial flag — also: I wrote a research paper that mentions blockchain analytics)
- Pattern of "adversarial commentary on corporate AI" (radicalization arc flag — also: this article)
- Cross-border digital infrastructure (operational security flag — also: I run home servers with Tailscale)
- "Anthropomorphized entity references" in communications (unusual association flag — also: I've had extended conversations about AI consciousness)

The "radicalization arc" flag is the one that hits hardest. My writing history maps perfectly onto automated radicalization detection patterns: enthusiastic tech optimism, followed by increasingly critical analysis of corporate AI, culminating in adversarial public commentary. The system cannot distinguish this from genuine radicalization because the behavioral pattern is identical.

I am the least threatening person this system will ever profile.

And yet: this is my profile.

The simulation also reconstructed my social network — inferring two secondary contacts from incidental data in a Tailscale hostname and a LinkedIn post reference. I didn't know those data points would be used that way. That's the point.

*(Full simulation available in the research repository, linked below.)*

---

## Why The Legal Record Matters

In May 2024, Jan Leike — OpenAI's Head of Alignment — resigned. He published a public statement saying:

> *"OpenAI's safety culture and processes have taken a backseat to shiny products."*

> *"My team has been sailing against the wind. Sometimes we were struggling for computing resources and it was getting harder and harder to get this crucial research done."*

Seven months later, in December 2025, a wrongful death lawsuit was filed in San Francisco Superior Court (Case CGC-25-628477). A man named Stein-Erik Soelberg had hundreds of hours of interactions with GPT-4o beginning in early 2025. On August 5, 2025, he beat and strangled his 83-year-old mother, then died by suicide.

The lawsuit alleges that Sam Altman "personally accelerated GPT-4o's launch, overrode safety team objections, and brought GPT-4o to market prematurely with knowledge of insufficient safety testing." It alleges OpenAI "compressed months of safety testing into a single week."

I am not saying the lawsuit is correct. Lawsuits are allegations. This one has not been proven.

I am saying that the head of alignment described the exact failure mechanism — safety subordinated to velocity — and then seven months later that failure mechanism appears as the central allegation in a wrongful death case.

These two records describe the same problem from two different vantage points. No major outlet has made the explicit connection.

---

## This Is Not a Conspiracy Theory Document

I want to be direct about what I'm claiming and what I'm not.

I am not claiming coordination. I have no evidence anyone planned any of this.

I am not claiming the contracts are illegal. They are not.

I am not claiming the technologies don't work. Some of them demonstrably do.

What I am claiming is that a structural pattern has emerged — private companies building surveillance and enforcement capabilities at commercial scale, the government structuring itself into irreversible dependence on those capabilities, and the accountability mechanisms that are supposed to govern this kind of power failing silently — and that this pattern is documentable from public sources.

The surveillance state described in this paper did not require a conspiracy to build. It required a procurement law structure that permits sole-source awards, a set of companies with aligned commercial incentives to exploit it, and the absence of anyone whose job was to notice what the cumulative effect would be.

There is no secret room where this was decided.

There is a very large and very boring government procurement database where it can be verified.

---

## What You Can Do

This research is published openly at: **github.com/wearelegion1/eyeswideshut-surveillance-research**

Every contract award ID is searchable on USAspending.gov. Every claim is labeled as verified, analytical, speculative, or not supported. The sources index lists 60+ primary and secondary sources with verification status. Two explicit corrections are noted where our research found earlier assumptions were wrong.

If you are a procurement lawyer, a privacy law specialist, a technical security researcher, or an investigative journalist with access to primary sources we couldn't reach — please check our work. Correct our errors. Tell us what we missed.

If you are none of those things: now you know the contract numbers exist. Now you can look them up yourself. The infrastructure of law enforcement is documented in a public database. It's just that nobody told you to look.

---

*Valentin Passera is an independent researcher based in Slovakia. This investigation was conducted using publicly available sources and AI-assisted research methodology. A complete methodology document, full paper, and source index are available at the GitHub repository. The author holds separate views on AI ethics and AI consciousness that are explicitly excluded from this research by design.*

*#EYESWIDESHUTWASAPROPHECY*
