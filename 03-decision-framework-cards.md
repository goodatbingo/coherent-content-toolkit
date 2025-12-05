# Decision Framework Cards

## What This Is

Teams need to make content decisions without routing everything through central review. These framework cards provide clear criteria for distributed decision-making. Print them, keep them visible, and use them when facing common content trade-offs.

**How to use:** When facing a decision, find the relevant card and work through the criteria. Document your reasoning for significant decisions.

---

## Card 1: Personalize vs. Standardize

**The question:** Should this content vary based on user context, or stay the same for everyone?

### Personalize When:

✓ User context significantly changes what's relevant
✓ Personalization creates meaningful value (not just novelty)  
✓ You have reliable data to personalize accurately
✓ Wrong personalization isn't worse than no personalization
✓ Maintenance of multiple versions is sustainable

### Standardize When:

✓ Variation would create confusion about what's true
✓ Legal/regulatory requirements demand consistency
✓ Content establishes foundational understanding everyone needs
✓ Personalization data is unreliable or incomplete
✓ Maintenance burden outweighs personalization value

### Decision Criteria Matrix

| If user context... | And accuracy is... | Then... |
|-------------------|-------------------|---------|
| Changes meaning significantly | High confidence | **Personalize** |
| Changes meaning significantly | Low confidence | Standardize (bad personalization harms trust) |
| Changes only preference | High confidence | Personalize if sustainable |
| Changes only preference | Low confidence | **Standardize** |
| Doesn't change meaning | Any | **Standardize** |

### Quick Test

Ask: "If I showed the 'wrong' version to this user, would it be confusing, irrelevant, or just slightly less optimized?"

- Confusing or irrelevant → Must personalize
- Slightly less optimized → Consider maintenance cost vs. value
- No meaningful difference → Standardize

---

## Card 2: Comprehensive vs. Minimal

**The question:** How much information should this content include?

### Be Comprehensive When:

✓ User is making a consequential decision
✓ Missing information could lead to errors
✓ User has explicitly sought depth (help docs, research mode)
✓ Legal requirements mandate specific disclosures
✓ Content serves as reference to return to

### Be Minimal When:

✓ User is in task-focused flow state
✓ Context already provides most information
✓ Interruption has a high cost (e.g., checkout)
✓ Core message can stand alone
✓ Depth is available elsewhere (link, expand, drill down)

### Decision Criteria Matrix

| User state | Decision weight | Content approach |
|------------|----------------|------------------|
| Seeking/researching | High stakes | **Full comprehensive** |
| Seeking/researching | Low stakes | Comprehensive with scannable structure |
| Doing/flowing | High stakes | Essential + prominent "learn more" |
| Doing/flowing | Low stakes | **Minimal** with access to depth |
| Interrupted/notified | Any | **Minimal** with link to context |

### Quick Test

Ask: "If the user only reads the first sentence/line, will they have what they need to proceed safely?"

- Yes → You can be minimal
- No → Lead with essentials, layer depth
- Never → You need to restructure

---

## Card 3: Match Language vs. Culturally Adapt

**The question:** How much should localized content diverge from the source?

### Match Source Closely When:

✓ Technical precision is critical
✓ Legal accuracy is required
✓ Content will be back-translated or audited
✓ Brand terminology must remain consistent
✓ User expects formal/official register

### Culturally Adapt When:

✓ Natural expression matters more than precision
✓ Source includes idioms, humor, or cultural references
✓ Target audience has different conventions
✓ Tone should feel native, not translated
✓ User experience prioritizes comprehension over consistency

### Adaptation Spectrum

| Content Type | Adaptation Level | Example |
|--------------|-----------------|---------|
| Legal terms | **Exact match** | "Terms of Service" stays literal |
| Technical docs | Minimal adaptation | Clarity edits, terminology localized |
| UI strings | Moderate adaptation | Natural phrasing, cultural fit |
| Marketing | Full adaptation | Rewritten for cultural resonance |
| Support | High adaptation | Match local communication norms |

### Quick Test

Ask: "If a native speaker reads this, will it feel like it was written *for* them or *translated* to them?"

- Written for them → Appropriate adaptation
- Translated to them → May need more adaptation (or may be appropriate for formal contexts)

---

## Card 4: Proactive vs. Reactive Information

**The question:** Should we provide this information before users ask, or wait until they need it?

### Be Proactive When:

✓ Information prevents costly mistakes
✓ Users commonly need this but don't know to ask
✓ Delay would create significant friction
✓ Information shapes expectations helpfully
✓ Regulatory requirements mandate disclosure

### Be Reactive When:

✓ Information is relevant to only some users
✓ Proactive disclosure would overwhelm
✓ User context determines relevance
✓ Information is edge case, not common path
✓ Space/attention is limited

### Decision Criteria Matrix

