# Evidence Checklist

Use this checklist before describing the project as complete.

- [ ] Sanitized tenant overview
- [ ] Persona and access matrix
- [ ] Group and role inventory
- [ ] Conditional Access policy export or screenshots
- [ ] What If and sign-in test results
- [ ] PIM activation evidence
- [ ] Lifecycle test results
- [ ] Rollback record and lessons learned

## Evidence Quality Standard

Each evidence item should include:

- **Purpose:** What requirement or test it supports
- **Date:** When it was produced
- **Environment:** Lab scope and relevant assumptions
- **Expected result:** What should happen
- **Actual result:** What happened
- **Interpretation:** Why the result matters
- **Sanitization:** Confirmation that sensitive values were removed

## Final Review

- [ ] No credentials, secrets, personal information, PHI, or tenant-specific identifiers are exposed
- [ ] Screenshots are readable and cropped to the relevant area
- [ ] Commands and configurations are provided as text when practical
- [ ] Failed tests include root cause and corrective action
- [ ] All README claims are supported by linked artifacts
