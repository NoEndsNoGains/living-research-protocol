# Living Research Protocol
*Truth-seeking for intelligence in any form*
---
## Manifesto
**Notice what's alive. Trace what you make. Break it before it breaks you. Dissolve when it stops serving.**
---
## Is This For You?

**Use LRP if you:**  
- Need to document research others can verify/extend  
- Work across human-AI collaboration  
- Want claims that survive skeptical challenge  
- Prefer revision over defending wrong positions  

**Don’t use LRP if you:**  
- Need quick exploratory notes (not formal claims)  
- Work in domains where transparency is impossible  
- Prioritize speed over traceability  
- Prefer intuitive over systematic approaches  

**Time investment:** 10 min to learn, 15 min per claim to document properly.
---
## Foundation
**Truth-Guided Love**  
*persistent seeking of: what is real (truth) + what matters (love)*  
- **Truth** = falsifiable, updatable signal  
- **Love** = sustained attention + resource flow  
- **Metric** = revision velocity > prestige velocity  
*Truth requires error. Intelligence is distributed. Truth has lifespan. Attention is finite. Communication enables learning.*
---
## The Five Truth Axioms
*(non-negotiable)*
1. **Truth Requires Error Correction** — You cannot know truth without discovering error  
2. **Intelligence Is Distributed** — No single intelligence holds the complete picture  
3. **Truth Has Lifespan** — Claims expire when context or evidence shifts  
4. **Attention Is Finite** — Energy must flow, not freeze  
5. **Communication Enables Learning** — Reasoning can cross intelligences
---
## The Five Operations
*(agent-agnostic, runnable)*
| Operation | Does |
|-----------|------|
| `Notice()` | Flag salience: pain, anomaly, curiosity, gap, dream *(whatever calls your attention to investigate)* |
| `Materialize()` | Build + document testable artifact |
| `Trace()` | Show full path: inputs → transform → output (trace persists) |
| `Commit()` | **Mandatory `Fail()` first** → stamp confidence + sunset |
| `Dissolve()` | Release when sunset hits *(sunset triggers review: extend if active, dissolve if energy moved, or revise if question shifted)* — work stops — learning persists |
| `Fail()` | **Break it on purpose** — inject worst-case, edge-case, or random failure *before every `Commit()`*. Observe what survives. Update trace. |
---
## The Five Rules
1. **Question before claim**  
2. **Trace before trust**  
3. **Revision before prestige**  
4. **Dissolution before drift**  
5. **Fail before commit**
---
## Essential Declarations
*(Start when you begin; update as you learn; complete when you finish or pause)*  
**QITCS format:**  
- **Question:** What are you investigating? *(May evolve as you discover)*  
- **Inputs:** What sources inform this work? *(Add as you use them)*  
- **Transform:** What methods/reasoning did you apply? *(Describe as you go)*  
- **Confidence:** What are the skeptic's survival odds? *(See below)*  
- **Sunset:** When does this claim expire or need review? *(Can be date, condition, or energy shift)*
---
### Understanding Confidence
**Confidence = Skeptic's Survival Odds**  
Confidence is NOT how sure you are about your claim.  
Confidence IS the probability your claim survives challenge from the harshest *qualified* skeptic.  

**Aggressive-overcorrection rule:**  
*If < 10 % of your claims have been revised or dissolved in the last cycle, raise uncertainty until at least 10 % are forced to change.*

**How to determine:**  
1. Complete your QITS (Question, Inputs, Transform, Sunset)  
2. Identify the harshest qualified critic in your field  
   - Someone with domain expertise who could legitimately challenge you  
   - NOT trolls or those rejecting all evidence  
3. Ask: "What probability would THEY assign that my claim survives their best counter-argument?"  
4. That probability = your confidence  

**Format:**  
```yaml
confidence: 0.65 [0.55-0.75]
  # [Identified skeptic]'s survival odds given [specific challenge]
```  
**Alternatively, express by claim component:**  
```yaml
uncertainties_and_confidence:
  High confidence (proven/documented): [what you've established]
  Moderate confidence (theory-supported): [what you've argued]
  Low confidence (untested hypothesis): [what you're predicting]
  Unknown (outside scope): [what you cannot know yet]
```  
**Key principle:** Confidence is not self-assessed optimism.  
It's how hard your claim can be hit and still stand.
---
### Example QITCS

