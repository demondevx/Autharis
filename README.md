# Autharis — Discord Security Platform

Autharis is an enterprise-grade security platform designed to protect Discord communities through intelligent access control, threat detection, and automated enforcement.

## Why Autharis Exists

Discord communities face critical threats every day:
- Compromised admin accounts nuking servers.
- Rogue moderators abusing permissions.
- Silent permission creep leaving servers vulnerable.
- Delayed incident response due to lack of visibility.

Autharis solves these problems by enforcing a **Zero Trust** architecture. No one holds permanent power. Every high-risk action is authenticated, logged, and temporary.

## Core Protection Systems

### 1. Elevation System
Administrative powers are not permanently active. They must be elevated securely for a specific duration.

#### For Server Owners
- **Total Control:** You define exactly who can elevate and for how long.
- **Audit Visibility:** Every single elevated action is logged and searchable.
- **Protected Actions:** Critical changes require Multi-Factor Authentication (MFA).

#### For Admins
- **Temporary Access:** Request privileges only when you need them.
- **Accountability:** Your actions are transparent, building trust with the owner.

#### For Moderators
- **Controlled Permissions:** specific roles can be granted for limited times.
- **Reduced Risk:** If your account is compromised, the attacker cannot access admin tools without your 2FA.

#### For Community Members
- **Safer Environment:** A community protected from rogue nuking and abuse.

### 2. Honeypot Protection
Autharis automatically detects malicious behavior and removes threats before damage occurs. Decoy channels trap automated raids and unauthorized users, instantly banning them and logging the incident.

### 3. Security Logging & Audit Trail
Every security-critical event is recorded in an immutable audit trail.
- **Security Events:** Elevation requests, grants, denials, and revocations.
- **Incident Investigation:** Trace exactly who did what, when, and why.
- **Traceable Actions:** Correlation IDs link every action to a specific user session.

### 4. Social & Onboarding (New)
Autharis helps you manage your community presence:
- **Join/Leave Logging:** detailed logs of bot server membership changes sent to your support server.
- **Owner Welcome:** Automated, professional DMs to new server owners with quick-start buttons.
- **Interactive Help:** A rich `/help` command to guide users through features.

## Command Guide

| Command | Purpose | Who Can Use |
| :--- | :--- | :--- |
| `/elevate` | Securely activate administrative privileges. | Authorized Staff |
| `/elevate-config` | Configure roles, durations, and channels. | Server Owner |
| `/elevate-register` | Set up your personal 2FA authenticator. | Any Staff |
| `/elevate-reset` | Reset your authenticator using a backup code. | Any Staff |
| `/elevate-trust` | Managed trusted user lists. | Server Owner |
| `/honeypot-setup` | Deploy a decoy channel to trap attackers. | Server Admin |
| `/help` | Show available commands and guides. | Everyone |

## Privacy-First Design

Autharis is built on a privacy-first foundation.
- **Minimal Data Collection:** We store only what is strictly necessary for security auditing.
- **Security-Focused Storage:** Sensitive credentials are encrypted at rest.
- **No Data Selling:** Your community data belongs to you. We do not sell or trade user data.

## Getting Started

### 1. Invite Autharis
[Invite Autharis to Your Server](https://discord.com/oauth2/authorize?client_id=1470837307195265154&permissions=8&scope=bot%20applications.commands)

### 2. Recommended Setup Flow
1.  **Configure Elevation:** Use `/elevate-config` to set up your admin role and log channels.
2.  **Enable Honeypot:** Use `/honeypot-setup` to protect against raids.
3.  **Review Logs:** Verify that security events are appearing in your designated channels.

## Who Should Use Autharis?

- **Growing Communities** that need professional moderation tools.
- **Serious Moderation Teams** requiring accountability and audit trails.
- **High-Value Servers** protecting intellectual property or brand reputation.
- **Creator Communities** where safety is paramount.

## Support

For inquiries, assistance, or to report a security issue, please contact:
**support@demondev.org**

## Status

**Platform Status: Production Hardening Phase**

Autharis is actively evolving as we continue strengthening protections and expanding capabilities.
