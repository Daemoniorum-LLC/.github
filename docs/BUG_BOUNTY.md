# Daemoniorum, LLC Bug Bounty Program

Thank you for helping keep Daemoniorum and our users safe. We value the work of security researchers and encourage responsible disclosure of vulnerabilities.

## Scope

### In Scope

The following products and services are eligible for our bug bounty program:

**Developer Tools & IDEs**
- Wraith IDE
- Paimon (VS Code & IntelliJ extensions)
- Sigil programming language and toolchain

**Frameworks & Platforms**
- Persona Framework SDK
- Bael administrative interfaces
- Archon CMS/e-commerce platform
- Aether game engine

**Industry Solutions**
- Lilith (HR management)
- Codex (Legal practice management)
- Vulcan (Manufacturing ERP)
- Orpheus (Music platform)
- Dagon (Agricultural management)
- Umbra (Art gallery management)

**Infrastructure**
- *.daemoniorum.com
- Public API endpoints
- Authentication systems
- Cloud infrastructure components

### Out of Scope

- Third-party services and integrations
- Social engineering attacks against employees
- Physical security
- Denial of Service (DoS/DDoS) attacks
- Spam or social engineering techniques
- Issues in third-party dependencies (report these upstream)
- Recently disclosed zero-days (< 30 days)

## Vulnerability Classifications

### Critical (Up to $10,000)
- Remote code execution (RCE)
- SQL injection with data exfiltration
- Authentication bypass affecting all users
- Privilege escalation to admin/root
- Cryptographic key exposure
- Access to production infrastructure

### High ($2,500 - $5,000)
- Stored XSS in authenticated areas
- IDOR with access to sensitive data
- Server-Side Request Forgery (SSRF)
- Significant information disclosure
- Account takeover vulnerabilities
- Insecure direct object references

### Medium ($500 - $2,500)
- Reflected XSS
- CSRF on sensitive actions
- Session management issues
- Rate limiting bypass
- Information disclosure (non-sensitive)
- Subdomain takeover

### Low ($100 - $500)
- Self-XSS
- Missing security headers
- Verbose error messages
- Minor information leakage
- Best practice violations

## Rules of Engagement

1. **Do Not:**
   - Access, modify, or delete data belonging to other users
   - Execute denial of service attacks
   - Perform physical attacks or social engineering
   - Use automated scanning tools that generate excessive traffic
   - Disclose vulnerabilities publicly before they are fixed
   - Test on production systems without prior approval for destructive tests

2. **Do:**
   - Create test accounts for your research when possible
   - Stop testing and report immediately upon discovering sensitive data
   - Use the minimum access necessary to demonstrate the vulnerability
   - Provide detailed reproduction steps
   - Delete any test data you create

## Reporting Process

### How to Report

1. **Email:** security@daemoniorum.com
2. **Subject Line Format:** `[BUG BOUNTY] [Severity] - Brief Description`
3. **Encrypted Reports:** PGP key available at https://www.daemoniorum.com/.well-known/security.txt

### Report Contents

Please include:

- **Summary:** Clear description of the vulnerability
- **Affected Product/Service:** Which application or system is affected
- **Severity Assessment:** Your assessment of the impact
- **Reproduction Steps:** Detailed step-by-step instructions
- **Proof of Concept:** Screenshots, videos, or code demonstrating the issue
- **Impact Analysis:** What an attacker could achieve
- **Suggested Fix:** Optional but appreciated
- **Your Contact Information:** For follow-up communication

### Response Timeline

| Stage | Timeline |
|-------|----------|
| Initial Response | Within 48 hours |
| Triage & Severity Assessment | Within 5 business days |
| Remediation Timeline | Based on severity |
| Bounty Payment | Within 30 days of fix verification |

## Safe Harbor

Daemoniorum, LLC pledges the following to security researchers who follow this policy:

- We will not pursue legal action against researchers who act in good faith
- We will work with you to understand and resolve issues quickly
- We will recognize your contribution (with your permission) in our security acknowledgments
- We will maintain confidentiality regarding your report

If legal action is initiated by a third party against you for activities conducted under this policy, we will make it known that your actions were in compliance with this policy.

## Eligibility

To be eligible for a bounty:

- You must be the first to report the vulnerability
- You must not be a current employee or contractor of Daemoniorum, LLC
- You must not reside in a country under U.S. sanctions
- You must comply with all rules in this document
- The vulnerability must be in scope and not previously known

## Recognition

With your permission, we will acknowledge your contribution in:

- Our Security Hall of Fame
- Release notes when the fix is deployed
- Social media recognition (optional)

## Contact

- **Security Reports:** security@daemoniorum.com
- **General Questions:** bounty-questions@daemoniorum.com
- **Website:** https://www.daemoniorum.com/security

---

## Changelog

| Date | Version | Changes |
|------|---------|---------|
| 2025-12-18 | 1.0 | Initial bug bounty program |

---

<sub>This policy is subject to change. Please check back regularly for updates.</sub>

<sub>Daemoniorum, LLC | Roy, Utah | www.daemoniorum.com</sub>
