# Privacy Policy for Revive ’N Drive

**Effective date:** September 22, 2026  
**Last updated:** October 20, 2026

Revive ’N Drive ("Revive ’N Drive," "we," "us," or "our") provides the **Revive ’N Drive: My Garage** Android application (package name `com.revivendrive`). This policy explains what information the app handles, why it is used, when it is shared, and the choices available to you.

Revive ’N Drive is a consumer application for managing your own vehicles, maintenance and repair records, diagnostic notes, automotive reference information, and free digital field guides. It is separate from Mobile Mechanic Shop OS, which is a professional business product.

## Information we handle

### Google account and cloud Garage information

Google sign-in is optional. If you sign in, Google may provide your name, email address, profile image, and a Google account identifier. Google handles authentication; we do not receive your Google password.

When cloud synchronization is configured and you sign in, Revive ’N Drive stores a private Garage snapshot in Google Firebase Cloud Firestore under your authenticated account. Synced information may include:

- VIN, year, make, model, trim, engine, mileage, category, and vehicle notes;
- maintenance and repair records, service dates, mileage, parts, costs, and notes;
- diagnostic symptoms, trouble codes, answers, observations, possible causes, and outcomes;
- saved part references and vehicle specifications;
- app preferences and Library reading progress; and
- references to user-selected photos, receipts, and documents.

Structured Garage data is also stored locally so the app remains usable offline. Local file/content references do not themselves upload the referenced binary file in the current version. Firestore access rules are designed so authenticated users can access only data below their own user identifier.

Our use of information received from Google APIs complies with the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including Limited Use requirements where applicable.

### Camera and selected files

Camera permission is optional and is used to scan text from a VIN plate, label, or document. Camera frames are analyzed on the device for text recognition and are not used to record video continuously. Detected text is shown for confirmation.

When you select a vehicle photo, receipt, PDF, or other document through Android’s system picker, the app accesses only the item you select.

### VIN decoding

When you deliberately request a VIN lookup, the VIN is sent over an encrypted connection to the U.S. National Highway Traffic Safety Administration vPIC service. NHTSA may receive ordinary network information such as your IP address. See the [NHTSA privacy policy](https://www.nhtsa.gov/privacy).

### Advertising, consent, and identifiers

The free app displays advertising using the Google Mobile Ads SDK (AdMob). Depending on your device, region, consent choices, Google settings, and ad availability, Google Mobile Ads may process:

- the Android advertising ID, app set ID, and other device or account identifiers;
- IP address, general device information, app interactions, diagnostic information, and ad impressions/clicks; and
- consent signals and information needed to select, deliver, limit, measure, secure, and prevent fraud involving advertisements.

Revive ’N Drive uses Google’s User Messaging Platform to request consent and provide privacy options where required. You can also reset or delete the Android advertising ID in Android settings. We do not sell personal information. See [Google’s advertising privacy information](https://policies.google.com/technologies/ads).

### Google Play purchase

Revive ’N Drive offers a one-time `remove_ads` purchase. Google Play processes payment and maintains the purchase entitlement. We do not receive full card or bank details. Google Play may provide product ID, price/offer information, purchase status, purchase time, acknowledgement/refund status, and a purchase token needed to verify and restore the entitlement. The app stores a one-way SHA-256 hash of a purchase token in its local entitlement record rather than the raw token.

The included Library field guides are currently free. Revive ’N Drive+ is a future, separate premium system and is not an active entitlement unless explicitly offered in the app and Play listing.

### Technical information

Google Play, Firebase, Google Identity, Google Mobile Ads, Android, NHTSA, and network services may process standard technical information required to provide their services, including app/device version, IP address, timestamps, diagnostic events, authentication status, ad events, and transaction status.

## How information is used

We use information to:

- provide, personalize, save, synchronize, and restore Garage features;
- provide maintenance, diagnostic, parts/specification, and Library features;
- decode a VIN only when requested;
- authenticate accounts and protect access;
- display, limit, measure, and secure advertising;
- verify, acknowledge, restore, or revoke the Remove Ads entitlement;
- respond to support, privacy, and deletion requests;
- diagnose reliability, abuse, fraud, or security problems; and
- comply with law and enforce applicable terms.

## Sharing and service providers

Limited information may be shared:

- **Google Firebase and Google Identity:** account authentication and private Garage synchronization;
- **Google Mobile Ads and User Messaging Platform:** ad delivery, measurement, consent, security, and fraud prevention;
- **Google Play:** billing, entitlement restoration, refunds, and fraud prevention;
- **NHTSA:** only when you request VIN decoding;
- **service providers or authorities:** where necessary to operate the service, comply with law, investigate abuse, or protect rights and safety; or
- **a successor organization:** if the app or its assets are transferred, subject to this policy and applicable law.

We do not sell personal information.

## Retention and deletion

Local Garage information remains until you delete records, clear app storage, or uninstall the app. Cloud Garage information remains until you use the in-app **Delete Cloud Account & Garage** action or submit a verified deletion request.

Use our external deletion page:

**[Delete your Revive ’N Drive account and Garage data](https://revivendrive.github.io/revive-n-drive-privacy/delete-account.html)**

Deletion removes the Revive ’N Drive Firebase Authentication account and cloud Garage data we control, subject to limited retention required for legal, security, fraud-prevention, or transaction obligations. It does not delete your Google Account or Google Play transaction history. Google Play purchase records remain subject to Google’s policies.

You may revoke connected-app access through Google Account settings. Revoking access stops future authorization but does not automatically delete data already stored; use one of the deletion methods above as well.

## Security

We use reasonable safeguards including encrypted network connections, Android private app storage, authenticated Firebase access, and per-user Firestore access rules. No storage or transmission system is completely secure.

## Children’s privacy

The app is intended for a general automotive audience and is not directed to children under 13. We do not knowingly collect personal information from children under 13. Contact us if you believe a child has supplied personal information.

## Your choices and rights

Depending on your location, you may request access, correction, deletion, restriction, withdrawal of consent, or a copy of personal information we control. We may need to verify identity.

You may use core local Garage features without Google sign-in, decline camera permission and enter a VIN manually, manage advertising privacy options where shown, or purchase permanent ad removal through Google Play.

## Changes

We may update this policy as the app, service providers, or legal requirements change. The “Last updated” date will identify the latest revision, and material changes may receive additional notice.

## Contact

**Revive ’N Drive**  
Email: **tanneralcala@gmail.com**  
Account deletion: [revivendrive.github.io/revive-n-drive-privacy/delete-account.html](https://revivendrive.github.io/revive-n-drive-privacy/delete-account.html)  
GitHub: [ReviveNDrive](https://github.com/ReviveNDrive)

This policy describes privacy practices and is not legal advice. Rights may vary by jurisdiction.
