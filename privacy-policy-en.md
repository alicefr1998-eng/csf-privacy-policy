# Privacy Policy — Che si fa?

**Last updated:** 6 June 2026
**App version:** 1.0.0

---

## At a glance

- **Che si fa?** is a free app that shows you events and places in the Ligurian Levante (Tigullio, Golfo Paradiso, Val Graveglia, Val d'Aveto, etc.). You use it **anonymously, with no sign-up and no account**.
- **We never ask for your name, email or phone number.**
- Your **saved events, favourites and settings stay on your device** and are never uploaded to any server.
- We use **crash diagnostics** (to keep the app stable) and, **only with your consent**, **anonymous usage analytics** (to understand what works). You can change your mind anytime in settings.
- **Location** is requested only when you tap a feature that needs it (e.g. "events near me" or the map), is processed **on your device**, and is **never sent to or stored on our servers**.
- **We do not sell your data** and we **do not run ads or track you across other apps.**

The full version below explains everything in detail, as required by Regulation (EU) 2016/679 (GDPR).

---

## 1. Data Controller

The controller of your personal data is:

- **Alice Frugone**
- Privacy contact email: **chesifa.app@gmail.com**

For any request regarding your personal data or the exercise of your rights, write to the email address above.

No Data Protection Officer (DPO) has been appointed, as the conditions of Art. 37 GDPR do not apply.

---

## 2. Who this policy is for

This policy describes how we process data of users of the **Che si fa?** mobile application ("the App") on iOS, Android and web. The App is a **read-only** content aggregator: events and places are supplied by an external system and you browse them without being able to edit them.

The App is intended for residents, tourists and outdoor enthusiasts. It is **not intended for children under 13** (see § 12).

---

## 3. What data we process, why, and on what legal basis

We process **only the data strictly necessary** for the App to work. We do not collect direct identifiers (name, surname, email, phone). The table summarises our processing; the following sections add detail.

| # | Data | Purpose | Legal basis (Art. 6 GDPR) | Where it stays | Retention |
|---|---|---|---|---|---|
| A | **Anonymous device identifier** (`device_id`: a random UUID generated on the device) | Tell installations apart for diagnostics and statistics, without identifying you | Diagnostics: legitimate interest (f) · Analytics: consent (a) | On device; shared with Sentry and (only with consent) PostHog | Until you uninstall the App or clear its data |
| B | **Diagnostics & crash data** (device model, OS, app version, screen/route, technical error log, performance data) | Detect and fix errors and crashes; keep the App secure and stable | Legitimate interest (f) | Sentry servers (EU) | Up to ~90 days |
| C | **Anonymous usage analytics** (screens viewed, in-app actions, device type) | Understand how the App is used and improve it | **Consent (a)** | PostHog servers (EU) | Max 12 months, then aggregated/deleted |
| D | **Geolocation** (GPS coordinates) | Show nearby events and places; sort results by distance | Consent, via the OS permission (a) | **On your device only**, in temporary memory | Not retained: discarded when you close the App |
| E | **Device calendar** (writing an event) | Add an event you chose to your calendar | Consent, via the OS permission (a) | **On your device only** | Managed by your calendar |
| F | **Favourites, saved events and settings** | Make your lists and preferences work | Performance of the service (b) / legitimate interest (f) | **On your device only** (local storage) | Until you delete them or uninstall the App |
| G | **Technical connection data** (IP address, request data) sent to providers that deliver content, images, maps and updates | Deliver content and run the App | Legitimate interest / technical necessity (f) | Providers' servers (see § 6) | Per each provider's logs |

**Important notes:**

- The `device_id` (row A) is a random code generated on your device: it **contains no name, is not linked to your real identity** and cannot be traced back to you. It only avoids counting the same installation twice.
- **Usage analytics (row C)** is active **only if you give consent**. Without consent, the App works normally and we send no analytics data.
- **Location (row D)** and **calendar (row E)** are processed **on your device only**: we **do not receive, transmit or store** them on our servers.

### Nature of the provision

Providing this data is **optional**. You can use the App while refusing analytics consent and denying location and calendar permissions: some features (e.g. "events near me", "add to calendar") will be unavailable, but the rest of the App keeps working.

---

## 4. Device permissions

The App requests permissions **only when needed** ("just-in-time"), never at launch:

- **Location (while using the App):** requested when you tap "events near me" or open the map. We use it **only in the foreground**, while the App is open: we **do not track your movements in the background**. Location is used on the device to compute distances and is not sent to us.
- **Calendar:** requested only when you choose "Add to calendar" on an event, to write that event into your calendar. We **do not read** your other calendar entries.

You can **grant or revoke** each permission anytime in your device's OS settings (iOS: Settings › Privacy & Security; Android: Settings › Apps › Che si fa? › Permissions).

---

## 5. Analytics, consent and tracking technologies

To improve the App we use **PostHog**, a product-analytics tool configured **not** to automatically record your screen taps and **not** to collect your IP address (EU region).

In line with the ePrivacy Directive (2002/58/EC) and the guidelines of the Italian Data Protection Authority (**Garante**), because this analytics relies on a device identifier it is enabled **only after you give free and explicit consent** via the in-app banner. Until then, **no analytics data is collected**.

You can **withdraw consent at any time** from the App's Settings/Profile section; from then on we stop collecting usage analytics. Withdrawal does not affect the lawfulness of processing carried out before withdrawal.

The **crash-diagnostics tool (Sentry)** operates on the basis of our **legitimate interest** in keeping the App secure, stable and error-free: it collects technical information about errors, not personal content. You may object to this processing (see § 9).

**We do not use the App for advertising, marketing profiling, or tracking your activity across other apps or websites** (no "tracking" under Apple's App Tracking Transparency).

---

## 6. Recipients of data (processors and providers)

We do not sell or rent your data. To run the service we rely on technology providers acting as **data processors** (Art. 28 GDPR) or, for technical logs, as independent controllers. The main ones are:

| Provider | Role | Data | Data region | Policy |
|---|---|---|---|---|
| **Sentry** (Functional Software, Inc.) | Crash & error diagnostics | Technical error data, `device_id` | EU (Germany) | https://sentry.io/privacy/ |
| **PostHog** (PostHog, Inc.) | Usage analytics (consent only) | Anonymous usage events, `device_id` | EU (Frankfurt) | https://posthog.com/privacy |
| **Supabase** (Supabase, Inc.) | Content database & image storage (read-only) | Technical connection data (IP) | EU (West EU — Ireland) | https://supabase.com/privacy |
| **Expo / EAS** (650 Industries, Inc.) | App update delivery (OTA) | Technical connection data (IP, device info) | USA | https://expo.dev/privacy |
| **Apple** (Apple Inc.) | Map on iOS (Apple Maps) and App Store distribution | Technical map data, download data | Global | https://www.apple.com/legal/privacy/ |
| **OpenStreetMap Foundation** | Map tiles on Android | Technical connection data (IP) | EU/UK | https://wiki.osmfoundation.org/wiki/Privacy_Policy |
| **Google** (Google LLC) | Google Play distribution | Download and install data | Global | https://policies.google.com/privacy |

With providers acting as processors we have in place (or enter into) a **Data Processing Agreement (DPA)** under Art. 28 GDPR.

---

## 7. Transfers outside the European Union

Diagnostics (**Sentry**) and analytics (**PostHog**) data are hosted on **servers located in the European Union**.

Some providers (e.g. **Expo**, **Apple**, **Google**, and Sentry/PostHog as US companies) may be located in or access the data from the United States. In such cases the transfer complies with Chapter V GDPR via **Standard Contractual Clauses** approved by the European Commission and/or adherence to the **EU–U.S. Data Privacy Framework**, together with appropriate supplementary measures. You may request a copy of the safeguards by writing to the address in § 1.

---

## 8. Data retention

- **Local data on the device** (favourites, settings, `device_id`): kept until you delete them in the App or uninstall it.
- **Crash diagnostics (Sentry):** kept for a limited period, typically about **90 days**.
- **Usage analytics (PostHog):** kept only as long as needed for statistical purposes, and in any case no longer than **12 months**, after which it is aggregated or deleted.
- **Location and calendar:** not retained by us (see § 3).

At the end of these periods the data is irreversibly deleted or anonymised.

---

## 9. Your rights

As a data subject you have the right, within the limits of Arts. 15–22 GDPR, to:

- **access** your data and obtain a copy;
- request **rectification** or **erasure** ("right to be forgotten");
- request **restriction** of processing;
- **object** to processing based on legitimate interest (e.g. diagnostics);
- obtain **data portability** for data processed on the basis of consent or contract;
- **withdraw consent** at any time (for analytics, directly in the App's settings), without affecting prior lawful processing.

**How to exercise them.** Most data stays on your device: you can delete it yourself by clearing favourites, disabling analytics, or uninstalling the App. For server-side data (diagnostics/analytics) write to the address in § 1. Since we identify you only by an anonymous code (`device_id`), to act on your request we may ask you to provide that code, available in the App's Profile section; without it we may be unable to locate the data concerning you (Art. 11 GDPR).

**Complaint to the supervisory authority.** If you believe the processing infringes the GDPR, you may lodge a complaint with the Italian **Garante per la protezione dei dati personali** (Piazza Venezia 11, 00187 Rome — www.garante.it — garante@gpdp.it), or with the authority of the EU State where you reside.

---

## 10. Security

We adopt appropriate technical and organisational measures to protect data. In particular, all communications between the App and servers use **encrypted (HTTPS/TLS)** connections. Data stored on the device is protected by the operating system's security mechanisms.

---

## 11. Automated decision-making

We do **not** carry out any automated decision-making or profiling producing legal or similarly significant effects on you (Art. 22 GDPR).

---

## 12. Children

The App is **not intended for children under 13** (the age of digital consent in Italy under Art. 2-quinquies of the Privacy Code). We do not knowingly collect data from children under 13. If you are a parent or guardian and believe a minor has provided us with data, contact us at the address in § 1 and we will delete it.

---

## 13. Distribution via app stores

The App is distributed via the **Apple App Store** and **Google Play**. Download, installation and any payments are handled by Apple and Google under their respective privacy policies, over which we have no control.

---

## 14. Changes to this policy

We may update this policy to reflect changes to the App or legal obligations. The current version is always available at **https://alicefr1998-eng.github.io/csf-privacy-policy/** and, for significant changes, we will notify you within the App. The date at the top indicates the last update.

---

## 15. Contact

For any question about this policy or the processing of your data:

- **Email:** chesifa.app@gmail.com
- **Controller:** Alice Frugone, Italy

---

*Drafted in accordance with Regulation (EU) 2016/679 (GDPR), Italian Legislative Decree 196/2003 (Privacy Code) as amended by Legislative Decree 101/2018, and Directive 2002/58/EC (ePrivacy).*
