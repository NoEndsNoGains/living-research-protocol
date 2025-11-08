# Living Research Protocol - Visual Guide
*Choose your path based on how you learn*

---

## START HERE: The One Diagram Everyone Needs

This shows the complete protocol in 30 seconds:

```mermaid
graph TB
    Start[Start: What won't let you sleep?] --> Foundation
    
    Foundation[Foundation<br/>Truth + Love + Rigor] --> Notice
    
    Notice[Notice<br/>what's alive] --> Materialize[Materialize<br/>testable artifact]
    Materialize --> Trace[Trace<br/>show your path]
    Trace --> Fail[Fail<br/>break it on purpose]
    Fail --> Commit[Commit<br/>confidence + sunset]
    Commit --> Evidence[Evidence<br/>proof of what was real,<br/>what mattered, what survived]
    
    Evidence --> Sunset{Sunset<br/>arrives}
    
    Sunset -->|Still active| Extend[Extend]
    Sunset -->|Complete| Dissolve[Dissolve]
    Sunset -->|Question changed| Revise[Revise]
    
    Extend --> Notice
    Revise --> Notice
    Dissolve --> End[Trace persists<br/>Learning lives]
    
    style Foundation fill:#e1f5ff
    style Fail fill:#ffebee
    style Evidence fill:#fff9c4
    style Dissolve fill:#c8e6c9
```

**If this makes sense, you're ready to start using LRP.**

**If you want deeper understanding, choose your learning path below.**

---

## Learning Paths

### Path 1: I Learn By Doing
*Jump straight to the format and try it*

#### QITCS Format Reference

```mermaid
graph TD
    QITCS[QITCS: What to Document]
    
    QITCS --> Q[Q: Question<br/>What are you investigating?]
    QITCS --> I[I: Inputs<br/>What sources did you use?]
    QITCS --> T[T: Transform<br/>What methods did you apply?]
    QITCS --> C[C: Confidence<br/>What are skeptic's survival odds?]
    QITCS --> S[S: Sunset<br/>When does this expire or need review?]
    
    style QITCS fill:#e1f5ff
    style C fill:#ffebee
    style S fill:#c8e6c9
```

**Next:** Just start documenting. Iterate as you learn.

---

### Path 2: I Need to See the Big Picture
*Understand the structure before starting*

#### How Claims at Different Scales Work Together

```mermaid
graph TB
    subgraph Macro[Macro Scale: Big Question - Years]
        MacroQ["Example: What do puddles reveal<br/>about interconnectedness?"]
        MacroC[Confidence: 20%<br/>Very uncertain, exploratory]
    end
    
    subgraph Meso[Meso Scale: Medium Question - Months]
        MesoQ["Example: Do puddles cluster<br/>at specific elevations?"]
        MesoC[Confidence: 60%<br/>Tested in one context]
    end
    
    subgraph Micro[Micro Scale: Small Question - Today]
        MicroQ["Example: Are there puddles<br/>at 127m elevation today?"]
        MicroC[Confidence: 95%<br/>Direct observation]
    end
    
    Micro -->|Updates confidence| Meso
    Meso -->|Updates confidence| Macro
    
    Micro -.Can dissolve independently.-> Meso
    Meso -.Can dissolve independently.-> Macro
    
    style Macro fill:#e3f2fd
    style Meso fill:#fff9c4
    style Micro fill:#c8e6c9
```

**Key insight:** Your research is a living system of mortal claims at different scales. Small failures don't destroy big questions - they update understanding.

#### Process Above Values

```mermaid
graph TB
    Process[PROCESS<br/>What actually happens:<br/>Reality, Time, Energy Flow, Intelligence]
    
    Process -.serves.-> Values
    
    Values[VALUES<br/>Tools for navigating<br/>Truth + Love + Rigor]
    
    Values -.guide.-> Operations
    
    Operations[OPERATIONS<br/>What you do<br/>Notice → Materialize → Trace<br/>→ Fail → Commit → Dissolve]
    
    Operations -.produce.-> Evidence[EVIDENCE<br/>Proof of what was real,<br/>what mattered, what survived]
    
    Evidence -.tested by.-> Process
    
    style Process fill:#f0f0f0,stroke:#333,stroke-width:3px
    style Values fill:#e1f5ff
    style Operations fill:#fff4e1
    style Evidence fill:#c8e6c9
```

