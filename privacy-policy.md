# RufusFox — Privacy Policy

**Effective date:** 25 June 2026
**Last updated:** 25 June 2026

This Privacy Policy explains what personal data the **RufusFox** Android app
("**RufusFox**", "the app", "we", "us") collects, why, how it is stored, and the
rights you have over it.

**Provider / data controller:** Ambifuge Studio (an individual developer based in
Hungary), contact **rufusfox.support@gmail.com**. You can ask for the name of the
responsible individual at that address.

If you do not agree with this policy, please do not use the app. You can use most
of RufusFox **without an account**; some features (cloud backup/sync) require one.

---

## 1. Summary (the short version)

- RufusFox works **offline-first**. Your tasks, lists, water, medication and
  settings are stored **on your device**.
- If you **create an account and sign in**, that data is also backed up to
  **Google Firebase (Firestore)** so you can restore it on another device.
- We do **not** sell your data, show ads, or use it for advertising or profiling.
- You can **export** all your data and **permanently delete** your account and
  data from inside the app at any time.

---

## 2. What data we collect, why, and the legal basis

We only process data needed to provide the app's features. Under the GDPR, our
legal bases are shown in brackets.

### a) Account data (only if you sign in)
- **What:** your email address and an authentication identifier (a Firebase user
  ID), managed by **Firebase Authentication**. If you sign in with Google, Google
  provides your email and a sign-in token; we do not receive your Google password.
- **Why:** to create and secure your account and enable cloud backup/sync.
- **Legal basis:** performance of a contract (providing the account service).

### b) App content (your RufusFox data)
- **What:** the content you create in the app — tasks, lists, water intake,
  medication and courses, the timer, and your in-app settings.
- **Where:** always on your device; **additionally** synced to Firestore **only
  while you are signed in**.
- **Why:** to provide the app's core functionality and to back up/restore your
  data across devices.
- **Legal basis:** performance of a contract / our legitimate interest in
  providing a working, recoverable app.

### c) Diagnostics & crash reports
- **What:** if RufusFox crashes, a report can include the error details, your
  device model and OS version, recent in-app diagnostic logs, and (if signed in)
  your account email.
- **How:** **off by default.** Automatic sending only happens if you turn on
  "Auto-send crash reports" in Settings → Diagnostics. You can also send a report
  manually from the Feedback screen.
- **Why:** to find and fix bugs.
- **Legal basis:** your **consent** (you can withdraw it any time by turning the
  setting off).

### d) Feedback you send
- **What:** the message you write, plus app version, device model, OS, and (if
  signed in) your account email/ID.
- **Why:** to respond to and act on your feedback.
- **Legal basis:** our legitimate interest in supporting and improving the app.

### e) Notifications
- The app schedules **local** reminders (medication, water, daily summaries,
  timer). These are generated on your device; no personal data is sent to us to
  deliver them.

We do **not** collect advertising identifiers, contacts, location, or biometric
data, and we do not track you across other apps or websites.

---

## 3. Who your data is shared with (processors)

We do not sell or rent your data. We use the following processor to provide the
service:

- **Google Firebase** (Firebase Authentication, Cloud Firestore, App Check) —
  Google Ireland Ltd. / Google LLC — hosts your account and your synced app data,
  and protects the backend from abuse. Google acts as our data **processor** under
  its Data Processing Terms.

Aside from this processor, we only disclose data if required by law.

---

## 4. International transfers

Firebase/Firestore may store and process data on **Google servers located outside
Hungary/the EEA, including in the United States**. Where data is transferred
outside the EEA/UK, Google relies on safeguards such as the **EU Standard
Contractual Clauses**. See Google's Privacy Policy and Cloud Data Processing Terms
for details.

---

## 5. Device backup (Android Auto Backup)

Android may include the app's local data file in **Android Auto Backup** to your
own Google account. This backup is managed by Android and **end-to-end encrypted**
(tied to your Google account and device PIN on Android 9+); we cannot access it.
You can disable Auto Backup for the app in your device's system settings.

---

## 6. How long we keep data (retention)

- **Account + synced app data:** kept until **you delete your account** (see
  Section 8) or ask us to delete it. Dated backup snapshots are kept on a rolling
  basis (roughly the most recent ~20, plus one per day for up to ~14 older days)
  and are deleted when you delete your account.
- **Crash/diagnostic reports & feedback:** kept only as long as needed to
  diagnose issues and respond, and in any case no longer than 12 months.
- **Local data on your device:** stays until you delete it in the app, sign out
  (which clears this device after backing up), or uninstall the app.

---

## 7. Security

- All network traffic uses **HTTPS/TLS**.
- Authentication tokens are stored in the Android **Keystore-backed encrypted
  storage** on your device.
- Cloud security rules ensure **only you** can read or write your own synced data.
- App Check helps protect the backend from abuse.

No system is perfectly secure, but we take reasonable measures to protect your data.

---

## 8. Your rights

Under the GDPR (and similar laws) you have the right to **access, rectify, export
(portability), delete, restrict, and object** to the processing of your data, and
to **withdraw consent**. RufusFox supports the main rights directly in the app:

- **Export your data:** Settings → "Your data" → **"Export my data"** produces a
  complete JSON file of your app data that you can save or share.
- **Delete your account and data:** Settings → Account → **"Delete account &
  data"** permanently deletes your account and all your cloud data (and wipes the
  local copy on that device). **This cannot be undone.**
- **Withdraw crash-report consent:** Settings → Diagnostics → turn off "Auto-send
  crash reports".

If you have uninstalled the app, you can still request deletion via our
**[account-deletion page](account-deletion.md)** or by emailing
**rufusfox.support@gmail.com**. You also have the right to lodge a complaint with
your local data protection authority (in Hungary: the **NAIH**).

---

## 9. Children

RufusFox is **not directed at children under 16** and we do not knowingly collect
data from them. If you believe a child has provided us data, contact us and we
will delete it.

---

## 10. Changes to this policy

We may update this policy. We will change the "Last updated" date above and, for
significant changes, provide an in-app notice. Continued use after an update means
you accept the revised policy.

---

## 11. Contact

Questions or requests about this policy or your data:
**rufusfox.support@gmail.com**.
