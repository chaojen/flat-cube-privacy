# Privacy Policy

**Applies to: Flat Cube: Unfolded Puzzle ("Flat Cube")**

**Effective date: September 23, 2026**
**Last updated: September 25, 2026**

ChaoJen ("we," "us," or "our") respects and protects your privacy. This Privacy Policy explains what data the Flat Cube mobile application (the "App") collects, how it is used and shared, and the choices you have.

By downloading or using the App, you acknowledge that you have read this Policy. If you do not agree, please stop using the App.

---

## 1. Information We Collect

### 1.1 Account
The App does not require you to register or sign in. When you open it, Firebase Authentication creates an **anonymous (guest) account** for you in the background. For a guest account we receive only a randomly generated unique user identifier (UID), and we do not collect your name, email address, or phone number.

The UID is what lets the leaderboard know which results are yours. A guest account is tied to this installation of the App: if you uninstall the App or clear its data, a new guest account is created the next time you open it, and your previous results can no longer be linked back to you from the App.

**Optional sign-in with Apple or Google.** If you choose to, you can sign in with Apple or Google in Settings so that you can keep your results when you change devices or reinstall the App. Your existing UID, results, and nickname stay the same. When you do, Firebase Authentication receives from Apple or Google:
- An account identifier issued by that provider
- Your email address. With Sign in with Apple you can choose to hide your email, in which case we receive a private relay address from Apple instead.

We use this information only to let you sign back in to the same account. It is not shown to other players. We do not receive your Apple or Google password.

### 1.2 Leaderboard Nickname
If you choose to, you can set a **nickname** (up to 20 characters) in Settings. It is shown next to your results on the leaderboard. Please do not use your real name or other personal information as your nickname.

### 1.3 Solve Results
When you start a timed, ranked solve, the App sends the following to our servers so that the result can be verified and ranked:
- The scramble you were given and the moves you made
- When the solve was issued, started, and submitted, and the elapsed time
- The move count, and whether the result is a new personal or leaderboard best

We also keep a summary on your player profile: your best time, the number of solves you have submitted, and when you last submitted one.

Practice solves (when a ranked scramble is unavailable) and free play are **not** sent to our servers. Your free-play progress and your layout and control settings are stored only on your device.

### 1.4 Usage Analytics
We use Firebase Analytics to understand how the App is used, for example:
- Screens you visit (the home screen, the cube, the leaderboard, settings)
- When a timed solve is started, completed, or abandoned, with its move count, elapsed time, and whether it was ranked
- Which control mode you use
- Device model, operating system version, language, approximate region (estimated from IP address), and an app-instance identifier

Analytics events are associated with your anonymous UID.

### 1.5 Crash and Diagnostic Data
We use Firebase Crashlytics to receive crash reports and error diagnostics, which may include the stack trace, device model, operating system version, app version, and an installation identifier. Crash reports are associated with your anonymous UID so that we can investigate problems you report.

### 1.6 Advertising
The App shows ads through Google AdMob: a banner at the bottom of the main screen, and a full-screen ad after you complete a timed solve. To serve and measure ads, AdMob may collect:
- The advertising identifier (IDFA on iOS or the Advertising ID on Android)
- Device model, operating system version, language, IP address, and approximate location derived from it
- Ad interactions, such as impressions and clicks

**On iOS**, the App asks for permission through Apple's App Tracking Transparency prompt before the IDFA can be used. If you decline, AdMob cannot access the IDFA and serves ads without tracking you across other companies' apps and websites.

**In the European Economic Area, the United Kingdom, and Switzerland**, the App asks for your consent through Google's consent message before showing ads. You can consent, decline, or choose specific purposes, and you can change your choice at any time under **Settings → Ad privacy options**.

You can also reset or limit the advertising identifier in your device's settings.

### 1.7 What We Do Not Collect
- We do **not** access your contacts, photos, camera, microphone, or precise location.
- Firebase Analytics does **not** collect the advertising identifier; only AdMob uses it, as described in Section 1.6.
- The App has no in-app purchases, so we do not handle payment information.
- We do not receive your name from Apple or Google, and we do not access your contacts or other data in those accounts.

---

## 2. How We Use Your Information

