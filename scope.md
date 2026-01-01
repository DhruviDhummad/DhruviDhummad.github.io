# Scope of Assessment

## In Scope
- Target application: app.talentin.ai
- Cloud environment supporting the application (AWS)
- Authenticated and unauthenticated user flows
- Passive and low-impact security testing

### Assessment Areas
- HTTP security headers and configuration
- Authentication and session handling
- Basic input validation (non-destructive)
- Cloud activity monitoring using AWS GuardDuty

## Out of Scope
- Denial of Service (DoS) testing
- Brute-force attacks
- Data destruction or modification
- Aggressive automated exploitation
- Third-party services not managed by the organization

## Rules of Engagement
- Testing conducted with authorization
- No disruption to production services
- All findings documented with evidence
- Sensitive data redacted from reports