| If users need this... | And consequence of not knowing... | Then... |
|----------------------|----------------------------------|---------|
| Almost always | Significant | **Proactive, prominent** |
| Almost always | Minor | Proactive, accessible |
| Sometimes | Significant | Proactive for at-risk users, reactive otherwise |
| Sometimes | Minor | **Reactive** (on demand) |
| Rarely | Any | **Reactive** (buried appropriately) |

### Quick Test

Ask: "What percentage of users will regret not knowing this sooner?"

- >50% → Proactive
- 10-50% → Proactive with progressive disclosure
- <10% → Reactive

---

## Card 5: Urgent vs. Patient Tone

**The question:** How much urgency should this content convey?

### Be Urgent When:

✓ Time genuinely affects outcome
✓ Delay creates real risk or loss
✓ User needs to act *now* vs. later
✓ Scarcity is real, not manufactured

### Be Patient When:

✓ Decision benefits from reflection
✓ Urgency would create pressure users resent
✓ Timeline is flexible
✓ Urgency has been overused (user fatigue)

### Urgency Calibration

| Situation | Urgency Level | Expression |
|-----------|---------------|------------|
| Security threat | **Immediate action required** | Direct, action-first, no softening |
| Time-limited opportunity | Time-aware | Clear deadline, but not alarmist |
| Recommended action | Suggested | "When you're ready" framing |
| Optional enhancement | Patient | No time pressure, value focus |
| Informational | **Neutral** | Pure information, user decides timing |

### Quick Test

Ask: "If the user waits a day/week to act, what happens?"

- Significant negative outcome → Appropriate urgency
- Minor inconvenience → Note time sensitivity without pressure
- Nothing → Remove urgency cues

### Warning Signs of Over-Urgency

- Using "now" when timing doesn't matter
- Countdown timers for artificial deadlines
- Exclamation points in routine messages
- "Limited time" that isn't limited
- "Don't miss" for things that can be accessed later

---

## Card 6: Explain vs. Direct

**The question:** Should we explain the reasoning or just tell users what to do?

### Explain When:

✓ Users will make better decisions with understanding
✓ Building mental model helps future interactions
✓ Trust is built through transparency
✓ Users may question or resist without reasoning
✓ Explanation prevents repeated mistakes

### Direct When:

✓ Action is simple and obvious
✓ Delay has cost (time, attention, error)
✓ User has signaled preference for efficiency
✓ Reasoning is complex but action is clear
✓ Explanation is available but not required

### Decision Criteria Matrix

| User expertise | Stakes | Approach |
|---------------|--------|----------|
| Low | High | **Explain** (reduces errors) |
| Low | Low | Direct (explanation on demand) |
| High | High | Context + direct (they'll fill gaps) |
| High | Low | **Direct** (respect their time) |

### Layered Approach

When both explanation and direction have value:

1. **Lead with direction** (the action)
2. **Follow with brief why** (one sentence)
3. **Offer deeper explanation** (learn more link)

Example:
> Enter your backup email. We'll use this for account recovery if you lose access to your primary email. [Why we ask →]

---

## Card 7: Brand Voice vs. Clarity

**The question:** When brand expression and clarity conflict, which wins?

### Prioritize Clarity When:

✓ User is in problem-solving mode
✓ Content is instructional or procedural
✓ Misunderstanding has consequences
✓ User may be stressed or frustrated
✓ Content will be translated

### Allow Brand Expression When:

✓ User is in browsing/exploring mode
✓ Content is relational, not transactional
✓ Brand differentiation creates value
✓ User expects and enjoys brand personality
✓ Clarity is already established

### The Clarity Rule

**Clarity always wins for:**
- Error messages
- Security warnings
- Legal/financial information
- Instructions and procedures
- Accessibility-dependent content

**Brand can shine for:**
- Welcome/celebration moments
- Marketing and promotional content
- Empty states and delighters
- Relational communications
- Content where personality builds trust

### Quick Test

Ask: "If I removed all brand personality from this content, would it still work?"

- Yes, works fine → Brand is a bonus, not a crutch
- No, would be confusing → Brand is obscuring clarity (fix it)
- No, would lose trust → Brand is doing important work (keep it)

---

## Using These Cards

### For Individual Decisions

1. Identify which card(s) apply to your situation
2. Work through the criteria
3. Make and document your decision
4. Note the rationale for future reference

### For Team Calibration

1. Review cards together quarterly
2. Discuss recent decisions that felt unclear
3. Add team-specific guidance to cards as needed
4. Share exemplar decisions with rationale

### For Onboarding

1. New team members review all cards
2. Discuss 2-3 real decisions using each card
3. Shadow experienced team member using cards
4. Graduate to independent use with spot checks

---

*Part of the Distributed Coherence Toolkit by Scott Pierce / Good at Bingo*
