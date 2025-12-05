# Content Source Types Matrix

## What This Is

Not all content needs the same governance approach. This matrix helps teams categorize content into four types, each with different adaptation rules, ownership models, and review requirements.

**How to use:** Classify your content, apply the appropriate governance model, and ensure your systems support the distinctions.

---

## The Four Content Source Types

| Type | Definition | Adaptation Level | Governance Model |
|------|------------|------------------|------------------|
| **Core** | Strategic content expressing brand values and key messages | High adaptation to context | Principle-driven, distributed creation |
| **Reference** | Factually precise content that must remain accurate | Minimal adaptation | Centrally maintained, locally linked |
| **Operational** | Transactional content with predictable patterns | Template-based variation | Systematically generated |
| **Conversational** | Dynamic content responding to user context | Never identical | AI-guided with principle guardrails |

---

## Type 1: Core Content

### Definition

Core content expresses your organization's strategic positioning, value propositions, and key messages. It's what makes you *you*.

### Examples

- Product value propositions
- Brand positioning statements
- Key differentiators
- Mission/purpose expressions
- Voice and tone exemplars

### Governance Model

| Aspect | Approach |
|--------|----------|
| **Ownership** | Central strategy team owns principles; local teams own execution |
| **Creation** | Distributed, guided by coherence markers |
| **Review** | Self-review against principles; spot-check audits |
| **Updates** | Central principles change rarely; local execution changes frequently |
| **Variation** | Expected and encouraged across contexts |

### Adaptation Rules

**What stays the same:**
- Core value proposition (the "why it matters")
- Brand positioning
- Key claims and promises
- Underlying intent

**What adapts:**
- Length and depth
- Examples and specifics
- Tone intensity
- Channel-appropriate framing

### Example: Feature Value Proposition

**Core principle:** "We save users time by automating routine decisions"

**Web marketing:**
> Stop making the same decisions over and over. [Product] learns your patterns and handles the routine so you can focus on what matters.

**In-app tooltip:**
> We'll handle the routine tasks based on your patterns. Check automation settings anytime.

**Email announcement:**
> Your daily decisions, automated. [Product] now learns from your patterns to handle routine tasks automatically.

**Sales deck:**
> [Product] drives 40% productivity gains by automating routine decisions based on learned user patterns.

Same core principle, four appropriate expressions.

---

## Type 2: Reference Content

### Definition

Reference content must remain factually accurate across all instances. Accuracy matters more than adaptation.

### Examples

- Technical specifications
- Legal terms and conditions
- Pricing information
- Security/compliance statements
- Product capabilities (factual)
- Regulatory disclosures

### Governance Model

| Aspect | Approach |
|--------|----------|
| **Ownership** | Central team owns content; updates flow outward |
| **Creation** | Centralized authorship |
| **Review** | SME and legal review before publication |
| **Updates** | Controlled process; all instances update together |
| **Variation** | Link to authoritative source; minimize embedding |

### Adaptation Rules

**What stays the same:**
- Factual content
- Claims and specifications
- Legal language
- Numbers and dates

**What adapts:**
- Surrounding context
- Introduction/framing
- Level of detail shown (can truncate but not alter)
- Navigation to full reference

### Best Practice: Wrapper + Reference

Instead of embedding reference content everywhere (which drifts), use a wrapper pattern:

```
[Contextual wrapper - adapted]
Your account is protected by industry-standard security.

[Reference content - linked]
View our complete security practices →

[Reference content - embedded if required]
"Data encrypted with AES-256 at rest and TLS 1.3 in transit."
(This exact text controlled by central source)
```

### Reference Content Inventory Template

| Content | Source of Truth | Update Owner | Update Trigger | Dependent Locations |
|---------|-----------------|--------------|----------------|---------------------|
| Pricing | pricing-system | Finance | Price change | Web, app, email, sales |
| Security specs | security-docs | Security | Audit/change | Help, marketing, contracts |
| Legal terms | legal-repo | Legal | Policy change | All surfaces |

---

## Type 3: Operational Content

### Definition

Operational content follows predictable patterns for transactional interactions. The structure is consistent; variables change.

### Examples

- Order confirmations
- Password reset emails
- System notifications
- Status updates
- Receipt/invoice content
- Automated alerts

### Governance Model