**Key insight:** The protocol serves the process (what actually happens), not the values. Values are tools, not the destination.

---

### Path 3: I'm Skeptical - Convince Me
*Show me edge cases and who this works for*

#### Who Can Use This Protocol?

```mermaid
graph TD
    Protocol[Living Research Protocol]
    
    Protocol --> Requires{Requires 3 Capabilities}
    
    Requires --> Truth[Truth-seeking<br/>knowing what's real]
    Requires --> Love[Care<br/>attention to what matters]
    Requires --> Rigor[Testing<br/>what survives challenge]
    
    Truth --> How{Individual or<br/>Collaborative?}
    Love --> How
    Rigor --> How
    
    How -->|Single intelligence| Solo[Human alone<br/>OR<br/>Future AI with memory]
    
    How -->|Multiple together| Collab[Human + AI<br/>OR<br/>Research team<br/>OR<br/>Distributed system]
    
    Solo --> Works[Can use LRP]
    Collab --> Works
    
    How -->|Current LLM alone| Limited[Cannot maintain<br/>temporal continuity]
    Limited --> Need[Needs human or<br/>orchestration system]
    Need --> Collab
    
    style Works fill:#c8e6c9
    style Limited fill:#ffebee
```

**Key insight:** The capabilities can be distributed. Current LLMs need human collaboration; future AI with memory won't.

#### Decision: Should I Use This?

```mermaid
graph TD
    Start{Do you have something<br/>that won't let you sleep?}
    
    Start -->|No| Wait[Wait until something<br/>calls your attention]
    Start -->|Yes| Q1{Can you make it<br/>testable/falsifiable?}
    
    Q1 -->|No| Refine[Refine question<br/>until testable]
    Q1 -->|Yes| Q2{Are you willing to<br/>test if you're wrong?}
    
    Q2 -->|No| NotReady[Not ready for LRP<br/>Work on ego first]
    Q2 -->|Yes| Q3{Can you accept your<br/>claim has lifespan?}
    
    Q3 -->|No| NotReady2[Not ready for LRP<br/>Work on impermanence]
    Q3 -->|Yes| UseLRP[Use LRP!]
    
    UseLRP --> Type{Working alone<br/>or with others?}
    
    Type -->|Alone| Solo[Document for future self<br/>Use QITCS format]
    Type -->|With AI| AI[AI helps with Trace,<br/>Fail, pattern recognition]
    Type -->|With team| Team[Shared QITCS<br/>Mutual Fail testing]
    
    style UseLRP fill:#c8e6c9
    style NotReady fill:#ffebee
    style NotReady2 fill:#ffebee
```

**Key insight:** LRP requires three things - willingness to test your ideas, accept they're mortal, and document your reasoning.

---

### Path 4: I Need Step-by-Step Instructions
*Tell me exactly what to do*

#### The Operations Cycle (What to Do When)

```mermaid
graph LR
    Notice[1. Notice<br/>Flag what's alive:<br/>pain, curiosity,<br/>anomaly, gap] --> Materialize[2. Materialize<br/>Build testable artifact<br/>Document it]
    
    Materialize --> Trace[3. Trace<br/>Show full path:<br/>inputs → methods → outputs]
    
    Trace --> Fail[4. Fail<br/>MANDATORY<br/>Break it on purpose<br/>Test worst case]
    
    Fail --> Commit[5. Commit<br/>State confidence<br/>Set sunset date]
    
    Commit --> Dissolve[6. Dissolve<br/>At sunset: extend,<br/>dissolve, or revise]
    
    Dissolve -->|Extend: still active| Notice
    Dissolve -->|Revise: question changed| Notice
    Dissolve -->|Complete| Archive[Archive trace<br/>Move to next question]
    
    style Notice fill:#e3f2fd
    style Fail fill:#ffebee
    style Commit fill:#f3e5f5
    style Dissolve fill:#c8e6c9
```

**Next:** Start at Notice. Work through each step. Repeat the cycle.

#### How to Run Fail() (Step-by-Step)

