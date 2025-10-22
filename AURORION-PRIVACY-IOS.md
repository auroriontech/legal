# Privacy Policy - Aurorion iOS App

**Last Updated: October 21, 2025**

**Company:** Aurorion Tech Ltd
**Registered in Scotland:** SC835759
**Registered Office:** 4 Shadepark Gardens, Dalkeith, Scotland, EH22 1BX

## Introduction

Aurorion Tech Ltd ("we", "us" or "our") respects your privacy and is committed to protecting your personal data. This privacy policy explains how we collect, use, store, and protect your personal information when you use the Aurorion mobile application ("App") for iOS devices.

This policy is written in accordance with:
- UK General Data Protection Regulation (UK GDPR)
- Data Protection Act 2018 (DPA 2018)
- Privacy and Electronic Communications (EC Directive) Regulations 2003 (PECR 2003)

When we collect and use your personal data as described in this policy, we act as the data controller under UK GDPR.

## Important Information About Children

The App is intended for users aged 13 and older. If you are under 18, you must have parental or guardian consent to use the App.

We do not knowingly collect or store personal data from children under 13. If we become aware that we have collected personal data from a child under 13, we will delete that information as quickly as possible. Parents or guardians may contact us at privacy@aurorion.app to request deletion of data concerning their child.

## What Personal Data We Collect

### 1. Voice Data and Transcription

**What we collect:** The App uses on-device speech recognition to transcribe your voice into text.

**What we do NOT collect:** We do **not** record, store, or transmit your voice audio. All voice processing happens locally on your device using Apple's Speech Recognition framework.

**What we DO transmit:** Only the text transcription (not voice recordings) may be transmitted to:
- Our servers for processing
- Third-party AI service providers (Azure OpenAI) for generating conversational tour responses

**Legal basis:** Consent and legitimate interest in providing tour guidance services.

### 2. Location Data

**What we collect:**
- GPS coordinates (latitude, longitude)
- Address information including:
  - Street name and number
  - City/town (locality)
  - County/council area
  - State/region (administrative area)
  - Country
  - Postal code

**How we use it:**
- Provide location-specific tour information and guidance
- Identify nearby points of interest
- Deliver contextual responses based on your current location
- Generate personalized tour experiences

**Where it's sent:**
- Our servers (Cloudflare infrastructure)
- AI service providers for generating location-aware tour content

**How long we keep it:**
- Real-time location data is used immediately and not retained
- Location data stored as part of your tour history is retained until you delete it or 30 days after pass expiry

**Legal basis:** Consent and performance of our contract with you to deliver location-based tour services.

### 3. User Account Data

**What we collect:**
- Email address and authentication credentials
- Profile information you provide
- Tour history
- Conversation messages with tour guides/characters

**How we use it:**
- Create and manage your account
- Authenticate you when you use the App
- Synchronize your data across devices
- Provide customer support

**Where it's stored:**
- Locally on your device (SwiftData and Keychain)
- In our cloud backend (Cloudflare D1 database and R2 storage)

**How long we keep it:**
- Active accounts: Until you delete your account
- Inactive accounts: We may delete accounts after extended periods of inactivity
- Tour data: Automatically deleted or anonymized 30 days after pass expiry

**Legal basis:** Performance of our contract with you and legitimate interest in providing account-based services.

### 4. Usage and Diagnostic Data

**What we collect:**
- Error logs and crash reports
- App usage statistics (features used, session duration)
- Device information (device model, operating system version, app version)
- Performance metrics

**How we use it:**
- Improve app functionality
- Identify and fix technical issues
- Enhance user experience
- Understand how users interact with the App

**Legal basis:** Legitimate interest in improving our service and fixing technical issues.

## How We Use Your Data

### Internal Review of Tour Data

We review tour history and conversation data for:

1. **Compliance:** Ensuring content adheres to our community guidelines and legal requirements
2. **Safety:** Identifying and addressing potentially harmful or inappropriate content
3. **Service Improvement:** Analyzing usage patterns to enhance tour quality and app features

This internal review is conducted by Aurorion staff and automated systems. Your personal information is handled in accordance with UK GDPR data protection standards.

