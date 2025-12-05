# Adaptive Content Pattern Templates

## What This Is

Patterns enable appropriate variation. Unlike templates that enforce uniformity, patterns show what must be present while providing guidance for contextual adaptation. Each pattern includes required elements, contextual elements, and adaptation guidance.

**How to use:** Select the pattern closest to your content need, then adapt based on context.

---

## Pattern 1: Feature Introduction

Use when introducing a new capability, tool, or functionality to users.

### Required Elements

These must be present in every feature introduction, though their expression varies:

| Element | Purpose | Cannot Be Omitted Because |
|---------|---------|---------------------------|
| **Value proposition** | Why this matters to users | Users need motivation before mechanics |
| **Core capability** | What it enables them to do | Users need to know what's possible |
| **Next action** | How to start using it | Users need a clear path forward |

### Contextual Elements

Include based on situation:

| Element | Include When | Omit When |
|---------|--------------|-----------|
| Prerequisites | Feature requires setup or eligibility | Feature is universally available |
| Limitations | Constraints affect common use cases | Limitations are edge cases |
| Related features | Natural workflow connections exist | Would distract from primary value |
| Pricing/tier info | Affects availability | Included elsewhere in journey |

### Adaptation Guidance

**For expert users:**
- Lead with capability, follow with value
- Use technical terminology without definition
- Compress or omit basics they'll know
- Emphasize advanced applications

**For novice users:**
- Lead with value, follow with capability
- Define technical terms or use plain language
- Include foundational context
- Emphasize common applications

**By channel:**

| Channel | Emphasis | Length Guidance |
|---------|----------|-----------------|
| In-app tooltip | Next action | 1-2 sentences |
| Help article | Complete picture | 200-500 words |
| Email announcement | Value + urgency | 100-200 words |
| Marketing page | Value + differentiation | Variable |
| Push notification | Action only | < 50 characters |

### Example Variations

**Same feature, different contexts:**

*Expert user, in-app:*
> **Bulk Actions** now supports conditional logic. Select items → Actions → Add conditions.

*Novice user, help article:*
> Bulk Actions lets you make changes to many items at once, saving you time on repetitive tasks. For example, you could update the status of all items from last month in a single action. To get started, select the items you want to change, click the Actions button, and choose your action.

*Email announcement:*
> You asked, we built: Bulk Actions now handles conditional logic—update hundreds of items based on specific criteria in seconds. Try it today in your dashboard.

---

## Pattern 2: Error Message

Use when something has gone wrong and users need to understand and recover.

### Required Elements

| Element | Purpose | Cannot Be Omitted Because |
|---------|---------|---------------------------|
| **What happened** | User understands the situation | Reduces confusion and anxiety |
| **Impact** | User knows what this means for them | Enables appropriate response |
| **Recovery path** | User can move forward | Prevents dead-ends |

### Contextual Elements

| Element | Include When | Omit When |
|---------|--------------|-----------|
| Why it happened | Explanation helps user avoid recurrence | Cause is technical/irrelevant |
| Technical details | User can take action on them | Would only confuse |
| Alternative paths | Primary recovery may not work | Clear single recovery path |
| Support contact | Issue may require human help | Self-service resolution certain |
| Error code | Needed for support escalation | No support workflow exists |

### Adaptation Guidance

**By severity:**

| Severity | Tone | Detail Level | Recovery Emphasis |
|----------|------|--------------|-------------------|
| Minor (retry will likely work) | Matter-of-fact | Minimal | Immediate action |
| Moderate (user action needed) | Helpful | Moderate | Clear steps |
| Severe (data loss possible) | Calm but serious | Comprehensive | All options |
| Critical (security/safety) | Direct, urgent | Essential only | Immediate action |

**By user expertise:**

| User Type | What Happened | Recovery Path |
|-----------|---------------|---------------|
| Novice | Plain language, no jargon | Explicit step-by-step |
| Intermediate | Concise, some terminology okay | Key steps with flexibility |
| Expert | Technical precision | Options and shortcuts |

### Example Variations

**Same error, different contexts:**

*Novice user, payment failure:*
> **Your payment didn't go through**
> 
> The card ending in 4242 was declined. This sometimes happens when card details have changed or there's a temporary issue with the bank.
> 
> **What to do:**
> - Check that your card details are current
> - Try the payment again
> - Or use a different payment method
>
> Your cart is saved—nothing is lost.

*Expert user, API error:*
> **Payment failed: Card declined (4242)**
> 
> `error_code: card_declined` | `decline_code: insufficient_funds`
> 
> Retry with updated card or alternative payment method. [View declined payment →]

*Push notification:*
> Payment issue with your order. Tap to update payment method.

---

## Pattern 3: Onboarding Step

Use when guiding users through initial setup or learning.

### Required Elements

| Element | Purpose | Cannot Be Omitted Because |
|---------|---------|---------------------------|
| **Step context** | User knows where they are in the process | Reduces anxiety about scope |
| **Action** | User knows what to do | Enables progress |
| **Outcome** | User knows what they'll achieve | Motivates completion |

### Contextual Elements

| Element | Include When | Omit When |
|---------|--------------|-----------|
| Progress indicator | Multi-step process | Single action |
| Skip option | Step is optional or can be done later | Step is required |
| Example/preview | Outcome is hard to visualize | Outcome is obvious |
| Why this matters | Motivation helps completion | User is already committed |
| Time estimate | Step takes significant time | Trivial time investment |

### Adaptation Guidance

