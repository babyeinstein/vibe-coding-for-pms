# PM Code Review Workflow

## Basic Steps
1. Get PR code locally
2. Review using the checklist below
3. Clean up after reviewing (delete branch)

## Code Review Checklist

### Business Logic
- **Does this solve the right problem?**
  - Does the implementation match the requirements/stories?
  - Are edge cases handled appropriately?
  - Does the business logic align with product strategy?

### User Experience & Flow
- **Will users understand this?**
  - Is the user flow intuitive and logical?
  - Are error messages clear and helpful?
  - Does the UI/UX match the intended user journey?
  - Are there any confusing or unexpected behaviors?

### Data Integrity & Technical Safety
- **Will this break things?**
  - Are database changes safe and reversible?
  - Is data validation properly implemented?
  - Are there potential race conditions or conflicts?
  - Does this maintain backward compatibility?

### Product Quality
- **Does this meet our quality standards?**
  - Are accessibility requirements met?
  - Is performance acceptable for the use case?
  - Does this follow our design system/patterns?
  - Are there any obvious bugs or issues?

### Edge Cases & Error Handling
- **What happens when things go wrong?**
  - How does the system handle invalid inputs?
  - What happens during network failures?
  - Are error states gracefully managed?
  - Is there proper logging for debugging?


## Questions to Ask During Review

1. **For Business Logic:**
   - "Does this match our product requirements?"
   - "Are we handling all the business rules correctly?"
   - "What happens in edge cases?"

2. **For User Experience:**
   - "Will users find this intuitive?"
   - "Are we providing clear feedback?"
   - "Does this create a good user journey?"

3. **For Technical Safety:**
   - "What could go wrong here?"
   - "Are we properly validating inputs?"
   - "Is this change backward compatible?"

