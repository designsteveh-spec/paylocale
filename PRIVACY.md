# PayLocale Privacy Policy

**Last updated:** June 2026

This policy applies to the PayLocale Android app. The same text is available in the app under **Settings → Privacy policy**.

## Overview

PayLocale is an offline-first travel utility. We help you understand how to pay in different countries. This policy explains what data the app uses, why, and your rights — including if you are in the European Economic Area (EEA), United Kingdom, or Switzerland.

## Data controller

The data controller responsible for PayLocale is:

- **Stephen Heidelberg**
- Where applicable, apps are offered through **Naamans Creek Ventures LLC**
- **Privacy contact:** designstehev@gmail.com

We do not operate user accounts or a separate customer website for PayLocale.

## Data we store on your device

The app saves a small amount of information locally using Android DataStore:

- Your selected or last-known country
- Your home currency preference
- Whether you have seen the location permission explanation
- Cached exchange rates and cache timestamps (for the FX calculator)
- **PayLocale Pro entitlement** — a local flag set after Google Play verifies a purchase (we do not store payment card details)
- **Pinned trip countries** (Pro) — up to five country codes you choose
- **Downloaded country data version** (Pro) — if you use “Check for data updates”

**Legal basis (GDPR):** processing is necessary for the app to function as you expect (performance of the service / legitimate interest). This data stays on your device and is not uploaded to our servers.

## Location

If you allow location access, PayLocale uses your device location (approximate or precise, depending on the permission you grant) to detect which country you are in and show relevant payment guides.

- Location is requested only when you choose to enable it (in-app explanation, then the Android system permission prompt).
- You may decline permission and select a country manually at any time.
- Coordinates are converted to a country code on your device. We do not store your precise coordinates in our own database or sell location data.

**Legal basis (GDPR):** your **consent**, which you may withdraw by revoking location permission in Android settings or clearing app data.

**Third parties involved in location:** Google Play Services (device location) and, when online, the Android system geocoder may process location data under Google's terms. We do not control those providers.

## Payment guides (offline data)

Country payment guides, app recommendations, and ATM information are bundled inside the app. This content is read from local files and is not sent off your device by PayLocale.

**PayLocale Pro data updates:** Pro users may optionally download updated country JSON from our public GitHub repository. That request contacts GitHub (not our servers) and saves the file on your device. Free users remain on bundled data until an app update.

## In-app purchases (PayLocale Pro)

PayLocale Pro is a one-time in-app purchase processed entirely by **Google Play Billing**. We do not receive or store your payment card number. Google processes the transaction under [Google Play’s terms and privacy policy](https://policies.google.com/privacy).

When you purchase or restore Pro, the app queries Google Play on your device and stores a local entitlement flag so Pro features work offline. You can restore purchases on a new device signed into the same Google account via **Settings → Restore purchases**.

**Legal basis (GDPR):** performance of a contract (providing the Pro features you purchased).

## Network connections and third parties

PayLocale makes limited network requests:

| Service | Purpose | Data involved |
|---------|---------|----------------|
| **Frankfurter API** (api.frankfurter.app) | FX calculator exchange rates | Currency codes only in the request; the provider may log technical data such as IP address |
| **Google Play Services** | Device location (if permitted) | Location data per Google's policies |
| **Android Geocoder** | Country lookup fallback when online | Coordinates may be sent to the geocoder provider (often Google) |
| **Google Play** | Opening recommended app listings; in-app purchases and purchase verification | Standard Play Store / Billing interaction |
| **GitHub** (raw.githubusercontent.com) | Optional Pro country-data updates | HTTP request for public JSON files; GitHub may log technical data |
| **Google Maps** | Nearest ATM search (Pro) — opens Maps with your location and a bank search query | Location and query passed to Maps when you tap the map icon |
| **Your browser** | Wise, PayPal, or other sign-up links you tap | Governed by that site’s policies |

We do not use analytics SDKs, advertising networks, or cloud user databases.

**Legal basis (GDPR):** **legitimate interest** in providing current exchange rates and location-based country detection, or **consent** where required (location).

## International data transfers

PayLocale is developed in the United States. When the app contacts third-party services (for example Frankfurter or Google), data may be processed in countries outside your own, including outside the EEA/UK. Those providers apply their own safeguards as described in their privacy policies.

We do not transfer personal data from your device to servers we operate.

## Retention

- **On-device preferences and rate cache:** kept until you clear app storage, uninstall the app, or we change what is stored in a future update (described in an updated policy).
- **Data held by third parties:** governed by their retention policies.

## Your rights (EEA / UK / similar jurisdictions)

Depending on where you live, you may have the right to:

- **Access** information about processing (this policy describes what we process)
- **Erasure** — uninstall the app or clear PayLocale’s storage in Android settings (**Settings → Apps → PayLocale → Storage → Clear data**)
- **Withdraw consent** — revoke location permission or stop using optional features
- **Object** to processing based on legitimate interest — contact us; given our minimal processing, uninstalling or clearing data is usually sufficient
- **Lodge a complaint** with your local data protection supervisory authority

We do not maintain remote profiles, so most requests can be fulfilled on your device without contacting us. For other privacy questions or to exercise your rights, email **designstehev@gmail.com**.

## What we do not collect

We do not collect your name, email, payment card numbers, or transaction history through PayLocale itself. PayLocale does not process payments.

## Children

PayLocale is not directed at children. It should not be used by anyone under **16** without parental or guardian consent where local law requires it.

## Changes

We may update this policy as the app evolves. Material changes will be reflected in the in-app **Settings → Privacy policy** text and in this document.

## Contact

Privacy questions: **designstehev@gmail.com**

You may also use the developer contact shown on the PayLocale Google Play store listing.