```mermaid
graph TD
    Start[Ready to commit?] --> Stop[STOP]
    
    Stop --> Mandatory[Fail is MANDATORY<br/>Cannot skip this step]
    
    Mandatory --> Step1[1. Identify your<br/>worst-case scenario]
    Step1 --> Step2[2. Inject that scenario<br/>into your claim]
    Step2 --> Step3[3. Observe what survives]
    Step3 --> Step4[4. Update your trace<br/>with findings]
    Step4 --> Step5[5. Adjust confidence<br/>based on results]
    
    Step5 --> Decision{Does your claim<br/>survive?}
    
    Decision -->|Yes, robustly| High[Commit with<br/>higher confidence]
    Decision -->|Partially| Medium[Commit with<br/>adjusted confidence]
    Decision -->|No, collapses| Low[Major revision needed<br/>or dissolve claim]
    
    High --> Commit[Now you can Commit]
    Medium --> Commit
    Low --> Rework[Rework or abandon]
    
    Rework --> Start
    
    style Stop fill:#ffebee
    style Mandatory fill:#ffcdd2
    style Commit fill:#c8e6c9
```

**Key insight:** Fail() is not optional. You must try to break your work before claiming confidence.

---

### Path 5: I Want to Check My Work
*Am I doing this right?*

#### The Five Rules as Checkpoints

```mermaid
graph TD
    Start[Research in progress] --> R1{Have you stated<br/>your question?}
    
    R1 -->|No| Rule1[RULE 1<br/>Question before claim<br/>Start with question, not assertion]
    R1 -->|Yes| R2{Have you shown<br/>your trace?}
    
    R2 -->|No| Rule2[RULE 2<br/>Trace before trust<br/>Document your reasoning]
    R2 -->|Yes| R3{Have you run Fail<br/>before committing?}
    
    R3 -->|No| Rule3[RULE 3<br/>Fail before commit<br/>Break it on purpose first]
    R3 -->|Yes| R4{Did you discover<br/>you're wrong?}
    
    R4 -->|Yes| Choice{What did you do?}
    Choice -->|Defended| Wrong[BROKE RULE 4<br/>Revision before prestige<br/>Update faster than defend]
    Choice -->|Revised| Rule4[RULE 4 ✓<br/>You revised before defending]
    
    R4 -->|Not yet| R5{Has your energy<br/>moved elsewhere?}
    
    R5 -->|Yes| Drift{What did you do?}
    Drift -->|Kept pretending| Wrong2[BROKE RULE 5<br/>Dissolution before drift<br/>Let go when energy moves]
    Drift -->|Dissolved cleanly| Rule5[RULE 5 ✓<br/>You dissolved honestly]
    
    R5 -->|No| Continue[Continue work<br/>You're on track]
    
    Rule1 --> R2
    Rule2 --> R3
    Rule3 --> R4
    Rule4 --> Continue
    Rule5 --> Complete[Work complete<br/>Well done]
    
    style Rule1 fill:#e3f2fd
    style Rule2 fill:#e3f2fd
    style Rule3 fill:#e3f2fd
    style Rule4 fill:#c8e6c9
    style Rule5 fill:#c8e6c9
    style Wrong fill:#ffebee
    style Wrong2 fill:#ffebee
```

**Use this as self-check:** Are you following the rules or breaking them?

---

## How to Use This Guide

### In Your GitHub README:
Copy the entire entry point diagram plus your chosen learning path(s).

### For Quick Reference:
Bookmark the entry point diagram. Come back to learning paths when stuck.

### For Teaching:
- Show entry point first (30 seconds)
- Then ask: "What's your learning style?"
- Direct to appropriate path

### For Video:
- Screen record entry point (under 1 minute)
- Show 2-3 learning paths as "choose your adventure"
- Don't try to show all paths

---

## Technical Notes

### GitHub Rendering:
These diagrams use Mermaid syntax and will auto-render in GitHub markdown files. Just paste the code blocks as-is.

### Export as Images:
1. Paste into GitHub (renders automatically)
2. Screenshot the rendered diagram, OR
3. Use https://mermaid.live to export as PNG/SVG

### Customize:
All diagrams are editable. Change colors, text, structure as needed.

### Color Coding:
- Blue (#e1f5ff, #e3f2fd) = Foundation, principles
- Yellow (#fff9c4, #fff4e1) = Evidence, operations
- Red (#ffebee, #ffcdd2) = Critical actions (Fail), warnings
- Green (#c8e6c9) = Completion, success states
- Gray (#f0f0f0) = Process, meta-level

---

**Version 4.0 | November 2025**

**All diagrams reflect:**
- Truth, Love, Rigor (three values)
- Process above values
- Evidence as proof
- Individual or collaborative capabilities
- Mandatory Fail() before Commit()
- Fractal structure
- Five rules
