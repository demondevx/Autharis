# Privacy Policy

**Last Updated:** February 13, 2026

## 1. Introduction
This Privacy Policy describes how Autharis ("we," "us," or "our") collects, uses, and discloses information when you use our Discord security bot application (the "Service").

Autharis is operated by DemonDev.
For privacy-related inquiries, contact: support@demondev.org

**Autharis is a security-focused application.** We prioritize your privacy and data security. Ideally, we operate on a Zero Trust model where data retention is minimized to what is strictly necessary for security auditing and functionality.

## 2. Legal Basis for Processing (GDPR)
We process data under the lawful basis of Legitimate Interest, as the information collected is strictly necessary to provide server security, authentication, and audit functionality.

## 3. Information We Collect
We collect the following types of information:

### A. Automatically Collected Information
- **Discord IDs:** User IDs, Guild IDs, Channel IDs, Role IDs, and Message IDs involved in security events.
- **Security Event Metadata:** Timestamps, action types (e.g., elevation granted, role revoked), and correlation IDs for audit trails.
- **Audit Logs:** Records of high-privilege actions performed through the Service.
- **Configuration Data:** Settings configured by server administrators (e.g., trusted roles, log channels).

### B. Information You Provide
- **TOTP Configuration:** Encrypted secrets for Time-based One-Time Password (TOTP) generation.
- **Elevation Reasons:** Text provided when requesting elevated privileges.

## 4. Information We DO NOT Collect
We strictly **DO NOT** collect or store:
- **Message Content:** We do not store message content. Honeypot enforcement may process messages in real time to detect violations, but message content is not retained.
- **Passwords:** We never ask for or store your Discord account password.
- **Private Direct Messages (DMs):** We do not access your DMs unless you interact directly with the bot for authentication purposes.

## 5. How We Use Your Information
We use the collected information for the following purposes:
- **Security Auditing:** To provide server owners with a comprehensive audit trail of elevated actions.
- **Authentication:** To verify your identity using Multi-Factor Authentication (MFA/TOTP).
- **Service Functionality:** To manage permissions, assign roles, and enforce security policies.
- **Incident Response:** To detect and alert on suspicious activities or security anomalies.

## 6. Data Retention
- **Audit Logs:** Retained for 7 days in our high-speed cache (Redis) for immediate retrieval, and may be persisted in server logs indefinitely based on server administrator configuration.
- **Session Data:** Retained only for the duration of the active elevation session (max 15 minutes).
- **TOTP Secrets:** Stored using industry-standard AES-256 encryption.

## 7. Data Sharing
We do not sell, trade, or otherwise transfer your personally identifiable information to outside parties. Data is only shared with:
- **Server Owners:** Audit logs regarding actions in their specific guilds.
- **Discord:** As required for the Service to function via the Discord API.
- **Legal Requirements:** If required by law or to protect our rights.

## 8. Your Data Rights
Users may request deletion of their stored authentication data by contacting support@demondev.org.
Server administrators may remove the bot from their server at any time, which deletes configuration data associated with that server.

## 9. Configuration & Control
Server administrators have full control over the Service's configuration within their guild. Users can reset their own authenticator data using the designated commands, which irrevocably deletes their stored secrets.

## 10. Contact Us
If you have questions about this Privacy Policy, please contact the developer via the official support channels.
