# Privacy Policy for PlateVitals

**Last updated:** October 27, 2026  
**Developer:** Vernon Bearss (doing business as PlateVitals)  
**Contact:** csavern@gmail.com  
**App:** PlateVitals (Android package `com.vern.diettracker`)

This Privacy Policy describes how PlateVitals (“we,” “us,” or “the App”) collects, uses, stores, and shares information when you use the PlateVitals Android application. By using the App, you agree to this policy.

**PlateVitals is a wellness and fitness tracking tool. It is not a medical device and is not intended to diagnose, treat, cure, or prevent any disease. Always consult a qualified healthcare professional for medical advice. Continuous glucose monitor (CGM) readings shown in the App (including data originating from devices such as Abbott Lingo) may be delayed and are for personal wellness awareness only.**

---

## 1. Information We Collect

### 1.1 Account and identity
When you sign in (Google Sign-In and/or email account options offered in the App), we may collect:

- Name and email address associated with your account  
- Google account identifiers and profile photo URL (if provided by Google Sign-In)  
- Authentication tokens needed to keep you signed in and to sync your data  

### 1.2 Profile and food / wellness logs (you provide)
Depending on how you use the App, this may include:

- Profile details you enter (for example goals, diet style such as Keto / Diabetic / Heart-Health preferences, water and macro targets)  
- Meal and food logs, barcodes scanned, water intake, habits, and related notes  
- Photos or images you choose to capture or select from your photo album for food logging  
- Local preferences and onboarding choices  

### 1.3 Health and fitness data (Health Connect — only with your permission)
If you connect Android Health Connect and grant permissions, the App may **read** (it does not write back to Health Connect in the current product) data such as:

- Blood glucose (for example readings shared into Health Connect by Abbott Lingo or other CGM apps; readings may lag by roughly three hours or more depending on the source app)  
- Steps  
- Heart rate (including resting heart rate when available)  
- Blood pressure  
- Weight  
- Active calories burned  
- Oxygen saturation  
- Sleep  

Samsung Health (and similar apps) are used **only** when they share data into Health Connect and you grant PlateVitals the corresponding Health Connect permissions. We do not access Samsung Health through a separate proprietary API in the current App.

You can revoke Health Connect permissions at any time in Android / Health Connect settings or by disconnecting in the App.

### 1.4 Device and technical data
The App may process limited technical information needed to operate, such as:

- Device identifiers used by Google / Firebase for authentication and crash-free operation  
- App version, platform (Android), and similar diagnostics you see in Settings  
- Notification permission status (local reminders; not used for advertising)  

### 1.5 AI food estimates from photos or text
If you use camera / album food logging or AI meal analysis, meal photos and/or meal descriptions you submit are sent to **Google Gemini** (Google Generative Language API) to estimate food identity and nutrition. Those images and prompts are processed by Google under Google’s terms and privacy practices for that API. Do not upload photos you do not want processed for that purpose.

---

## 2. How We Use Information

We use the information above to:

- Provide account sign-in, cloud backup/restore, and multi-device sync when Firebase is configured  
- Display food logs, macros, water, habits, goals, and Health Connect vitals in the App  
- Improve food estimates via AI vision when you request them  
- Send **local** reminders you enable (meal, water, or similar notifications on your device)  
- Maintain security, prevent abuse, and support the App  

We do **not** sell your personal information.  
We do **not** currently show third-party ads in the App.

---

## 3. Where Data Is Stored

- **On your device:** Day logs, preferences, and related state are stored locally (including browser-style local storage in the app WebView and Capacitor Preferences).  
- **In the cloud (when you are signed in and Firebase is enabled):** Profile and health/food state used for sync may be stored in **Google Firebase Authentication** and **Cloud Firestore** under your user account (Firebase project associated with PlateVitals).  
- **Health Connect:** Source health records remain under Android Health Connect / the originating apps (for example Lingo). PlateVitals reads copies you authorize for display and local/cloud sync of the App’s own state.  
- **AI analysis:** Photos/text you submit for food analysis are transmitted to Google’s Gemini API for processing as described above.

---

## 4. Sharing of Information

We share data only as needed to operate the App:

| Recipient | Purpose |
|-----------|---------|
| **Google (Sign-In / Firebase Auth / Firestore)** | Authentication and optional cloud sync of your app state |
| **Google (Gemini API)** | Food photo / description analysis when you use that feature |
| **Android Health Connect** | Permission-gated reading of health data you approve (no sale of that data) |
| **Service providers** | Only as embedded in the Google/Firebase/Android stack required to run the App |

We do not share your health or food data with advertisers. We may disclose information if required by law or to protect rights, safety, or the integrity of the service.

---

## 5. Retention

- Local data remains on your device until you clear app data, uninstall, or delete content in the App.  
- Cloud (Firestore / Auth) data is retained while your account exists and cloud sync is used, or until you request deletion.  
- AI requests are processed to return an estimate; we do not operate a separate long-term photo archive outside the providers above. Avoid uploading sensitive images you do not need analyzed.  

Exact retention for Google/Firebase services is also governed by Google’s applicable terms and retention controls.

---

## 6. Security

We use industry-standard protections available through Android and Google Firebase, including encrypted transit (HTTPS / TLS) for network calls. No method of electronic storage or transmission is 100% secure. Please use a strong Google account password and keep your device updated.

---

## 7. Children’s Privacy

PlateVitals is **not directed at children under 13**. We do not knowingly collect personal information from children under 13. If you believe a child under 13 has provided us personal information, contact csavern@gmail.com and we will take reasonable steps to delete it.

Given the health- and CGM-related nature of the App, we recommend use by adults (18+) or under appropriate parental/guardian guidance where allowed by platform rules.

---

## 8. Your Rights and Choices

You may:

- **Sign out** in the App  
- **Revoke Health Connect permissions** in system / Health Connect settings  
- **Disable notifications** in Android settings  
- **Clear local app data** or uninstall the App  
- **Request account / cloud data deletion** by emailing **csavern@gmail.com** from the address associated with your account (include “PlateVitals data deletion” in the subject). We will take reasonable steps to delete Firebase Auth / Firestore data tied to your account, subject to technical and legal limits  

You can also manage Google account permissions at your Google Account security settings.

---

## 9. International Users

The App is developed for use primarily in the United States. If you use the App from elsewhere, your information may be processed in the United States or other locations where Google / Firebase operate.

---

## 10. Medical and Health Disclaimer

PlateVitals provides wellness, nutrition logging, and fitness-related displays only. It is **not** FDA-cleared or approved as a medical device. CGM, heart rate, blood pressure, SpO₂, sleep, and similar values may be incomplete, delayed, or inaccurate. **Do not use the App for emergency decisions or as a substitute for professional medical care.**

---

## 11. Changes to This Policy

We may update this Privacy Policy from time to time. The “Last updated” date at the top will change when we do. Continued use of the App after an update means you accept the revised policy. Material changes may also be noted in the App or store listing when practical.

---

## 12. Contact

**Vernon Bearss / PlateVitals**  
Email: **csavern@gmail.com**

For privacy questions, data access, or deletion requests, email the address above.
