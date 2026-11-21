# Privacy Policy for PlateVitals

**Last updated:** November 21, 2026 (app version 1.0.33)  
**Developer:** Vernon Bearss (doing business as PlateVitals)  
**Contact:** csavern@gmail.com  
**App:** PlateVitals (Android package `com.vern.diettracker`)  
**Consumer Health Data Privacy Policy (Washington, Nevada, Connecticut):** https://txvern.github.io/platevitals-legal/consumer-health-data.html  
**Delete your account:** see [How to delete your account and data](#delete-account)

This Privacy Policy explains what PlateVitals (“we,” “us,” or “the App”) collects, why, where it is stored, who it is shared with, and how you can delete it.

**PlateVitals is a wellness and fitness tracking tool for adults 18 and older. It is not a medical device and does not diagnose, treat, cure, or prevent any disease or medical condition. Always ask a qualified healthcare professional for medical advice. Glucose readings shown in the App (for example from an Abbott Lingo sensor through Health Connect) may be delayed and are for personal wellness awareness only.**

---

## 1. Information we collect

### 1.1 Account
When you sign in with Google (or create an email account in the App) we collect your name, email address, a Google / Firebase account ID and, if Google provides it, your profile photo address. These are used to sign you in and to back up your data to your account.

### 1.2 Profile, wellness goals and logs (you enter them)
- Profile details: age, sex, height, weight, waist, activity level, calorie / Protein / Carbohydrate / Fat / water / step goals and diet style (for example Keto, Low Glycemic / Low Carb, Low Sodium / DASH-Style).
- **Wellness goals you choose** (optional): Blood Sugar Awareness / Low Carb, Low Sodium, Heart-Healthy Eating, Weight Loss & Portion Control. These only change your suggested nutrition targets. Because they can reveal something about your health, we treat them as consumer health data.
- Meal and food logs, water, glucose readings you type in, weight and waist entries, habit check-offs and reminder times.
- Your one-time consent to health data use and your 18-or-older confirmation (with the date and time).

### 1.3 Health Connect (only with your permission)
If you connect Android Health Connect and grant permission, PlateVitals **reads** (it never writes) these six data types, and only to show them in the App:

| Health Connect data | Where you see it in the App |
|---|---|
| Steps | Daily Step Counter |
| Active calories burned | Calorie Summary Ring (calories left today) |
| Heart rate | Heart Rate card |
| Weight | Weight card and your calorie targets |
| Blood glucose | Glucose card, Glucose detail screen and Trends |
| Oxygen saturation (blood oxygen) | Blood Oxygen card |

Reads cover today (glucose: the last 48 hours). PlateVitals does not read Health Connect in the background and does not read blood pressure, sleep or resting heart rate. You can turn permissions off at any time in Health Connect or Android settings, or with Disconnect in the App.

**Health Connect Limited Use.** PlateVitals' use of information received from Health Connect follows the Health Connect Permissions policy, including its Limited Use requirements. Health Connect data is used only to provide the dashboard features you see; it is never used for advertising, never sold, never used to train AI models, never sent to Google Gemini, and is not read by people except with your permission, for security, or when the law requires it.

### 1.4 Phone step sensor
If Health Connect steps are not available, PlateVitals can count steps with your phone's built-in step sensor. Android asks for the **Physical activity** permission first. The step count stays in the App like other step data (see section 3).

### 1.5 Meal photos and food text (AI estimates)
When you use AI plate photo scan or typed AI food search, the photo (resized on your phone) or the text you typed is sent to **Google Gemini** (Google's Generative Language API) to estimate the food and its nutrition. No health readings, name, email or account ID are sent with it. PlateVitals does not keep a copy of the photo after the estimate.  
PlateVitals currently uses Gemini's **free (unpaid) service**. Under Google's terms for that service, **Google may use the photos and text sent to it to improve Google products, and Google staff may review them**. Please do not scan photos that show people, documents or other personal details. If this changes (for example to Google's paid service, where submissions are not used to improve Google products), we will update this policy.

### 1.6 Barcodes
When you scan a barcode, only the barcode number is sent to **Open Food Facts** (a free public food database) to look up the product's nutrition label. Nothing else about you is sent.

### 1.7 Membership purchases (Google Play Billing)
The membership ($4.99 a month in the United States) is sold and billed only by **Google Play**. We never see your card or bank details. Google Play tells the App whether your subscription is active and gives it a purchase token and order ID, which we store with your account so your membership works after a reinstall or on a new phone.

### 1.8 Device and technical data
The App uses the app version and Android version shown in Settings, Firebase sign-in tokens, and your notification permission status. Reminders are **local notifications** created on your phone; we do not run push-notification or advertising services. The App has no ad, analytics or crash-reporting SDKs.

---

## 2. How we use information
- Sign you in, back up your data and restore it on reinstall or a new phone.
- Show your dashboard, goals, history, Trends and Health Connect readings.
- Estimate food nutrition from photos, text or barcodes when you ask.
- Send the reminders you turn on, at the times you choose.
- Check and restore your Google Play membership.
- Keep the App secure and answer your support requests.

We do **not** sell personal information, do **not** show ads, and do **not** share health data with advertisers or data brokers.

---

## 3. Where your data is stored
- **On your phone:** everything you log, your profile and settings are stored in the App's private storage on your phone.
- **In your PlateVitals account (only if you sign in):** a copy of your profile, wellness goals, meals, water, reminders and habits, your glucose readings, and the daily steps, active calories burned, weight and heart rate shown on your dashboard (including up to 60 days of daily history) is saved in **Google Firebase** (Firebase Authentication and Cloud Firestore, in the United States). This backup is what brings your data back after a reinstall. Blood oxygen readings are shown but not saved to your account.
- **Health Connect:** the original records stay in Health Connect and the apps that wrote them (for example Lingo or Samsung Health). PlateVitals keeps only the copies described above.

Data is encrypted in transit (HTTPS/TLS). Google encrypts Firebase data at rest. Data on your phone is protected by your phone's own encryption and lock screen.

---

## 4. Who we share data with
| Recipient | What | Why |
|---|---|---|
| Google Firebase (Authentication, Cloud Firestore) | Account details and the backup in section 3 | Sign-in and backup (our service provider) |
| Google Gemini API | Meal photo or food text you choose to analyze | Nutrition estimate (see section 1.5 about Google's use on the free service) |
| Open Food Facts | Barcode number only | Product nutrition lookup |
| Google Play | Your purchase (handled by Google) | Membership billing and subscription status |
| Android Health Connect | Read requests you approve | Show your readings |

We may also disclose information if the law requires it or to protect someone's safety. If PlateVitals is ever sold or merged, we will tell you before your data is handled under a different policy.

---

<a id="delete-account"></a>

## 5. How to delete your account and data

### In the App (fastest)
1. Open PlateVitals and tap **Settings** (bottom bar).
2. Open **Account** and tap **Delete account**.
3. Read what will be deleted and tap **Delete everything**. If Android asks you to choose your Google account again, do so; Google requires a recent sign-in before an account can be deleted.

This immediately deletes your PlateVitals cloud backup (Cloud Firestore), your PlateVitals sign-in (Firebase Authentication account), and everything PlateVitals stored on your phone, and turns off its reminders.

### Without the App (by email)
Email **csavern@gmail.com** from the email address you use with PlateVitals, with the subject **“PlateVitals account deletion”**. We will confirm your request within 7 days and delete your account and cloud data within **30 days**, then email you when it is done.

### What is deleted and what is kept
- **Deleted:** your account, profile, wellness goals, meals, glucose, steps, weight, heart rate, water, reminders, habits, consent record and membership record held by PlateVitals.
- **Not deleted by PlateVitals:** records in Health Connect and in the apps that wrote them (delete those in Health Connect); your Google Play purchase history, which Google keeps under its own policies; and emails you sent us, which we keep only as long as needed to answer you and show that we handled your request.
- Google may keep encrypted backup copies of Firebase data for a short period under its own retention schedule before they are permanently erased.
- **Deleting your account does not cancel a Google Play subscription.** Cancel it in the Google Play Store app → Profile → Payments & subscriptions → Subscriptions.

You can also remove only part of your data at any time: delete individual meals in the App, disconnect Health Connect, or sign out and clear the App's storage in Android settings.

---

## 6. How long we keep data
- On your phone: until you delete it, delete your account, clear the App's storage or uninstall.
- In your account: while your account exists. Inactive accounts are kept until you delete them.
- Gemini and Open Food Facts requests are not stored by PlateVitals.

---

## 7. Age requirement (18+ only)
PlateVitals is for **adults 18 and older only**. You must confirm you are 18 or older before adding health data. We do not knowingly collect information from anyone under 18. If you believe someone under 18 is using PlateVitals, email csavern@gmail.com and we will delete their data.

---

## 8. Your choices and rights
- See and change your data in the App at any time.
- Withdraw Health Connect access in Health Connect or with Disconnect.
- Turn reminders off in Settings → Reminders, or block notifications in Android settings.
- Delete your account and data (section 5).
- Ask for a copy of your data, a list of the companies we share it with, or a correction by emailing csavern@gmail.com. We answer within 45 days.
- Residents of Washington, Nevada and Connecticut have additional rights over consumer health data; see the **Consumer Health Data Privacy Policy**: https://txvern.github.io/platevitals-legal/consumer-health-data.html

---

## 9. Where we operate
PlateVitals is offered in the United States, and data is processed in the United States by Google.

---

## 10. Medical and health disclaimer
PlateVitals shows wellness, nutrition and fitness information only. It is **not** cleared or approved by the FDA as a medical device. Glucose, heart rate, blood oxygen and similar readings may be delayed, incomplete or wrong, and AI nutrition estimates can be wrong. **Do not use the App for emergencies or medical decisions. In an emergency call 911.**

---

## 11. Changes to this policy
When we change this policy we update the date at the top. If a change is significant, for example a new kind of data or a new company we share with, we will show a notice in the App before it applies and ask for your consent again where the law requires it.

---

## 12. Contact
**Vernon Bearss / PlateVitals** · Email: **csavern@gmail.com**