**Legal basis:** Legitimate interest in maintaining a safe platform and improving our services, balanced against your privacy rights.

### Partner Institution Data Sharing

**Important:** If you use tours featuring guides or characters provided by partner institutions (such as museums, universities, or cultural organizations), we may share your tour history and conversation data with that specific partner institution.

**What we share:**
- Tour history and conversation data **only for tours involving their specific guides or characters**
- Tours with other guides/characters are **not** shared with that institution
- General tours without institutional partnerships are **not** shared with any third party

**How partners use this data:**
- Improve their content quality
- Understand visitor engagement
- Enhance their tour offerings

**Your rights:** You have the right to object to this sharing. Contact privacy@aurorion.app to exercise this right.

**Disclosure:** Data sharing with partners is clearly disclosed when you select their guides or characters.

**Legal basis:** Legitimate interest in enabling partner institutions to improve their content, with your informed consent when selecting their guides/characters.

## Third-Party Service Providers

The App integrates with the following third-party services:

### Azure OpenAI
- **Purpose:** AI-powered conversation processing for tour narration
- **Data shared:** Text transcriptions, conversation history, location context
- **Location:** Data may be processed in the EEA and/or USA
- **Safeguards:** Data processing agreements ensuring UK GDPR compliance

### Azure Text-to-Speech
- **Purpose:** Voice synthesis for spoken tour responses
- **Data shared:** Text responses to be converted to speech
- **Location:** Data may be processed in the EEA and/or USA
- **Safeguards:** Data processing agreements ensuring UK GDPR compliance

### Cloudflare
- **Purpose:** Cloud backend, database (D1), and file storage (R2)
- **Data shared:** All account data, tour history, conversation messages
- **Location:** Data may be stored in the EEA and/or USA
- **Safeguards:** Cloudflare complies with UK GDPR through approved data transfer mechanisms

### Apple Services
- **Purpose:** Speech Recognition, Apple TTS, Sign in with Apple
- **Data shared:** Voice audio (processed locally), account authentication
- **Location:** Processed on-device or in Apple's infrastructure
- **Safeguards:** Apple's privacy commitments and UK GDPR compliance

All third-party processors act under data-processing agreements that ensure equivalent data protection standards in compliance with UK GDPR requirements.

**Data Sharing Limitation:** Except for the service providers listed above and partner institutions (as described earlier), we do **not** sell, rent, or share your personal data with third parties.

## International Data Transfers

Your personal data may be transferred to and processed in countries outside the UK, including:

- **European Economic Area (EEA):** Adequate level of protection under UK GDPR
- **United States:** Transfers are made under approved mechanisms (e.g., adequacy decisions, standard contractual clauses)

We ensure all international transfers comply with UK GDPR Article 45 requirements.

### Remote Working

Our founders and team members occasionally work while traveling outside the UK. Remote access to your data is strictly controlled:
- Encrypted connections (VPN or HTTPS) for all remote access
- Password protection and multi-factor authentication
- Strict "need-to-know" policy limiting access to authorized personnel only

## Data Security

We implement technical and organizational security measures including:

- **Encryption:** Data encrypted at rest (in databases) and in transit (TLS/HTTPS)
- **Secure Storage:** Keychain storage for sensitive credentials on your device
- **Access Controls:** Multi-factor authentication (MFA) for production systems
- **Least-Privilege Access:** Only employees with genuine business need can access your data
- **Secure Sharing:** Internal documents containing personal data are encrypted and password-protected
- **No Direct Third-Party Access:** Service providers process data on our written instructions only
- **Incident Response:** We maintain and test a data-breach response plan

However, no method of transmission or storage is 100% secure, and we cannot guarantee absolute security.

### Data Breach Notification

If we become aware of a personal data breach that poses a risk to your rights and freedoms, we will notify:
- The Information Commissioner's Office (ICO) without undue delay
- You directly, where required, with information about the breach and steps to protect yourself

## Data Retention

| Data Type | Retention Period |
|-----------|------------------|
| Tour data and conversation history | Until you delete them, or 30 days after pass expiry (automatically deleted/anonymized) |
| Account data | While your account is active |
| Diagnostic/crash logs | Up to 90 days |
| Location data in tour history | Until you delete the tour, or 30 days after pass expiry |
| Real-time location data | Not retained (used immediately) |

