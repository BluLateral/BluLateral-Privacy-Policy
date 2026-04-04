PRIVACY POLICY

Effective Date: 04/04/2026

BluTapp, Inc. ("BluLateral," "we," "us," or "our") provides the BluLateral mobile application (the "App"). This Privacy Policy explains what data the App collects, how we use it, how long we keep it, how it is deleted, and when it is shared.

## 1. Information We Collect

### 1.1 Data Stored Locally on Your Device

The App stores limited data on your device so it can operate and resume sessions. This local data may include:

- a display name entered in the App
- your selected role (participant/client or facilitator/therapist)
- the current active session code
- an optional facilitator end-of-session message

The App does not require an end-user account and does not collect email addresses, payment information, survey responses, or personal login credentials through normal App use.

### 1.2 Live Session Data

During an active session, the App sends session data through our EMQX MQTT service so devices can join, rejoin, and stay in sync. This data may include:

- the session code
- the display name entered in the App
- a device identifier used by the App
- app version information
- device and tapper status, including pairing state
- facilitator session-control settings such as speed, intensity, identify commands, and any optional end-of-session message

We use this data only to operate live sessions and keep connected devices synchronized.

### 1.3 Analytics and Crash Diagnostics

In release versions of the App, we use Google Analytics for Firebase and Firebase Crashlytics. These services may collect pseudonymous technical data, including:

- Firebase app or installation identifiers
- Crashlytics installation UUIDs
- device model, operating system version, app version, language, and similar device information
- app usage events and high-level usage metrics
- crash logs, stack traces, and diagnostic information
- approximate location inferred by Google from IP address
- advertising identifiers where permitted by the device, platform, and Google/Firebase settings

The App does not set a Google Analytics user ID, does not set Firebase Analytics custom user properties, and does not set a Crashlytics user identifier. We do not intentionally send your display name, raw session code, or custom end-of-session message to Google Analytics or Crashlytics. We do not intentionally collect precise GPS location through the App.

## 2. How We Use Data

We use data to:

- operate the App and live sessions
- allow participants to join, rejoin, and resume sessions
- keep session state synchronized across devices
- understand high-level App usage and improve the App
- diagnose crashes, bugs, and connectivity issues
- protect the security and integrity of the App
- comply with legal obligations

## 3. How We Share Data

We share data only as needed to provide the App:

- with Google, for Google Analytics for Firebase and Firebase Crashlytics
- with our EMQX MQTT service, which transmits live session data and retains the latest session command and status messages so devices can join or rejoin with current session state
- with service providers, advisors, or authorities when reasonably necessary to comply with law, protect rights or safety, or enforce our policies
- in connection with a merger, financing, acquisition, or sale of business assets

We do not sell personal data. We do not use EMQX rules, bridges, or exports to copy session payloads into separate analytics or storage systems.

## 4. Data Retention

We retain different categories of data for different periods:

- Active session code stored locally on the device: until the session ends, at which point the App clears it from local storage.
- Display name, selected role, and saved facilitator end-of-session message stored locally on the device: until you delete the App or clear the App's local storage.
- EMQX retained session messages: the latest retained session command and status messages for each session topic remain in the broker until they are overwritten or manually deleted. These retained messages can include the session code, display name, device identifier, device status, session-control settings, and optional end-of-session message.
- Google Analytics for Firebase data: 2 months.
- Firebase Crashlytics data: 90 days before removal begins, according to Firebase documentation.
- We may retain limited data longer if required by law, to investigate abuse, or to protect the security of the App.

## 5. How Data Is Deleted

Because the App does not use end-user accounts, there is no separate account-deletion flow. Data can be deleted in the following ways:

- End the active session to clear the locally stored active session code.
- Delete the App or clear the App's local storage to remove the locally stored display name, selected role, and saved end-of-session message.
- Email `info@blulateral.com` to request deletion of retained MQTT broker session data we control. To help us locate the data, please include the session code and the approximate session date and time.
- Google Analytics for Firebase and Firebase Crashlytics data are deleted by Google according to the retention periods and controls described above and in Google's policies.

## 6. Your Choices

- You may limit certain advertising identifiers through your mobile operating system settings.
- If you do not want local App data to remain on your device, delete the App or clear its local storage after use.
- If you want retained MQTT broker session data deleted, contact us using the email address below.

## 7. Data Security

We use reasonable administrative, technical, and organizational measures to protect data. No method of transmission or storage is completely secure, and we cannot guarantee absolute security.

## 8. International Data Transfers

Our service providers, including Google/Firebase and our MQTT infrastructure providers, may process data in countries other than your own, including the United States. Where required, we rely on applicable contractual and legal safeguards for those transfers.

## 9. Children's Privacy

The App is not intended for children under 13, or a higher minimum age where required by local law. We do not knowingly collect personal data from children in violation of applicable law. If you believe a child provided personal data to us, contact `info@blulateral.com` and we will take reasonable steps to address it.

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will post the updated version and revise the Effective Date above. Continued use of the App after the updated policy takes effect means you accept the revised policy.

## 11. Contact

Email: `info@blulateral.com`

Website: `https://www.blulateral.com/support`