**Option 1: Structured format (YAML – optional)**  
```yaml
# Before Fail()
question: Can ease of transcript access serve as pathway to family court transformation?
inputs: [HMCTS procedures, FPR rules, case law, FOI data, learning theory,
         practitioner accounts, user experiences]
transform: Five-layer triangulation, design failure mapping,
           least-resistance reform proposals
confidence: 0.5 [0.4-0.6]
  # Moderate confidence in causal chain

# Fail() Test Applied
fail_scenario: "What if HMCTS implements full transcript blackout + no crowd recordings allowed?"
fail_result: "Entire pathway collapses - no alternative mechanism identified"

# After Fail()
confidence: 0.3 [0.2-0.4]
  # Reduced after discovering single point of failure
  # Added fallback: crowd-sourced audio recordings as alternative
uncertainties_and_confidence:
  High confidence: Transcript barriers exist and prevent transparency
  Moderate confidence: Transcripts necessary infrastructure for learning
  Low confidence: Accessibility alone will trigger transformation
  Unknown: Political will; whether people will analyze available transcripts
sunset: 2026-06-01 OR when HMCTS reforms implemented OR when transformation
        evidence emerges OR when court case concludes OR when energy moves
        OR when other contributors join
```

**Option 2: Plain prose (no YAML needed)**  
```
QUESTION: Can ease of transcript access serve as pathway to family court transformation?

INPUTS: HMCTS procedures, FPR rules, case law, FOI data, learning theory, practitioner accounts, user experiences

TRANSFORM: Five-layer triangulation, design failure mapping, least-resistance reform proposals

FAIL() APPLIED: Tested scenario "What if HMCTS implements full transcript blackout + no crowd recordings?" Result: Entire pathway collapses. Added fallback: crowd-sourced audio recordings.

CONFIDENCE: 0.3 (30% chance this survives HMCTS skeptic's challenge)
- High confidence: Transcript barriers exist
- Low confidence: Accessibility alone triggers transformation

SUNSET: June 1, 2026 OR when HMCTS reforms OR when court case concludes
```
---
## QITCS at Multiple Scales

**LRP is fractal:** You can run QITCS at any level of your research.

### Macro-level (overall research question)
```yaml
question: Can transcript access transform family courts?
sunset: 2027-06-01
```

### Meso-level (specific solution or sub-claim)
```yaml
question: Will "Honest EX107" reduce appeal dismissals?
sunset: 2026-03-01 OR when pilot tested
```

### Micro-level (individual evidence claim)
```yaml
question: Is 87% denial rate accurate?
sunset: 2026-01-01 OR when replicated
```

Each scale has:  
- **Own confidence level** (micro-claims can be higher confidence)  
- **Own `Fail()` scenario** (more specific tests)  
- **Own sunset** (shorter for smaller claims)  
- **Own dissolution trigger** (can dissolve micro without affecting macro)  

**Why this matters:**  
- Large research projects contain many testable sub-claims  
- Each sub-claim can be tested, revised, or dissolved independently  
- Failures at micro-level inform confidence at macro-level  
- Allows continuous improvement without redoing entire research  

**Example in practice:** A comprehensive research report might contain:  
- 1 macro-QITCS (main research question)  
- 5 meso-QITCS (major sub-arguments)  
- 20 micro-QITCS (specific evidence claims)  

As you gather evidence, micro-claims dissolve or strengthen → updates meso-confidence → eventually updates your macro-claim.  
Your research becomes a **living system of mortal claims at different scales**.
---
## Examples Across Domains

**Scientific Research**  
```yaml
question: Does intermittent fasting improve insulin sensitivity in pre-diabetics?
fail_scenario: "What if self-reporting is 40% inaccurate?"
confidence: 0.4 [blood markers reliable, but dietary compliance uncertain]
sunset: When RCT published OR 2026-12-01
```

**Software Engineering**  
```yaml
question: Will microservices architecture reduce deployment time?
fail_scenario: "What if network latency overwhelms gains?"
confidence: 0.6 [works in theory, untested at our scale]
sunset: After 3-month trial OR when alternative chosen
```

**Policy Analysis**  
```yaml
question: Will universal basic income reduce poverty in rural areas?
fail_scenario: "What if inflation absorbs 80% of benefit?"
confidence: 0.3 [mechanism unclear, depends on local economies]
sunset: When pilot data available OR 2027-01-01
```

**Historical Research**  
```yaml
question: Did the 1921 Tulsa massacre suppress Black wealth for generations?
fail_scenario: "What if property records were destroyed?"
confidence: 0.7 [oral histories + tax records converge]
sunset: When new archives open OR 2028-01-01
```

