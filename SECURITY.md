# Covve Bug Bounty Program

## Overview
**Last updated on 2024-03-01**

## Objective
Covve takes the security of its users, employees, and technology very seriously. We greatly value the support of security experts around the world in helping us identify and eliminate any weaknesses. To recognize these efforts and the key role security researchers play in keeping Covve secure, we offer bounties for reporting certain qualifying security vulnerabilities. Please make sure you review and understand the program policy before submitting a report.

If you think you have found a security flaw, we welcome the chance to work with you – and reward you – to resolve the issue.

## Payout Scheme
For vulnerabilities eligible for a reward, the bounty will be rewarded upon triage and validation by the Covve security team. We will keep you informed on the progress to resolve your report.

| Severity Level | Description                                                         | Reward Range       |
| -------------- | ------------------------------------------------------------------- | ------------------ |
| **Low**        | Minor issues that impact user data security or access control       | $50 - $150         |
| **Medium**     | Issues that could potentially lead to unauthorized data access with limited impact | $150 - $250 |
| **High**       | Vulnerabilities that allow unauthorized access to multi-user data or major service disruption | $250 - $500 |
| **Critical**   | Flaws that enable widespread data breach or complete system compromise | >$1000*         |

*Note: The maximum reward for critical vulnerabilities is at the discretion of Covve and may be awarded based on the impact and exploitability of the vulnerability.*

## Scope

### In Scope
1. **Covve API and Infrastructure:**
   - All security vulnerabilities related to our backend services and data storage.
2. **Covve Mobile Applications (pCRM and Business Card Scanner):**
   - Security issues related to data protection and access control.

### Out of Scope
1. **Local App Hacking:**
   - Issues that require physical access to the mobile device or user credentials.
2. **Third-party services not managed by Covve.**

## Reporting Guidelines
1. **Provide Detailed Reports:** Include a detailed description of the vulnerability, steps to reproduce, and potential impact. If the report is not detailed enough to reproduce the issue, it will not be eligible for a reward.
2. **Submit Proof of Concept:** Provide a clear proof of concept to demonstrate the exploit.
3. **Respect User Privacy:** Do not access or modify user data without explicit consent. Avoid disruptions to the service.
4. **Use Safe Testing Methods:** Test vulnerabilities only in your own accounts or test environments.
5. **One Vulnerability per Report:** Submit one vulnerability per report unless you need to chain vulnerabilities to provide impact.
6. **First Reporter:** Only the first report of a vulnerability will be eligible for a reward if it can be fully reproduced.
7. **Underlying Issues:** Multiple vulnerabilities caused by one underlying issue will be awarded one bounty.

## Prohibited Actions
- Physical attacks against Covve offices and data centers.
- Any vulnerability obtained through the compromise of a Covve employee or contractor, or Covve user: if you need to test a vulnerability, create another account; don’t take someone else’s.
- Any vulnerability found through the use of a botnet, compromised site, or a DDoS Cannon (any tool that generates a significant volume of traffic).
- Disrupting or negatively impacting Covve users, e.g. accessing or modifying Covve users' data or denying users access to Covve services.

## How to Report
- Submit vulnerability reports to [security@covve.com](mailto:security@covve.com).
- Include "Bug Bounty Submission" in the subject line.
- Attach all necessary details, screenshots, and proof of concept.

## Response Process
1. **Acknowledgement:** We will acknowledge the receipt of your report within 48 hours.
2. **Assessment:** Our security team will assess the report and determine the severity level.
3. **Reward:** Upon verification, eligible rewards will be processed within 30 days.

## Responsible Disclosure and Privacy Policy
- **Non-Disclosure:** Any information regarding vulnerabilities should not be published or shared publicly. Bug bounties and the details of reported vulnerabilities must remain private and confidential.
- **Disclosure Timeline:** Do not disclose vulnerabilities before they are fixed AND you have received explicit permission from Covve.
- **Privacy Assurance:** Covve commits to not sharing personal details of researchers without their consent.

## Legal
By participating in Covve’s Bug Bounty Program, you agree to comply with all applicable laws and regulations. You also agree that you are participating in an ethical manner, without causing harm to Covve, our users, or our infrastructure.

This policy helps Covve protect user data and improve service security by leveraging the expertise of the security community. For any questions or clarifications, please contact us at [security@covve.com](mailto:security@covve.com).
