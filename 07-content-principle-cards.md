# Content Principle Cards

## What This Is

Portable reference cards that help teams make contextually appropriate decisions across 12+ channel types. Each card states a principle, then shows how to apply it in different moments and contexts.

**How to use:** Print these cards. Keep them at your desk. Reference them when making content decisions. Customize with your own principles.

---

## Card 1: Respect User Attention

### The Principle

User attention is borrowed, not owned. Every word must justify its presence.

### By Moment Type

| Moment | User State | Content Approach |
|--------|------------|------------------|
| **High-attention** (signup, purchase, settings) | Invested, willing to engage | Be complete and clear. Users are ready to read. |
| **Ambient** (browsing, exploring, dashboard) | Scanning, filtering | Be minimal and scannable. Earn deeper attention. |
| **Interruption** (notifications, alerts, popups) | Disrupted, potentially annoyed | Be brief and actionable. Justify the interruption. |

### By Channel

| Channel | Attention Constraint | Implication |
|---------|---------------------|-------------|
| Push notification | Seconds | Action or single key fact only |
| Email | 11 seconds average | Subject + first line must deliver value |
| In-app modal | Medium (user chose to be here) | Complete but not exhaustive |
| Help article | High (user sought help) | Comprehensive with clear structure |
| Marketing page | Variable (user evaluating) | Scannable with depth available |

### Quick Checks

Before publishing, ask:

- [ ] Would the user thank me for this content, or resent the time?
- [ ] Could I remove 20% without losing essential meaning?
- [ ] Is the most important information visible first?

---

## Card 2: Lead with What Users Need

### The Principle

Start with what users came for. Context and caveats come after.

### By Moment Type

| Moment | User Need | Lead With |
|--------|-----------|-----------|
| **Task completion** | Finish what they started | The action or confirmation |
| **Problem-solving** | Fix what's broken | The solution or next step |
| **Decision-making** | Choose wisely | The key differentiator or recommendation |
| **Learning** | Understand something | The core concept or answer |

### By Channel

| Channel | What Users Came For | Lead Example |
|---------|-------------------|--------------|
| Search results | Answer to their query | Direct answer first, source second |
| Error message | How to fix it | Recovery action first, explanation second |
| Confirmation email | Proof it worked | Confirmation first, details second |
| Feature description | Whether it's for them | Benefit first, mechanics second |
| Settings page | How to change it | Controls first, explanations nearby |

### Anti-Pattern: Context-First

❌ "Before you can use this feature, you'll need to understand how our permission system works..."

✓ "To enable this feature, go to Settings > Permissions. You'll need admin access."

### Quick Checks

- [ ] Does the first sentence answer "why is this user here?"
- [ ] Could I move the first paragraph's last sentence to the beginning?
- [ ] Am I protecting myself (CYA) at the cost of user efficiency?

---

## Card 3: Match Tone to Stakes

### The Principle

Tone should calibrate to what's at risk for the user.

### Tone Calibration Matrix

| Stakes | User Emotion | Appropriate Tone | Avoid |
|--------|--------------|------------------|-------|
| **Critical** (security, data loss, money) | Anxious, worried | Direct, calm, action-focused | Casualness, humor |
| **High** (important decisions, deadlines) | Focused, serious | Clear, supportive, thorough | Flippancy, vagueness |
| **Medium** (typical tasks, routine) | Neutral, task-oriented | Helpful, efficient, friendly | Over-formality, excessive warmth |
| **Low** (exploration, delight moments) | Curious, open | Warm, expressive, engaging | Pushiness, corporate-speak |

### By Channel

| Channel | Typical Stakes | Tone Guidance |
|---------|---------------|---------------|
| Security alert | Critical | No personality—clarity and urgency only |
| Payment confirmation | High | Reassuring, complete, professional |
| Onboarding | Medium | Encouraging, helpful, patient |
| Empty state | Low | Warm, inviting, brand-forward |
| Marketing email | Variable | Match to content stakes, not channel |

### Common Mistakes

| Mistake | Example | Fix |
|---------|---------|-----|
| Casual when critical | "Oops! We couldn't process your payment 😅" | "Your payment didn't go through. Here's how to fix it." |
| Formal when friendly | "We are pleased to inform you that your settings have been successfully updated." | "Got it! Your settings are updated." |
| Urgent when routine | "Don't miss this! Update available!" | "A new update is available." |

---

## Card 4: Provide Escape Hatches

### The Principle

Never trap users. Always show them a way out, back, or around.

### Escape Hatch Types

| Situation | Escape Hatch | Example |
|-----------|--------------|---------|
| Dead end | Alternative path | "Can't find what you need? Try search or contact support." |
| Irreversible action | Undo or pause | "Changed your mind? You have 30 days to reactivate." |
| Commitment ask | Graceful decline | "Not now" / "Maybe later" / "Remind me" |
| Mandatory flow | Skip or defer | "Skip this step" / "I'll do this later" |
| Error state | Recovery path | "Try again" / "Start over" / "Get help" |

### By Channel

| Channel | Critical Escape Hatches |
|---------|------------------------|
| Modal/popup | Clear close button; click-outside dismissal |
| Email | Unsubscribe (required); preferences link |
| Notification | Dismiss; notification settings access |
| Form | Cancel; save draft; partial completion |
| Wizard/flow | Back; save progress; exit without losing work |

### User Agency Signals

Look for phrases that trap:

❌ "You must complete this step"  
✓ "Complete this step to continue, or save and finish later"

❌ "Your only option is..."  
✓ "The best option is... You could also..."

