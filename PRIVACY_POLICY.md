<div align="center">

# 🌤️ RealMeteo — Privacy Policy

**Last updated: July 29, 2026 · Effective immediately**

[![App](https://img.shields.io/badge/RealMeteo-Download-brightgreen?style=for-the-badge&logo=google-play)](https://go.deniscasian.com/realmeteo)
[![Privacy](https://img.shields.io/badge/No%20Ads-Zero%20Tracking-blue?style=for-the-badge)](https://go.deniscasian.com/realmeteo)
[![GDPR](https://img.shields.io/badge/GDPR-Compliant-green?style=for-the-badge)](https://go.deniscasian.com/realmeteo)

</div>

---

> **Related:** [Terms of Use](./TERMS_OF_SERVICE.md) · [Back to README](./README.md)

---

This Privacy Policy explains how RealMeteo ("we", "us", or "our") collects,
uses, and protects your information when you use our Android application.
We are committed to protecting your privacy. **We do not sell your personal
data to anyone.**

---

## 🛡️ No Third-Party Advertising

RealMeteo contains **no third-party advertising.**

We do not display ads, we do not use advertising SDKs, and we do not access
your Android Advertising ID. The app is funded entirely by optional Supporter
contributions and Premium subscriptions. There is **no advertising profiling
of any kind.**

---

## 1. 📋 Information We Collect

### Location Data

With your explicit permission, the app accesses your device's GPS or network
location solely to provide accurate local weather forecasts. Your coordinates
are sent directly to the **Open-Meteo** weather API and, when the device's
built-in geocoder is unavailable, to the **BigDataCloud** reverse-geocoding
API to determine your city name.

> Your location is **never stored on our servers**, because we do not operate any.

### Purchase Information

When you make a purchase, Google Play processes the transaction and
**RevenueCat** records the resulting entitlement. We receive an anonymous
purchase identifier and the status of your subscription.

> We **never** receive your name, email address, or payment card details.

### Usage Data

We do **not** collect analytics or usage data. The app contains:

- ❌ No analytics SDK
- ❌ No crash-reporting SDK
- ❌ No advertising SDK

### Advertising Identifiers

**None.** RealMeteo does not request, read, or transmit the Android
Advertising ID.

### User Preferences

Settings such as your preferred language, temperature unit, favorite cities,
widget configuration, and notification preferences are **stored locally on
your device only** and are never transmitted to us.

---

## 2. ⚙️ How We Use Your Information

We use the information collected for the following purposes:

- To fetch and display accurate weather forecasts for your location
- To determine the name of your city for display purposes
- To process purchases and unlock the features you paid for
- To send morning weather notifications *(only if you enable this feature)*
- To send severe weather alerts to Premium users *(only if you enable this)*
- To remember your preferences and favorite cities locally on your device
- To update home screen widgets with current weather data

> 📌 We do not use your data for profiling, we do not sell it, and we do not
> share it with any party other than those described in this policy.

---

## 2.1 ⚖️ Legal Basis for Processing (GDPR)

If you are located in the European Economic Area (EEA), we process your
personal data based on the following legal grounds:

| Legal Basis | Purpose |
|---|---|
| **Consent** *(Art. 6(1)(a))* | Accessing your device location to provide local forecasts. You can withdraw this consent at any time via Android Settings. |
| **Contract Performance** *(Art. 6(1)(b))* | Providing the weather forecasting service you requested, and delivering Premium or Supporter features you purchased. |
| **Legitimate Interest** *(Art. 6(1)(f))* | Caching weather data locally so the app remains usable offline. |

> 📌 Because RealMeteo displays no advertising, we do not rely on consent for
> advertising purposes and there is no advertising profile associated with you.

---

## 3. 🔗 Third-Party Services

RealMeteo uses the following third-party services. Each has its own Privacy
Policy which we encourage you to review:

| Service | What it receives | Purpose |
|---|---|---|
| **Open-Meteo** | Your coordinates | Weather forecast data. No account, no tracking, no data retention. |
| **Open-Meteo Geocoding** | City name you type | City search. No personal data. |
| **BigDataCloud** | Your coordinates | Reverse geocoding — used only as a fallback when the device's own geocoder fails. |
| **Google Play Billing** | Purchase transaction | Processes payments. We never see your payment details. |
| **RevenueCat** | Anonymous app user ID, purchase receipts | Manages subscription status and restores purchases across devices. |

**Policy links:**
[Open-Meteo](https://open-meteo.com/en/terms) ·
[BigDataCloud](https://www.bigdatacloud.com/privacy-policy) ·
[RevenueCat](https://www.revenuecat.com/privacy) ·
[Google](https://policies.google.com/privacy)

> 📌 RealMeteo does **not** include Google AdMob, Firebase Analytics,
> Google Analytics, or any other advertising or analytics SDK.

---

## 4. 💳 Purchases & Subscriptions

RealMeteo is free to use. All weather features work without payment.
We offer optional purchases to support development:

| Product | Type | Description |
|---|:---:|---|
| ❤️ **Supporter** | One-time | A badge and the removal of in-app support messages |
| ❤️ **Monthly Supporter** | Subscription | A monthly badge and exclusive app icons |
| 👑 **Premium** | Subscription | 14-day forecast, charts, weather alerts, city comparison, customizable widget |
| 💎 **Lifetime Premium** | One-time | All Premium features permanently |

### How Payments Are Processed

All payments are handled by **Google Play Billing.** We never receive or store
your payment card details. Prices are provided directly by Google Play in your
local currency.

### Subscription Management

We use **RevenueCat** to verify and synchronize your purchase status across
devices. RevenueCat assigns your installation an anonymous identifier that is
not linked to your name or email address.

### Cancellation and Refunds

Subscriptions renew automatically until cancelled. You can cancel at any time
through **Google Play → Subscriptions.** Cancelling stops future charges;
access continues until the end of the paid period. Refunds are handled by
Google Play according to their refund policy.

> 📌 Purchasing Lifetime Premium does **not** automatically cancel an existing
> monthly subscription. Google Play does not permit apps to cancel subscriptions
> on your behalf. The app will prompt you and link you to Google Play so you
> can cancel it yourself.

---

## 5. 🔐 App Permissions

| Permission | Purpose | Required? |
|---|---|:---:|
| `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION` | Detect your location for weather forecasts | ❌ Optional |
| `INTERNET` | Fetch weather data | ✅ Yes |
| `POST_NOTIFICATIONS` | Send morning weather notifications and alerts *(only if enabled)* | ❌ Optional |
| `SCHEDULE_EXACT_ALARM` | Deliver the morning notification at the exact time you chose | ❌ Optional |
| `RECEIVE_BOOT_COMPLETED` | Reschedule notifications after device restart | ❌ Optional |
| `WAKE_LOCK` | Keep device awake briefly while fetching weather for a scheduled notification | ❌ Optional |
| `com.android.vending.BILLING` | Process in-app purchases through Google Play | ❌ Optional |

> 📌 Location permission is **never required.** If you deny it, you can still
> use the app by manually searching for any city.

---

## 6. 🛡️ Data Storage & Security

All user preferences — language, units, favorite cities, widget configuration,
notification settings — are stored **locally on your device** using Android
SharedPreferences. This data **never leaves your device.**

Weather data is cached locally on your device for offline use and is
automatically overwritten on each successful update.

> We do not operate any servers, databases, or backend infrastructure that
> stores your personal data.

All network requests use **HTTPS encryption.**

### Data Retention

| Data | Retention |
|---|---|
| Cached weather data | Automatically overwritten with each update (every 15–60 minutes) |
| User preferences | Stored until you uninstall the app or clear app data |
| Purchase records | Retained by Google Play and RevenueCat per their own policies |

---

## 7. 👶 Children's Privacy

RealMeteo is not directed at children under the age of **13** (or **16** in
the European Economic Area). We do not knowingly collect personal information
from children.

If you believe a child under the applicable age has provided us with personal
information, please contact us and we will take steps to delete such information.

> Because the app contains no advertising and no analytics, there is no
> behavioural tracking of any user, including children.

---

## 8. ⚖️ Your Rights

Depending on your location, you may have the following rights regarding your data:

| Right | Description |
|---|---|
| **Access** | Request information about what data is held about you |
| **Deletion** | Request deletion of your data *(most data exists only on your device and is removed by uninstalling the app)* |
| **Revoke permissions** | At any time via **Android Settings → Apps → RealMeteo → Permissions** |
| **Portability** | Request a copy of your data in a machine-readable format |
| **Rectification** | Request correction of inaccurate data |

> Since we do not store personal data on our servers, most of these rights can
> be exercised directly on your device. For data held by RevenueCat in
> connection with your purchases, contact us and we will forward your request.

---

## 9. 🌍 International Data Transfers (GDPR)

If you are located in the EEA, United Kingdom, or Switzerland:

| Service | Location | Transfer Mechanism |
|---|---|---|
| **Open-Meteo** | Germany 🇩🇪 | Within EEA — no transfer issue |
| **BigDataCloud** | Australia 🇦🇺 | Fallback geocoding only |
| **RevenueCat** | United States 🇺🇸 | Standard Contractual Clauses |
| **Google** | United States 🇺🇸 | EU–U.S. Data Privacy Framework |

You have the right to lodge a complaint with your local data protection
authority if you believe your rights have been violated. In Romania, this is
the **[ANSPDCP](https://www.dataprotection.ro/).**

> 📌 For EEA users: you can request deletion of your data by contacting us at
> **[support@deniscasian.com](mailto:support@deniscasian.com)**

---

## 10. 🇺🇸 California Privacy Rights (CCPA)

If you are a California resident, you have additional rights under the CCPA:

- **Right to Know** — what personal information we collect and how we use it
- **Right to Delete** — request deletion of your personal information
- **Right to Opt-Out** — opt out of the "sale" or "sharing" of personal information
- **Right to Non-Discrimination** — we will not discriminate against you for
  exercising your rights

> 📌 We do **not** sell or share your personal information as defined under
> the CCPA. RealMeteo contains no advertising and no cross-context
> behavioural tracking.

To exercise these rights, contact us at
**[support@deniscasian.com](mailto:support@deniscasian.com)**

---

## 10.1 🇺🇸 Other U.S. State Privacy Rights

If you are a resident of **Virginia (VCDPA)**, **Colorado (CPA)**,
**Connecticut (CTDPA)**, or **Utah (UCPA)**, you have similar rights,
including:

- **Right to Access** — request information about what personal data we collect
- **Right to Delete** — request deletion of your personal data
- **Right to Opt-Out** — opt out of the sale or sharing of personal data
  *(note: we do not sell your data)*
- **Right to Correct** — request correction of inaccurate personal data

> 📌 Since we do not store personal data on our servers, most of these rights
> can be exercised directly on your device by uninstalling the app or clearing
> app data.

To exercise these rights, contact us at
**[support@deniscasian.com](mailto:support@deniscasian.com)**

---

## 11. 🍪 Cookies & Tracking Technologies

RealMeteo does **not** use cookies, tracking pixels, fingerprinting, or any
similar technology. The app contains no advertising SDK and no analytics SDK,
so there is nothing to opt out of.

> This documentation page may load fonts from Google Fonts, which may log
> your IP address. No cookies are set by this page.

---

## 12. 🔄 Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will
update the "Last updated" date at the top of this page. We encourage you to
review this policy periodically.

Continued use of the app after changes are posted constitutes your acceptance
of the revised policy.

### Change Log

| Date | Changes |
|---|---|
| **July 29, 2026** | Removed all references to Google AdMob and advertising identifiers; RealMeteo no longer contains any advertising SDK. Added RevenueCat and BigDataCloud as data processors. Added a dedicated Purchases section. Updated the permissions list. |

---

## 👤 Developer Information

| | |
|---|---|
| **Developer** | Denis Casian |
| **Location** | Romania 🇷🇴 |
| **Email** | [support@deniscasian.com](mailto:support@deniscasian.com) |
| **Website** | [deniscasian.com](https://deniscasian.com) |
| **Data Protection** | As an independent developer, we are not required to appoint a Data Protection Officer (DPO) under GDPR. However, you can contact us at any time regarding data protection matters. |

---

<div align="center">

**Questions or concerns?**

[![Email](https://img.shields.io/badge/Contact-support@deniscasian.com-blue?style=for-the-badge&logo=gmail)](mailto:support@deniscasian.com)

[Terms of Use](./TERMS_OF_SERVICE.md) · [README](./README.md) · [Download RealMeteo](https://go.deniscasian.com/realmeteo)

*© 2026 RealMeteo. All rights reserved.*

</div>
