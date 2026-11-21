# Password Policy

**Document ID:** ISP-003  
**Version:** 1.0  
**Effective Date:** [Date]  
**Owner:** [CISO]

## 1. Purpose

To establish requirements for the creation, use and management of passwords and other authentication secrets in order to protect against unauthorized access.

## 2. Scope

All user accounts, service accounts and authentication mechanisms used within **[Company Name]** systems.

## 3. Policy Statements

3.1 Passwords must meet the following minimum requirements:
- Minimum length: **12 characters** (preferably 14+)
- Must contain a mix of uppercase, lowercase, numbers and special characters **or** be a strong passphrase
- Must not contain the username or common dictionary words in an easily guessable form

3.2 Passwords must not be reused across different systems or previous passwords (history of at least 5–10).

3.3 Multi-factor authentication (MFA) is mandatory for:
- Remote access
- Privileged accounts
- Access to systems processing sensitive or critical data

3.4 Passwords must never be shared, written down in unprotected form, or stored in clear text.

3.5 Password changes must be forced periodically only when there is evidence of compromise or for privileged accounts according to risk assessment. Forced periodic changes for regular users are discouraged if MFA and strong passwords are in place (aligned with modern NIST guidance).

3.6 Service accounts and API keys must use long, randomly generated secrets and be rotated according to a defined schedule or upon compromise.

3.7 Default and vendor passwords must be changed before systems are put into production.

## 4. Related Documents

- Access Control Policy
- Information Security Policy