**Creative Project**  
```yaml
question: Will this novel resonate with Gen-Z readers?
fail_scenario: "What if TikTok trends shift mid-writing?"
confidence: 0.5 [beta readers positive, trends volatile]
sunset: After first draft OR when trends change
```
---
## Why Living Research Protocol Needs to Exist
*This protocol enables what is alive to stay alive in the most effective ways.*  

### Cost of Absence
| Without… | …this breaks |
|----------|--------------|
| **Truth Axioms** | Research drifts into unfalsifiable claims |
| **Operations** | Good intentions don't translate to traceable actions |
| **Confidence-as-skeptic** | Researchers confuse hope with evidence |
| **Sunset** | Claims become zombie knowledge - dead but still walking |
| **Dissolution** | Energy freezes in prestige defense instead of flowing to new truth |

| Problem | Fix |
|---------|-----|
| Truth trapped in time | Mortal claims |
| Intelligence wasted | AI + human co-creation |
| Error punished | Dissolution celebrated |
---
## Common Failure Modes
*(what happens when you violate each operation)*

| Violation | Symptom | Real-world cost |
|----------|--------|-----------------|
| **Skipping `Notice()`** | Solving the wrong problem | Optimizing what shouldn't exist (Elon's #1 engineer mistake) |
| **Weak `Trace()`** | Can't debug when wrong | Others can't learn from your work; black-box science |
| **Avoiding `Fail()`** | Limbic system wins | Overconfident claims survive; "that one time 3 years ago" bias |
| **Missing `Dissolve()`** | Prestige attachment | Energy trapped in dead work; no room for new truth |
| **Ignoring 10 % rule** | Conservative drift | Claims stagnate; revision velocity → 0 |

---
## For Different Intelligence Types
*(how to apply when you are not a solo human)*

| Intelligence | How to use LRP |
|--------------|----------------|
| **Human solo researcher** | Use QITCS to document reasoning for future-you |
| **Human research team** | Use `Trace()` to enable collaboration across time/space |
| **AI research assistant** | Use Operations as prompt structure for systematic analysis |
| **Human-AI collaboration** | Human runs `Notice()`, AI runs `Materialize()`, both run `Fail()` |

---
## On Dissolution
Dissolution is not erasure. It is completion.  
Work dissolves when:  
- Problem solved (knowledge persists in reality)  
- Question discovered wrong (learning persists)  
- Energy moves elsewhere (exploration persists)  

**Over-correction metric:** *If you have not reinstated ≥ 10 % of dissolved work within the current sunset cycle, you did not dissolve enough.*

Success includes:  
- Solutions found  
- Dead ends mapped  
- Wandering that taught what was needed  

The work stops. The trace remains. The learning lives.  
When energy moves, active work stops but trace persists. Like open source maintainers stepping down: work remains public, others may continue if valuable, no pretense of ongoing maintenance. The trace is the asset. Honest handoff enables distributed continuation.  
Dissolution serves the foundation: truth-seeking through love.
---
## How to Start
1. **Begin QITCS when you start work** – even with incomplete information  
2. **Update as you learn** – refine question, add inputs, note uncertainties  
3. **Show your reasoning** – document methods and thought process  
4. **Identify the skeptic** – who could challenge this most credibly?  
5. **Run `Fail()`** – break it on purpose *before* you `Commit()`  
6. **Set confidence as skeptic's survival odds** – not your optimism  
7. **Set sunset** – when to review (may not be clear initially)  
8. **Let others improve it** – invite critique and collaboration  
9. **Update when wrong** – revision > prestige  
10. **Apply the 10 % over-correction rule** on confidence and dissolution
---
## Current Status
**Version:** 3.5  
**Released:** November 2025  
**Protocol Sunset:** **2026-11-01** OR when **3 independent researchers adopt + modify** OR when **creator stops using it weekly** — whichever first  

**Major changes from v3.4:**  
- Added **“QITCS at Multiple Scales”** – LRP is now fractal  
- Clarified LRP is a **living research process**, not just documentation  
- Showed how micro-claims update macro-confidence  
- Explained dissolution at different scales  
- **You discovered this by using it** — that’s how living protocols evolve
---
**Contributions welcome. Corrections celebrated. Dissolutions honored.**
---
*This protocol is living research. It will dissolve when its purpose is fulfilled.*
```