You may request deletion of your data at any time by contacting privacy@aurorion.app.

## Your Rights Under UK GDPR

You have the following rights regarding your personal data:

### 1. Right of Access
Request a copy of the personal data we hold about you, including:
- What data we have
- How we're using it
- Who we've shared it with (including which partner institutions, if any, have received your tour data)

### 2. Right to Rectification
Request correction of inaccurate or incomplete data.

### 3. Right to Erasure ("Right to be Forgotten")
Request deletion of your personal data in certain circumstances:
- The data is no longer necessary for the purpose it was collected
- You withdraw consent (where processing is based on consent)
- You object to processing and there are no overriding legitimate grounds
- The data has been unlawfully processed

### 4. Right to Restrict Processing
Request limitation of how we process your data in certain situations:
- You contest the accuracy of the data
- Processing is unlawful but you don't want erasure
- We no longer need the data but you need it for legal claims
- You've objected to processing pending verification of legitimate grounds

### 5. Right to Data Portability
Receive your data in a structured, commonly used, machine-readable format and transfer it to another controller.

### 6. Right to Object
Object to processing based on legitimate interests, including:
- Internal review of tour data for compliance, safety, or improvement purposes
- Sharing data with partner institutions
- Direct marketing (you have an absolute right to object to marketing)

### 7. Right to Withdraw Consent
Where processing is based on consent, you can withdraw consent at any time. This does not affect the lawfulness of processing before withdrawal.

### 8. Right to Lodge a Complaint
If you're not satisfied with our response, you have the right to lodge a complaint with the Information Commissioner's Office (ICO), the UK's data protection authority:

**ICO Contact:**
- Website: www.ico.org.uk
- Helpline: 0303 123 1113
- Address: Information Commissioner's Office, Wycliffe House, Water Lane, Wilmslow, Cheshire, SK9 5AF

## Exercising Your Rights

To exercise any of these rights:

1. **Email us:** privacy@aurorion.app
2. **Provide:**
   - Your name and contact information
   - Description of your request
   - Proof of identity (to prevent unauthorized access)

**Response time:** We will respond within 30 days in accordance with UK GDPR requirements.

**No fee:** You will not be charged a fee unless your request is clearly unfounded, repetitive, or excessive.

## Legal Basis for Processing

We process your personal data under the following legal bases:

1. **Consent:** You provide explicit consent (e.g., accepting our terms, enabling location services)
2. **Contract:** Processing is necessary to perform our contract with you (delivering tour services)
3. **Legal Obligation:** Processing is necessary to comply with legal requirements
4. **Legitimate Interests:** Processing is necessary for our legitimate interests, provided your rights do not override these interests:
   - Service improvement
   - Fraud prevention
   - Content safety and compliance
   - Enabling partner institutions to improve their content
   - Network and information security

## Cookies and Tracking

The Aurorion iOS App does **not** use cookies or tracking technologies. All data collection is as described in this policy.

## Changes to This Privacy Policy

We may update this privacy policy from time to time. We will notify you of material changes by:
- Posting the updated policy within the App
- Updating the "Last Updated" date
- Sending notification through the App or email

Your continued use of the App after changes constitutes acceptance of the updated policy.

## Third-Party Links

The App may contain links to third-party websites or services. We are not responsible for the privacy practices of these third parties. We encourage you to read their privacy policies.

## Contact Us

If you have questions about this privacy policy or how we handle your data:

**Privacy Inquiries:**
- Email: privacy@aurorion.app

**General Support:**
- Email: support@aurorion.app
- Website: https://aurorion.app

**Postal Address:**
Aurorion Tech Ltd
4 Shadepark Gardens
Dalkeith, Scotland
EH22 1BX
United Kingdom

---

**Your Consent**

By using the Aurorion iOS App, you acknowledge that you have read and understood this Privacy Policy and consent to the collection, use, and disclosure of your personal information as described herein.

---

Copyright © 2025 Aurorion Tech Ltd. All rights reserved.
