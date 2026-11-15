---
layout: default
title: Privacy Policy — Tip Sheet 2
---

# Privacy Policy for Tip Sheet 2

_Last updated: November 14, 2026_

Tip Sheet 2 ("the app") is designed with your privacy as a priority. This policy explains what information the app collects, how it is used, and the choices you have.

## Information Stored on Your Device and in Your iCloud

Tip Sheet 2 stores all of your shift, job, tip, and earnings data locally on your device using Apple's SwiftData framework. If you have iCloud enabled, this data is automatically synced to your personal iCloud account via CloudKit, and your app preferences (such as default shift settings and visible fields) sync via Apple's iCloud Key-Value Storage, so everything stays up to date across your own Apple devices.

**We do not have access to this data.** It never leaves Apple's ecosystem and is not transmitted to any server operated by the developer.

## Location

If you grant location permission, Tip Sheet 2 uses your location on-device via Apple's CoreLocation framework for:
- **While Using the App:** Automatically suggesting your nearest job when you start a new shift near a job's saved location.
- **Always (Optional):** Monitoring your saved job's geofence in the background to remind you to log your shift when you leave work.

Location data is processed strictly on-device and is never transmitted off your device or shared with third parties.

## Analytics

Tip Sheet 2 uses Firebase Analytics (provided by Google) to understand how the app is used in aggregate and to improve the product. The analytics data collected is limited to anonymous usage events such as:

- Which screens are viewed and how long they are viewed
- Onboarding progression and feature usage (e.g., creating jobs/shifts, configuring rules, exporting a CSV, importing a Tip Sheet v1 backup, viewing reports, configuring shift reminders, and review prompt milestones)
- General app lifecycle events (app sessions)

**We never send any of the following to analytics:**
- Monetary values (tips, wages, sales, earnings)
- Hours worked
- Job names or employer information
- Shift notes or star ratings
- Any other personally identifying information

Analytics data is associated only with an anonymous app-instance identifier managed by Firebase and is not linked to your identity or used for tracking across other apps or websites.

## In-App Purchases &amp; StoreKit 2 Revenue Tracking

Tip Sheet 2 offers a one-time, non-consumable in-app purchase ("Tip Sheet 2 Pro") processed by Apple. The developer does not receive or store your payment information; purchase validation is handled entirely through Apple's StoreKit 2.

When you complete a new purchase of Tip Sheet 2 Pro, anonymous StoreKit 2 transaction metadata is logged via Firebase Analytics (`Analytics.logTransaction`) to measure purchase conversions and app revenue in aggregate. No personal payment details or Apple ID information are collected.

## Crash &amp; Diagnostic Data

Tip Sheet 2 uses Apple's **MetricKit** framework on-device to capture recent crash and hang diagnostics locally. This diagnostic data is stored only on your device and is **never** sent automatically.

If you choose **Settings → Contact Support** and select **Attach Report**, the app attaches a non-financial diagnostic report (app version, iOS version, iCloud sync status, and the most recent on-device MetricKit diagnostic payload) to your support email draft to help troubleshoot issues. You can choose **Don't Attach** at any time.

## Third-Party Services

The app uses the following third-party services:

- **Apple CloudKit &amp; iCloud** — for optional iCloud sync across your devices. Governed by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).
- **Google Firebase Analytics** — for anonymous usage analytics and StoreKit 2 purchase attribution. Governed by [Google's Privacy Policy](https://policies.google.com/privacy).

## Children's Privacy

Tip Sheet 2 is not directed at children under 13 and does not knowingly collect personal information from children.

## Your Choices

- You can disable iCloud sync for Tip Sheet 2 in iOS **Settings → [Your Name] → iCloud**.
- You can revoke or adjust location permissions in iOS **Settings → Privacy &amp; Security → Location Services**.
- You can disable analytics collection by limiting ad/analytics tracking in iOS **Settings → Privacy &amp; Security**.
- You can delete all local app data at any time by deleting the app, and remove iCloud data via iOS **Settings → [Your Name] → iCloud → Manage Account Storage → Tip Sheet 2**.

## Changes to This Policy

This policy may be updated from time to time. The "Last updated" date above reflects the most recent revision.

## Contact

If you have questions about this privacy policy, contact: **support@tipsheetapp.com**