We use the information we collect to:
- Issue scrambles, time your solves, verify results, and publish the leaderboard
- Show your nickname and results on the leaderboards (the 30-day leaderboard; earlier versions of the App show daily and all-time leaderboards), and show you your own records
- Let you sign back in to the same account with Apple or Google, if you choose to
- Understand how the App is used so that we can improve it
- Diagnose crashes and fix bugs
- Prevent abuse and protect our backend through Firebase App Check
- Show ads through Google AdMob, which funds the App

We do **not** sell your personal data. Apart from the advertising data that AdMob collects as described in Section 1.6, we do not use your data for advertising.

---

## 3. What Other Players Can See

The leaderboard is visible to everyone who uses the App. For each entry it shows:
- Your nickname (or a placeholder if you have not set one)
- Your best time and its move count
- When that result was achieved

The moves of your solves, your email address, your analytics data, and your crash reports are **not** shown to other players.

---

## 4. Third-Party Services

The App uses the following Google services, which process data on our behalf. We recommend that you also review their privacy policies:

| Service | Purpose | Privacy Policy |
| --- | --- | --- |
| Firebase Authentication | Guest accounts and optional sign-in with Apple or Google | https://firebase.google.com/support/privacy |
| Sign in with Apple | Optional sign-in | https://www.apple.com/legal/privacy/ |
| Google Sign-In | Optional sign-in | https://policies.google.com/privacy |
| Cloud Firestore and Cloud Functions for Firebase | Storing and verifying solves, nicknames, and the leaderboard | https://firebase.google.com/support/privacy |
| Google Analytics for Firebase | Usage analytics | https://firebase.google.com/support/privacy |
| Firebase Crashlytics | Crash reporting | https://firebase.google.com/support/privacy |
| Firebase App Check | Protecting the backend from abuse | https://firebase.google.com/support/privacy |
| Google AdMob | Showing ads | https://policies.google.com/technologies/ads |

We do not share your data with any other third party, except as required by law (see Section 5).

---

## 5. Data Sharing and Disclosure

We share your data only:
- **With other players**, as described in Section 3
- **With the service providers** listed in Section 4, only as needed to operate the App
- **When required by law**, to comply with a court order or a lawful request from a government authority

---

## 6. Data Storage and Retention

- Your data is stored on Google Cloud servers located in the United States.
- Solve records, your player profile, leaderboard entries, and your account are kept for as long as the leaderboard is operated, unless you delete your account (see Section 8).
- Analytics and crash data are kept according to Firebase's retention settings, currently up to 14 months for Analytics and up to 90 days for Crashlytics.

---

## 7. Data Security

Data sent between the App and our servers is encrypted in transit (HTTPS). Access to the database is restricted by Firestore Security Rules: your device can change only your own nickname, and results are written only by our server after verification. Firebase App Check helps ensure that requests come from the genuine App. No method of transmission or storage is 100% secure, but we take reasonable measures to protect your data.

---

## 8. Your Choices and Rights

- **Nickname**: You can change your nickname at any time in Settings.
- **Sign out**: If you signed in with Apple or Google, you can sign out in Settings. The App then continues with a new guest account, and you can sign back in later to get your results back.
- **Account deletion**: You can delete your account at any time under **Settings → Delete account**. This immediately and permanently deletes your account, nickname, solve records, and all of your leaderboard entries (30-day, daily and all-time), and the App continues with a new guest account. On iOS, if you signed in with Apple, the App also revokes its Sign in with Apple authorization. Analytics and crash data are not linked to a name or email and expire according to Section 6. If you can no longer open the App, you can also email us at the address below to request deletion; we will delete the data within 30 days.
- **Ads**: You can change your ad consent under Settings → Ad privacy options (where required by law), turn off tracking permission for the App in iOS Settings, or reset the advertising identifier in your device settings.
- **Stopping collection**: You can stop all data collection at any time by uninstalling the App.

---

## 9. Children's Privacy

The App is not directed at children under the age of 13 (or the minimum age required by the laws of your region), and we do not knowingly collect personal data from children. The App does not require any personal information; signing in with Apple or Google is optional. If you believe a child has entered personal information, for example as a nickname, please contact us and we will delete it.

---

## 10. International Data Transfers

Because our servers are located in the United States, your data may be transferred to and processed in a country other than your own. By using the App, you consent to this transfer.

---

## 11. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will update the "Last updated" date on this page, and for material changes we may also notify you within the App.

---

## 12. Contact Us

If you have any questions or requests regarding this Privacy Policy, please contact us:

- **Email**: chao.jen.main@gmail.com
- **Operator / Developer**: ChaoJen
