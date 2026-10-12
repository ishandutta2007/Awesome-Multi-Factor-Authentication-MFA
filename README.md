# Awesome-Multi-Factor-Authentication-MFA

# Top Multi-Factor Authentication (MFA) Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Adaptive Authentication, Token Verification & Passwordless Identity Assurance*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Multi-Factor Authentication (MFA) Tools**. These tools add additional verification factors — TOTP codes, push approvals, hardware security keys, biometrics, and passkeys — to strengthen login security, enforce adaptive access policies, and protect identities across cloud, on-premise, and hybrid environments.

**Examples** include Salesforce Authenticator, Cisco Duo, Google Authenticator, Microsoft Entra ID MFA, Okta Verify, RSA SecurID, Ping Identity, Authy, Yubico, and OneLogin Protect (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom authentication flows, and transparent identity verification — ideal for organizations building data-sovereign identity infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Authenticator](https://www.salesforce.com/)**  
  Mobile app providing push-based, TOTP, and location-based multi-factor authentication for Salesforce users.

- **[Cisco Duo](https://duo.com/)**  
  Cloud-based MFA and access security platform with push, SMS, phone callback, hardware tokens, and device trust.

- **[Google Authenticator](https://security.googleblog.com/)**  
  Widely used mobile app generating TOTP and HOTP codes for two-factor authentication across services.

- **[Microsoft Entra ID MFA](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)**  
  Azure AD's MFA service with authenticator app, SMS, phone call, FIDO2 keys, and conditional access policies.

- **[Okta Verify](https://www.okta.com/)**  
  MFA app with push notifications, TOTP, biometrics, and device assurance for Okta-managed identities.

- **[RSA SecurID](https://www.rsa.com/en-us/products/rsa-securid-suite)**  
  Enterprise MFA platform with hardware tokens, software tokens, and risk-based authentication.

- **[Ping Identity](https://www.pingidentity.com/)**  
  Identity security platform with MFA, adaptive authentication, and passwordless capabilities.

- **[Authy](https://authy.com/)**  
  Twilio's multi-device TOTP authenticator with encrypted backups and push-based approvals.

- **[Yubico](https://www.yubico.com/)**  
  Hardware security key provider with FIDO2/WebAuthn, U2F, smart card, and OTP capabilities.

- **[OneLogin Protect](https://www.onelogin.com/)**  
  MFA solution within OneLogin with push notifications, TOTP, and adaptive authentication policies.

## Open-Source GitHub Projects

- **[Keycloak](https://github.com/keycloak/keycloak)**  
  Leading open-source identity and access management platform with built-in MFA supporting TOTP, WebAuthn, and recovery codes. Apache 2.0 licensed.

- **[Authelia](https://github.com/authelia/authelia)**  
  Open-source authentication and authorization server providing 2FA/MFA with TOTP, WebAuthn, Duo, and mobile push. Apache 2.0 licensed.

- **[Authentik](https://github.com/goauthentik/authentik)**  
  Open-source identity provider with MFA supporting TOTP, WebAuthn, Duo, SMS, and static tokens. MIT licensed.

- **[Zitadel](https://github.com/zitadel/zitadel)**  
  Open-source identity infrastructure with MFA including TOTP, U2F, WebAuthn, and OTP via email/SMS. Apache 2.0 licensed.

- **[Ory Kratos](https://github.com/ory/kratos)**  
  Open-source identity and user management server with MFA supporting TOTP and WebAuthn. Apache 2.0 licensed.

- **[FusionAuth](https://github.com/FusionAuth/fusionauth-issues)**  
  Open-source identity platform with MFA supporting TOTP, SMS, email, and WebAuthn. Apache 2.0 licensed.

- **[Gluu Server](https://github.com/GluuFederation/gluu-server)**  
  Open-source identity and access management with MFA, FIDO2, OTP, and adaptive authentication. MIT licensed.

- **[WSO2 Identity Server](https://github.com/wso2/product-is)**  
  Open-source IAM with MFA supporting TOTP, FIDO2, email OTP, and adaptive authentication. Apache 2.0 licensed.

- **[PrivacyIDEA](https://github.com/privacyidea/privacyidea)**  
  Open-source multi-factor authentication server supporting TOTP, HOTP, WebAuthn, Yubikey, SMS, and push tokens. AGPL-3.0 licensed.

- **[LinOTP](https://github.com/LinOTP/LinOTP)**  
  Open-source OTP and MFA server with support for TOTP, HOTP, Yubikey, SMS, and push notifications. AGPL-3.0 licensed.

- **[SuperTokens](https://github.com/supertokens/supertokens-core)**  
  Open-source authentication solution with MFA including TOTP and email/SMS OTP. Apache 2.0 licensed.

- **[Hanko](https://github.com/teamhanko/hanko)**  
  Open-source passwordless and MFA authentication server with WebAuthn, passkeys, and TOTP. AGPL-3.0 licensed.

- **[Ory Oathkeeper](https://github.com/ory/oathkeeper)**  
  Open-source identity and access proxy with MFA enforcement for zero-trust architectures. Apache 2.0 licensed.

- **[Aegis Authenticator](https://github.com/beemdevelopment/Aegis)**  
  Open-source Android TOTP/HOTP authenticator app with encrypted vault and biometric protection. GPL-3.0 licensed.

- **[FreeOTP](https://github.com/freeotp/freeotp-android)**  
  Open-source TOTP/HOTP authenticator app from Red Hat for Android and iOS. Apache 2.0 licensed.

- **[andOTP](https://github.com/andOTP/andOTP)**  
  Open-source Android authenticator app supporting TOTP, HOTP, and Steam tokens with encrypted backups. MIT licensed.

- **[OTPClient](https://github.com/paolostivanin/OTPClient)**  
  Open-source TOTP/HOTP authenticator for Linux desktop with encrypted storage. GPL-3.0 licensed.

- **[Raivo OTP](https://github.com/raivo-otp/ios-application)**  
  Open-source iOS TOTP authenticator with iCloud sync and biometric protection. MIT licensed.

- **[2FAS](https://github.com/twofas/2fas-ios)**  
  Open-source cross-platform authenticator with browser extensions and encrypted backup. GPL-3.0 licensed.

- **[Yubico Authenticator](https://github.com/Yubico/yubioath-flutter)**  
  Open-source desktop and mobile app for YubiKey-based TOTP generation. Apache 2.0 licensed.

- **[OpenOTP](https://github.com/RCDevs/OpenOTP)**  
  Open-source OTP and MFA server supporting TOTP, HOTP, Yubikey, and push authentication. GPL-3.0 licensed.

- **[Step CA](https://github.com/smallstep/certificates)**  
  Open-source certificate authority with ACME and MFA integration for device and user authentication. Apache 2.0 licensed.

### Additional Strong Open-Source Options

- **[OPA (Open Policy Agent)](https://github.com/open-policy-agent/opa)** — Policy engine for adaptive MFA enforcement based on context and risk.
- **[OpenFGA](https://github.com/openfga/openfga)** — Fine-grained authorization with MFA step-up requirements for sensitive actions.
- **[SpiceDB](https://github.com/authzed/spicedb)** — Zanzibar-inspired permissions with conditional MFA enforcement.
- **[Cerbos](https://github.com/cerbos/cerbos)** — Open-source authorization layer with policy-driven MFA triggers.
- **WebAuthn Libraries** — `webauthn4j`, `py_webauthn`, `SimpleWebAuthn` for implementing passkeys and hardware key support.
- **TOTP Libraries** — `otplib`, `pyotp`, `speakeasy` for generating and validating time-based codes.
- **Push Authentication** — `Duo`, `Okta`, and `Auth0` SDKs for implementing push-based MFA flows.
- **Identity Providers** — `Keycloak`, `Authentik`, `Zitadel`, and `Ory` for complete IAM with MFA capabilities.

**Frameworks for building custom systems**: Combine **Keycloak** or **Authentik** for IAM, **PrivacyIDEA** for token management, **Authelia** for reverse-proxy MFA, **OPA** for adaptive policy, and **PostgreSQL + Grafana** for authentication analytics to build a complete self-hosted MFA stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- MFA tools must comply with data protection regulations (GDPR, CCPA), industry standards (NIST 800-63B, FIDO2, SOC 2), and accessibility requirements.
- Self-hosted open-source solutions require proper security hardening, key management, and high-availability design.

---

**Made for identity engineers, security architects, IT administrators, and developers building passwordless and multi-factor authentication systems.**  
Let's make multi-factor authentication more open, transparent, and developer-friendly.