**By user motivation:**

| Motivation Level | Emphasis | Tone |
|------------------|----------|------|
| High (chose to start) | Efficiency | Direct, get-it-done |
| Moderate (recommended) | Value | Encouraging, benefit-focused |
| Low (required) | Progress | Reassuring, low-friction |

**By step complexity:**

| Complexity | Guidance Depth | Visual Support |
|------------|----------------|----------------|
| Simple | Minimal | Optional |
| Moderate | Step-by-step | Helpful |
| Complex | Detailed with validation | Essential |

### Example Variations

*High-motivation user, simple step:*
> **Connect your calendar** (Step 2 of 4)
> 
> We'll use this to find meeting times that work. Select your calendar provider below.
>
> [Google Calendar] [Outlook] [Other]

*Moderate-motivation user, complex step:*
> **Set up your preferences** (Step 3 of 5 • ~2 minutes)
> 
> These settings help us personalize your experience. You can change them anytime.
> 
> **Why this matters:** The more accurate your preferences, the better recommendations you'll get.
>
> [Detailed preference form with clear labels and defaults]
>
> [Save and continue] [Skip for now]

---

## Pattern 4: Help/Documentation

Use when users are seeking answers or guidance.

### Required Elements

| Element | Purpose | Cannot Be Omitted Because |
|---------|---------|---------------------------|
| **Direct answer** | User gets what they came for | Primary purpose of help content |
| **Context** | User understands when this applies | Prevents misapplication |
| **Related paths** | User can explore further if needed | Many questions lead to follow-ups |

### Contextual Elements

| Element | Include When | Omit When |
|---------|--------------|-----------|
| Prerequisites | Answer depends on prior setup | Answer is standalone |
| Step-by-step procedure | Process has multiple steps | Single action or concept |
| Screenshots/visuals | UI reference helps comprehension | Concept is abstract |
| Warnings/cautions | Common mistakes are costly | Risk is low |
| Edge cases | Users frequently encounter them | Would overwhelm main answer |

### Adaptation Guidance

**By question type:**

| Question Type | Lead With | Structure |
|---------------|-----------|-----------|
| "How do I...?" | Steps to accomplish goal | Procedure format |
| "What is...?" | Definition/explanation | Concept format |
| "Why does...?" | Explanation of cause | Narrative format |
| "Can I...?" | Yes/no, then conditions | Conditional format |

**By user journey stage:**

| Stage | Assumed Knowledge | Detail Level |
|-------|-------------------|--------------|
| New user | None | Comprehensive |
| Active user | Core concepts | Focused |
| Power user | Full product familiarity | Precise |

---

## Pattern 5: Confirmation/Success

Use when users have completed an action successfully.

### Required Elements

| Element | Purpose | Cannot Be Omitted Because |
|---------|---------|---------------------------|
| **Confirmation** | User knows action succeeded | Removes uncertainty |
| **What happened** | User understands the result | Enables verification |
| **Next steps** | User knows what to do now | Prevents confusion |

### Contextual Elements

| Element | Include When | Omit When |
|---------|--------------|-----------|
| Summary of details | Action involved important specifics | Details are obvious |
| Reference number | User may need to reference later | No future reference needed |
| Timeline | User expects something to happen next | Action is complete |
| Undo option | Action is reversible and consequential | Action is trivial or irreversible |
| Related actions | Natural workflow continues | User should focus on confirmation |

### Adaptation Guidance

**By action consequence:**

| Consequence | Tone | Detail Level |
|-------------|------|--------------|
| Low (saved settings) | Brief | Minimal |
| Moderate (purchase) | Clear | Key details |
| High (major commitment) | Reassuring | Comprehensive |

**By channel:**

| Channel | Emphasis | Length |
|---------|----------|--------|
| In-app toast | Confirmation only | 5-10 words |
| Confirmation page | Full details | Variable |
| Email receipt | Complete record | Comprehensive |
| Push notification | Confirmation + action | < 50 characters |

---

## Pattern 6: Empty State

Use when users encounter an area with no content or data yet.

### Required Elements

| Element | Purpose | Cannot Be Omitted Because |
|---------|---------|---------------------------|
| **Context** | User understands what belongs here | Reduces confusion |
| **Path forward** | User knows how to populate | Enables progress |

### Contextual Elements

| Element | Include When | Omit When |
|---------|--------------|-----------|
| Illustration | Visual helps comprehension | Would feel decorative |
| Value preview | Motivation helps adoption | User already committed |
| Example content | Sample helps understanding | Would feel cluttered |
| Alternative actions | Multiple paths exist | Single clear path |

### Adaptation Guidance

**By expected time to content:**

| Timeline | Emphasis | Tone |
|----------|----------|------|
| Immediate (user will add) | Action | Encouraging |
| Soon (system will populate) | Expectation | Patient |
| Uncertain (depends on events) | Explanation | Informative |

---

## Creating Your Own Patterns

Use this template to develop patterns for content types specific to your product:

### Pattern: [Name]

**Use when:** [Situation description]

### Required Elements

| Element | Purpose | Cannot Be Omitted Because |
|---------|---------|---------------------------|
| | | |

### Contextual Elements

| Element | Include When | Omit When |
|---------|--------------|-----------|
| | | |

### Adaptation Guidance

[Add guidance by user type, channel, context, or other relevant dimensions]

### Example Variations

[Show the same content need addressed in different contexts]

---

*Part of the Distributed Coherence Toolkit by Scott Pierce / Good at Bingo*
