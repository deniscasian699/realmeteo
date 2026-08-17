<div align="center">

# 🔐 Security Policy — RealMeteo

</div>

---

## Supported Versions

| Version | Supported |
|---|:---:|
| Latest (Google Play) | ✅ Active |
| Previous versions | ❌ No support |

Always use the latest version of RealMeteo available on Google Play to
ensure you have the most recent security fixes and improvements.

---

## Reporting a Vulnerability

If you discover a security vulnerability in RealMeteo, please report it
**responsibly** and **privately:**

> ⚠️ **Do not open a public GitHub issue for security vulnerabilities.**
> This could expose users before a fix is available.

### How to Report

1. Send an email to **[support@deniscasian.com](mailto:support@deniscasian.com)**
   with the subject line: `[SECURITY] RealMeteo Vulnerability Report`
2. Include in your report:
   - A clear description of the vulnerability
   - Steps to reproduce the issue
   - Potential impact assessment
   - Your suggested fix (if any)
   - Your Android version and RealMeteo version

### Response Timeline

| Step | Timeline |
|---|---|
| Acknowledgement | Within 72 hours |
| Assessment | Within 7 days |
| Fix release | Depends on severity |

We appreciate responsible disclosure and will credit researchers who help
keep RealMeteo secure (with their permission).

---

## Scope

| In Scope ✅ | Out of Scope ❌ |
|---|---|
| RealMeteo Android app | Open-Meteo API |
| In-app purchase flows | BigDataCloud API |
| Widget security | Google Play / RevenueCat |
| Notification handling | Physical device attacks |

---

## Known Security Practices

- ✅ All network requests use **HTTPS** encryption
- ✅ No plaintext credentials stored
- ✅ No advertising or analytics SDKs
- ✅ All preferences stored locally using Android SharedPreferences
- ✅ Purchase verification handled by RevenueCat (server-side)

---

*Thank you for helping keep RealMeteo and its users safe. 🌤️*