| Aspect | Approach |
|--------|----------|
| **Ownership** | Product/ops owns templates; central content sets standards |
| **Creation** | Template + variable system |
| **Review** | Template review; individual instances not reviewed |
| **Updates** | Template changes propagate automatically |
| **Variation** | Structured by template; variables provide customization |

### Adaptation Rules

**What's templated:**
- Message structure
- Required elements
- Tone and voice
- Formatting

**What varies (variables):**
- User name
- Transaction details
- Dates/times
- Amounts
- Status-specific language

### Template Design Principles

1. **Front-load the key information**
   - Subject line/preview: What happened
   - First line: What the user needs to know
   - Details: Supporting information

2. **Handle edge cases in template logic**
   - Conditional blocks for different states
   - Graceful degradation when variables missing

3. **Build in appropriate tone ranges**

| Transaction Outcome | Tone Modifier |
|--------------------|---------------|
| Success | Warm, confirming |
| Pending | Patient, reassuring |
| Problem | Direct, solution-focused |
| Failure | Empathetic, action-oriented |

### Example: Order Status Template Structure

```
SUBJECT: [tone_modifier] Your order #[order_id] [status_phrase]

Hi [customer_name],

[status_message]

[IF has_tracking]
Track your package: [tracking_link]
[/IF]

[IF has_issue]
What happened: [issue_explanation]
What to do: [resolution_steps]
[/IF]

Order details:
[item_list]
Total: [order_total]

[IF status=delivered]
Thanks for shopping with us!
[/IF]

[IF status=issue]
Questions? Reply to this email or call [support_number].
[/IF]
```

---

## Type 4: Conversational Content

### Definition

Conversational content is dynamically generated in response to user context. It's never identical because context never is.

### Examples

- Chatbot responses
- AI-generated summaries
- Personalized recommendations
- Search result descriptions
- Dynamic help responses
- Voice assistant interactions

### Governance Model

| Aspect | Approach |
|--------|----------|
| **Ownership** | AI/ML team owns systems; content team owns principles |
| **Creation** | AI-generated within guardrails |
| **Review** | Principle compliance; output sampling; edge case monitoring |
| **Updates** | Training data and prompt updates; continuous improvement |
| **Variation** | Expected; every instance contextually appropriate |

### Guardrail Framework

Instead of reviewing outputs, govern inputs:

| Guardrail Type | What It Controls | Example |
|----------------|------------------|---------|
| **Tone boundaries** | Voice expression range | "Friendly but not casual; helpful but not pushy" |
| **Content boundaries** | What can/cannot be said | "Never promise specific timelines without system data" |
| **Accuracy requirements** | Fact-checking standards | "Product specs must match database; hedging required for estimates" |
| **Escalation triggers** | When to involve humans | "Complaints, legal questions, safety concerns" |
| **Coherence markers** | Brand consistency | Reference Coherence Markers Worksheet |

### Monitoring and Quality

Since you can't review every output, monitor systematically:

| Metric | What It Catches | Response |
|--------|-----------------|----------|
| User satisfaction (post-interaction) | Effectiveness issues | Review low-rated conversations |
| Escalation rate | Scope/capability gaps | Expand training or boundaries |
| Fallback frequency | Understanding failures | Improve intent recognition |
| Coherence sampling | Brand drift | Adjust prompts/training |
| Edge case flags | Boundary violations | Refine guardrails |

---

## Content Type Classification Worksheet

For each major content category in your organization, classify and assign governance:

| Content Category | Type | Adaptation Level | Owner | Review Model |
|------------------|------|------------------|-------|--------------|
| Homepage value props | Core | High | Marketing | Principle-based |
| Pricing page | Reference | Minimal | Finance | SME review |
| Order confirmation | Operational | Template | Product | Template review |
| Support chatbot | Conversational | Dynamic | Support + AI | Guardrail monitoring |
| | | | | |
| | | | | |
| | | | | |
| | | | | |

---

## Governance Summary

| Type | Central Controls | Local Freedom | Review Burden |
|------|-----------------|---------------|---------------|
| **Core** | Principles, coherence markers | Expression, adaptation | Low (self-review) |
| **Reference** | Content itself | Surrounding context | High (SME required) |
| **Operational** | Templates, standards | None within template | Low (template-level) |
| **Conversational** | Guardrails, training | Every instance | Medium (sampling) |

---

*Part of the Distributed Coherence Toolkit by Scott Pierce / Good at Bingo*
