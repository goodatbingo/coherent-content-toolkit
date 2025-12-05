# Variation Rationale Log

## What This Is

When content varies significantly across contexts, document why. This creates institutional knowledge that compounds over time—helping teams understand not just *what* varies, but the reasoning behind it.

**How to use:** Log significant variations when they're created. Review logs during onboarding, audits, and when making related decisions.

---

## When to Log Variations

Log a variation when:

✓ Content differs significantly from another context's version
✓ The variation was a deliberate choice, not an accident
✓ Future team members might question the difference
✓ The reasoning isn't obvious from context
✓ Similar variations might be needed in the future

Don't log:
- Minor length adjustments
- Obvious channel constraints (character limits, etc.)
- Variations fully covered by existing patterns

---

## Variation Log Template

### Entry #___

**Date:** _______________  
**Logged by:** _______________

---

#### Content Identifier

| Field | Entry |
|-------|-------|
| **Content name/title** | |
| **Source content location** | |
| **Variant content location** | |
| **Content type** | □ Core  □ Reference  □ Operational  □ Conversational |

---

#### The Variation

**Source version (or summary):**

> _____________________________________________________________________________
> 
> _____________________________________________________________________________

**Variant version (or summary):**

> _____________________________________________________________________________
> 
> _____________________________________________________________________________

**Key differences:**

- [ ] Length/depth
- [ ] Tone/voice
- [ ] Structure/format
- [ ] Included information
- [ ] Terminology
- [ ] Call to action
- [ ] Other: _______________

---

#### The Rationale

**Why does this content vary?**

| Reason Category | Explanation |
|----------------|-------------|
| **User context** | |
| **Channel constraints** | |
| **Goal difference** | |
| **Expertise level** | |
| **Legal/regulatory** | |
| **Cultural adaptation** | |
| **Other** | |

**What coherence markers are preserved?**

- [ ] User agency treatment
- [ ] Complexity handling  
- [ ] Trust-building approach
- [ ] Business-user balance
- [ ] Attention philosophy
- [ ] Other: _______________

**What would be lost if we forced consistency?**

> _____________________________________________________________________________

---

#### Decision Details

**Who made this decision?**

_______________________________________________________________________________

**Was this validated? How?**

- [ ] User testing
- [ ] A/B testing
- [ ] Expert review
- [ ] Stakeholder alignment
- [ ] Team discussion
- [ ] Not validated (yet)

**Confidence level:**

- [ ] High - validated and performing well
- [ ] Medium - makes sense, not yet validated
- [ ] Low - best guess, needs validation

---

#### Future Reference

**When might we revisit this variation?**

- [ ] Never - this is permanent
- [ ] When source changes
- [ ] After performance data
- [ ] During next audit
- [ ] Other: _______________

**Related variations to consider:**

_______________________________________________________________________________

**Tags/categories:**

_______________________________________________________________________________

---

## Sample Completed Entry

### Entry #017

**Date:** October 15, 2024  
**Logged by:** Maria Chen, Content Design

---

#### Content Identifier

| Field | Entry |
|-------|-------|
| **Content name/title** | Account deletion confirmation |
| **Source content location** | Web app: Settings > Delete Account |
| **Variant content location** | Mobile app: Profile > Account > Delete |
| **Content type** | ☑ Core  □ Reference  □ Operational  □ Conversational |

---

#### The Variation

**Source version (web):**

> **Delete your account?**
> 
> This will permanently delete your account and all associated data. This action cannot be undone.
> 
> Before you go:
> - Download your data (link)
> - Review what will be deleted (link)
> - Consider pausing instead (link)
> 
> [Cancel] [Delete my account]

**Variant version (mobile):**

> **Delete account?**
> 
> This permanently deletes your account and data.
> 
> [Keep account] [Delete]
> 
> Download data first →

**Key differences:**

- [x] Length/depth
- [ ] Tone/voice
- [x] Structure/format
- [x] Included information
- [ ] Terminology
- [x] Call to action
- [ ] Other

---

#### The Rationale

| Reason Category | Explanation |
|----------------|-------------|
| **User context** | Mobile users more likely to be in quick task mode |
| **Channel constraints** | Screen real estate; mobile scrolling adds friction |
| **Goal difference** | Same goal but mobile needs faster completion |
| **Expertise level** | Same |
| **Legal/regulatory** | Both include required warning language |
| **Cultural adaptation** | N/A |
| **Other** | Mobile users who want details can tap through |

**What coherence markers are preserved?**

- [x] User agency treatment - Both give choice, both enable data download
- [x] Complexity handling - Both warn of permanence; web offers more detail proactively
- [x] Trust-building approach - Both transparent about consequences
- [x] Business-user balance - Both offer alternatives to deletion
- [x] Attention philosophy - Mobile respects limited mobile attention

**What would be lost if we forced consistency?**

> Using web version on mobile would create friction through scrolling and reduce completion rate for users who have decided to delete. Using mobile version on web would miss opportunity to provide helpful alternatives to users who might not have decided firmly.

---

#### Decision Details

**Who made this decision?**

Product design + content design + legal review

**Was this validated? How?**

- [x] User testing - Mobile prototype tested with 12 users
- [ ] A/B testing
- [x] Expert review - Legal confirmed both meet requirements
- [x] Stakeholder alignment
- [ ] Team discussion
- [ ] Not validated

**Confidence level:**

- [x] High - validated and performing well
- [ ] Medium
- [ ] Low

---

#### Future Reference

**When might we revisit this variation?**

- [ ] Never
- [x] When source changes
- [ ] After performance data
- [x] During next audit
- [ ] Other

**Related variations to consider:**

Similar pattern needed for subscription cancellation flow (entry #023)

**Tags/categories:**

`account-management` `high-stakes` `mobile-adaptation` `legal-reviewed`

---

## Log Index

Maintain a quick-reference index of all logged variations:

| # | Date | Content | Reason Category | Confidence |
|---|------|---------|-----------------|------------|
| 001 | | | | |
| 002 | | | | |
| 003 | | | | |
| 004 | | | | |
| 005 | | | | |

---

## Using the Log

### For Onboarding
New team members review the log to understand variation patterns and reasoning. Start with high-confidence entries in their content area.

### For Audits
During coherence audits, use the log to verify that documented variations still make sense and undocumented variations get logged.

### For Decision-Making
When facing a new variation decision, search the log for similar situations. Learn from past reasoning.

### For Governance
Use log patterns to update Decision Framework Cards and Adaptive Content Patterns. Codify recurring variation types.

---

*Part of the Distributed Coherence Toolkit by Scott Pierce / Good at Bingo*