❌ [Modal with only one button]  
✓ [Modal with primary action AND dismiss option]

### Quick Checks

- [ ] Can the user get out of this screen/flow if they want to?
- [ ] Have I made the escape hatch visible but not dominant?
- [ ] If this is truly mandatory, have I explained why?

---

## Card 5: Acknowledge Before Asking

### The Principle

Before asking for something, acknowledge what you're asking.

### Acknowledgment Framework

| When Asking For | Acknowledge |
|-----------------|-------------|
| Personal data | Why you need it and how you'll protect it |
| Time/effort | That this takes effort and what they'll get |
| Money | The value they're receiving |
| Patience (loading, processing) | What's happening and roughly how long |
| Difficult action | That this is hard/unpleasant and why it matters |
| Trust | That you understand trust must be earned |

### By Channel

| Channel | Ask Type | Acknowledgment |
|---------|----------|----------------|
| Sign-up form | Data | "We'll use this to personalize your experience." |
| Upsell prompt | Money + attention | "This is a paid feature. Here's what you get." |
| Survey request | Time | "Quick question—takes about 30 seconds." |
| Permission request | Access | "We need this to send you notifications. You can change this anytime." |
| Difficult flow | Effort | "This takes a few steps, but we'll guide you through." |

### Anti-Pattern: Ask Without Context

❌ "Enter your phone number" [required field]  
✓ "Enter your phone number for account recovery. We won't use it for marketing."

❌ "Allow notifications?" [system prompt]  
✓ "Stay updated on order status. Allow notifications?" → [system prompt]

❌ "Subscribe for $9.99/month" [button]  
✓ "Get unlimited access for $9.99/month. Cancel anytime." [button]

### Quick Checks

- [ ] If I were the user, would I know why I'm being asked this?
- [ ] Have I addressed the most likely concern or objection?
- [ ] Is the value exchange clear?

---

## Card 6: Be Honest About Limitations

### The Principle

Transparency about what you can't do builds trust in what you can.

### Limitation Types

| Limitation Type | How to Handle | Example |
|-----------------|---------------|---------|
| Feature constraint | State clearly, offer alternative | "Search only covers the last 90 days. For older records, contact support." |
| Data uncertainty | Qualify appropriately | "This estimate is based on typical usage. Your results may vary." |
| System status | Be specific about impact | "Some features are unavailable right now. Expected back at 3pm PT." |
| Knowledge gap | Admit and redirect | "I don't have that information. Here's how to find it." |
| Partial answer | Be clear about scope | "This covers the basics. For advanced scenarios, see [documentation]." |

### By Channel

| Channel | Limitation Context | Handling |
|---------|-------------------|----------|
| Search results | Not finding what user wants | "No results for X. Try Y or browse categories." |
| AI response | Uncertainty or knowledge gap | "I'm not certain about this. Here's what I know..." |
| Estimate/calculation | Based on assumptions | "Based on [assumptions]. Actual may vary because..." |
| Time prediction | Inherently uncertain | "Usually takes 3-5 days. We'll email you with updates." |

### Honesty Signals

Trust-building phrases:
- "I'm not sure, but..."
- "This is an estimate..."
- "Your experience may differ because..."
- "There are limitations..."
- "This doesn't cover..."

Trust-breaking phrases:
- "Guaranteed!" (when it's not)
- "Only takes a minute!" (when it takes longer)
- "Easy!" (when it's complex)
- Omitting important caveats

---

## Card 7: Write for the Moment After

### The Principle

Consider what happens after the user reads this content.

### The Next Moment

| Current Content | Moment After | Content Should Enable |
|-----------------|--------------|----------------------|
| Error message | User tries to fix | Clear fix path; fallback if fix fails |
| Confirmation | User may need reference | Key details; reference number; timeline |
| Instructions | User does the thing | Each step actionable; recovery for mistakes |
| Announcement | User evaluates relevance | Quick assess of "is this for me?" |
| Warning | User decides action | Clear stakes; clear options |

### By Channel

| Channel | After This, User Will... | Therefore... |
|---------|--------------------------|--------------|
| Push notification | Tap or dismiss | Content must be complete enough to dismiss OR compelling enough to tap |
| Email | Archive, delete, or act | Subject + preview must enable triage; body must enable action |
| Help article | Try the solution | Every step must be actionable; failure scenarios anticipated |
| Onboarding | Use the feature | Immediately usable knowledge, not comprehensive background |
| Settings | Continue with task | Feedback on save; clear next location |

### Future-Proofing Questions

- [ ] What will the user try to do after reading this?
- [ ] Have I given them what they need for that next step?
- [ ] If something goes wrong next, does this content help?
- [ ] Will this content make sense if they return to it later?

---

## Card 8: [Template for Your Principles]

### The Principle

_____________________________________________________________________________

### By Moment Type

| Moment | User State | Content Approach |
|--------|------------|------------------|
| **High-attention** | | |
| **Ambient** | | |
| **Interruption** | | |

### By Channel

| Channel | Constraint/Context | Implication |
|---------|-------------------|-------------|
| | | |
| | | |
| | | |

### Quick Checks

- [ ] 
- [ ] 
- [ ] 

---

## Using These Cards

### Daily Reference
Keep cards visible at your workspace. Reference when making decisions.

### Team Calibration
Review cards together quarterly. Discuss examples where principles applied (or didn't).

### Onboarding
New team members read all cards, then discuss 2-3 real decisions using each.

### Customization
Add your organization's specific principles using the template card.

---

*Part of the Distributed Coherence Toolkit by Scott Pierce / Good at Bingo*
