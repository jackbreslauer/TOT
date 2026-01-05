# Health Insights App - Requirements

## Core Concept
An iOS app that reads health data from Apple HealthKit, sends it to an LLM, and displays personalized health recommendations.

---

## Screens

### 1. Onboarding
- Explain what the app does
- Request HealthKit permissions
- (TBD: Account creation? Or anonymous?)

### 2. Home / Dashboard
- Display recent health data summary
- Show latest insight
- (TBD: What data to highlight?)

### 3. Insight Detail
- Full LLM-generated recommendation
- Context: what data informed this insight
- (TBD: Ability to ask follow-up questions?)

### 4. History
- List of past insights
- (TBD: How far back? Searchable?)

### 5. Settings
- Manage HealthKit permissions
- Preferences
- (TBD: What preferences?)

---

## Open Questions

- [ ] How often should new insights generate? (Daily / On app open / On-demand)
- [ ] What HealthKit data types to collect? (Steps, heart rate, sleep, etc.)
- [ ] What's the core value prop / positioning?
- [ ] Account system needed, or fully local/anonymous?
- [ ] LLM provider? (OpenAI, Anthropic, etc.)

---

## Decisions Made

(We'll log decisions here as we make them)

---

## Out of Scope (v1)
- Apple Watch companion app
- Social/sharing features
- (Add things here as we decide to defer them)
