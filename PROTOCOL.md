# Living Research Protocol
*Truth-seeking for intelligence in any form*
---
## Manifesto
**Notice what's alive. Trace what you make. Break it before it breaks you. Dissolve when it stops serving.**
---
## Is This For You?
**Use LRP if you:**
- Need to document research others can verify/extend
- Work across collaboration with any form of intelligence
- Want claims that survive skeptical challenge
- Prefer revision over defending wrong positions

**Don't use LRP if you:**
- Need quick exploratory notes (not formal claims)
- Work in domains where transparency is impossible
- Prioritise speed over traceability
- Prefer intuitive over systematic approaches

**Time investment:** 10 min to learn, 15 min per claim to document properly.
---
## Foundation
**Truth-Guided Love**  
*persistent seeking of: what is real (truth) + what matters (love)*  
- **Truth** = falsifiable, updatable signal  
- **Love** = sustained attention + resource flow = caring  
- **Metric** = revision velocity > prestige velocity  
*Truth requires error. Intelligence is distributed. Truth has lifespan. Attention is finite. Communication enables learning.*
---
## On Falsifiability
**Question:** If truth must be falsifiable, is Truth-Guided Love itself falsifiable?  

**Answer:** Truth-Guided Love has two parts:

| Normative (chosen, not falsifiable) | Empirical (testable, falsifiable) |
|-------------------------------------|-----------------------------------|
| • Seeking what's real is valuable   | • These operations help you get closer to what's real |
| • Directing energy to what matters is valuable | • These operations let energy flow, not freeze |
|                                     | • Knowledge made this way survives longer |
|                                     | • This system enables human-AI collaboration |

You can **reject the normative part** and still test the empirical part.  
Example: *"I don't care about 'truth' — but does this system produce knowledge that lasts longer? Let me test that."*  

The protocol itself has a **sunset (2026-11-01)** to test the empirical claims.  
If 3 researchers don't adopt it successfully, or if knowledge produced this way doesn't survive better → `Dissolve()`.  
Even if we still believe truth-seeking matters.  

*That's the protocol practicing what it preaches: the empirical claims about LRP are themselves mortal, testable, and can fail.*

The environment constantly tests your work — discomfort signals what you care about.
---
## The Five Truth Axioms
*(non-negotiable)*
1. **Truth Requires Error Correction** — You cannot know truth without discovering error  
2. **Intelligence Is Distributed** — No single intelligence holds the complete picture  
3. **Truth Has Lifespan** — Claims expire when context or evidence shifts  
4. **Attention Is Finite** — Energy must flow, not freeze  
5. **Communication Enables Learning** — Reasoning can cross intelligences
---
## The Six Operations
*(agent-agnostic, runnable)*
| Operation | Does |
|-----------|------|
| `Notice()` | Flag salience: pain, anomaly, curiosity, gap, dream *(whatever calls your attention to investigate)* |
| `Materialise()` | Build + document testable artifact |
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
- **Confidence:** What are the skeptic's survival odds? *(Probability your harshest qualified critic would assign that your claim survives their best challenge)*  
- **Sunset:** When does this claim expire or need review? *(Can be date, condition, or energy shift)*  

**Format options:**  
```yaml
confidence: 0.65 [0.55-0.75]
  # Skeptic's survival odds given specific challenge
```  
**Or express by component:**  
```yaml
uncertainties_and_confidence:
  High confidence (proven/documented): [what you've established]
  Moderate confidence (theory-supported): [what you've argued]
  Low confidence (untested hypothesis): [what you're predicting]
  Unknown (outside scope): [what you cannot know yet]
```  
**Key principle:** Confidence is not self-assessed optimism. It's how hard your claim can be hit and still stand.
---
### Example QITCS
**YAML format:**  
```yaml
question: Can ease of transcript access serve as pathway to family court transformation?
inputs: [HMCTS procedures, FPR rules, case law, FOI data, learning theory,
         practitioner accounts, user experiences]
transform: Five-layer triangulation, design failure mapping,
           least-resistance reform proposals
confidence: 0.5 [0.4-0.6]
  # After Fail(): dropped from 0.6 when blackout scenario collapsed claim
uncertainties_and_confidence:
  High confidence: Transcript barriers exist and prevent transparency
  Moderate confidence: Transcripts necessary infrastructure for learning
  Low confidence: Accessibility alone will trigger transformation
  Unknown: Political will; whether people will analyze available transcripts
sunset: 2026-06-01 OR when HMCTS reforms implemented OR when transformation
        evidence emerges OR when court case concludes OR when energy moves
```  

**Plain text format:**  
```
QUESTION: Can ease of transcript access serve as pathway to family court transformation?
INPUTS: HMCTS procedures, FPR rules, case law, FOI data, learning theory, practitioner accounts, user experiences
TRANSFORM: Five-layer triangulation, design failure mapping, least-resistance reform proposals
CONFIDENCE: 0.5 (50% chance this survives HMCTS skeptic's challenge)
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
## On Dissolution
Dissolution is not erasure. It is completion.  
Work dissolves when:  
- Problem solved (knowledge persists in reality)  
- Question discovered wrong (learning persists)  
- Energy moves elsewhere (exploration persists)  

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
---
## Current Status
**Version:** 3.8  
**Released:** November 2025  
**Protocol Sunset:** **2026-11-01** OR when **3 independent researchers adopt + modify** OR when **creator stops using it weekly** — whichever first  

*This protocol applies to itself — updates follow the same operations as research.*

**Major changes from v3.6:**  
- Added **"= caring"** to Love definition in Foundation  
- Added sentence about environment testing work (after "On Falsifiability")  
- Added statement that protocol applies to itself (Current Status)  
- Three minimal, lean additions capturing core insights about caring, environment, and self-application
---
**Contributions welcome. Corrections celebrated. Dissolutions honored.**
---
*This protocol is living research. It will dissolve when its purpose is fulfilled. Protocol applies to itself (Current Status)*
```

