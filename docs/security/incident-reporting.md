# Incident Reporting

**Audience:** All YSE staff and volunteers  
**Last updated:** June 2026

---

## What Is a Security Incident?

A security incident is any event (or suspected event) that could compromise the confidentiality, integrity, or availability of YSE's information, accounts, or services.

You do **not** need to be certain that something bad has happened to report it. A strong gut feeling that something is wrong is enough. Reporting early costs nothing; reporting late can cause serious, hard-to-reverse damage.

---

## Examples of Incidents

The list below is not exhaustive. When in doubt, report it.

### Account & Access Incidents

| Situation | Example |
|---|---|
| **Unauthorized access** | You notice a sign-in to your Google or Microsoft account from a location or device you don't recognize |
| **Credential compromise** | You accidentally typed your password into a phishing page, or your password appeared in a data breach |
| **Account lockout** | You are unexpectedly locked out of your Google Workspace or Microsoft 365 account |
| **Suspicious account activity** | Emails you didn't send appearing in your Sent folder; calendar events you didn't create; files you didn't share showing as shared |

### Device Incidents (Your Personal Device)

Because YSE does not manage devices, **your personal phone, laptop, or tablet is part of YSE's security perimeter** when you use it to access Google Workspace or Microsoft 365. Incidents on your device can affect the whole organization.

| Situation | Example |
|---|---|
| **Lost or stolen device** | A phone or laptop with an active YSE session (Gmail, Teams, OneDrive) is lost or stolen |
| **Malware or ransomware** | Your device starts behaving strangely after opening an attachment or visiting a website; antivirus flags a threat |
| **Unauthorized access to your device** | Someone else has accessed your device and may have seen or interacted with YSE accounts |

### Data Incidents

| Situation | Example |
|---|---|
| **Accidental data exposure** | You shared a Google Drive file or SharePoint document with the wrong person or made it publicly accessible |
| **Unintended disclosure** | A YSE document containing personal data (e.g., a list of members, donors, or beneficiaries) was sent to the wrong email address |
| **Data loss** | Important files in Google Drive or SharePoint/OneDrive have been deleted or have disappeared |

### Service & Communication Incidents

| Situation | Example |
|---|---|
| **Phishing targeted at YSE** | You received a phishing email impersonating a colleague, YSE itself, or a partner, especially one that others may have received too |
| **Suspicious third-party app access** | You notice an unfamiliar app has been granted permission to your Google or Microsoft account |
| **Account takeover attempt** | You receive multi-factor authentication (MFA) prompts you did not initiate (push notifications, SMS codes): someone may be trying to log in as you |

!!! warning "MFA prompts you didn't request are a red flag."
    If you receive a Google authentication request out of the blue (a push notification, a code by SMS, or a prompt in the Authenticator app), **deny it immediately** and report it. Someone has your password and is trying to use it. Because Microsoft 365 access is federated through Google, a compromised Google account also means compromised access to Teams, SharePoint, and OneDrive.

---

## How to Report an Incident

**Email:** [support@youthsecurity.org](mailto:support@youthsecurity.org)

Report as soon as possible. You do not need to investigate first or have all the answers: just tell us what you observed and when.

### What to Include in Your Report

The more context you can provide, the faster the team can respond. Include as many of these as you can:

- **What happened**: describe what you saw, received, or noticed
- **When it happened**: date and approximate time (time zones help)
- **Which account or service is affected**: Google Workspace, Microsoft 365, or both
- **Which device was involved**: type (phone, laptop) and operating system if known
- **What you did next**: did you click a link, enter a password, deny an MFA prompt?
- **Your general location**: city and country where you have been recently (e.g. "Zurich, Switzerland"). If you suspect unauthorized access, the IT admin will review your account's sign-in history; knowing your legitimate locations makes it much easier to spot access from unexpected regions.
- **Any screenshots or forwarded emails**: attach them if you have them

!!! tip "You can report even if you're unsure."
    "I think something might be wrong with my account" is a valid incident report. We would always rather investigate a false alarm than miss a real compromise.

---

## What Happens After You Report

1. **Acknowledgement**: you will receive a reply confirming your report has been received.
2. **Assessment**: the IT admin will review the situation and determine the scope and severity.
3. **Containment**: if needed, affected accounts or sessions will be secured (e.g., forced sign-out, password reset, app permission revocation).
4. **Follow-up**: you will be kept informed of what was found and any actions you need to take on your end.

All reports are handled confidentially.

---

## Immediate Actions While You Wait

If you believe an account has been compromised **right now**, do not wait for a reply; take these steps immediately and then report.

### If your Google Workspace account is affected

1. Go to [myaccount.google.com/security](https://myaccount.google.com/security).
2. Under **"Your devices"**, review active sessions and sign out of any you don't recognize.
3. Change your Google password.
4. Confirm that 2-Step Verification is enabled.

### If your Microsoft 365 account is affected

Your Microsoft 365 account is accessed through your Google Workspace identity; you sign in to Teams, SharePoint, and OneDrive using your YSE Google account. There is no separate Microsoft password.

This means:

- **Securing your Google account also secures your Microsoft 365 access.** Follow the Google steps above first.
- If you suspect someone has accessed Teams, SharePoint, or OneDrive without your knowledge, report it and the IT admin can review Microsoft 365 sign-in logs on your behalf.
- You can review recent Microsoft 365 activity yourself at [mysignins.microsoft.com](https://mysignins.microsoft.com): sign in with your YSE Google account when prompted.

### If your device is lost or stolen

1. Use Google's Find My Device ([google.com/android/find](https://google.com/android/find)) or Apple's Find My ([icloud.com/find](https://www.icloud.com/find)) to locate or remotely lock your device.
2. Report to us immediately so we can revoke YSE account sessions on that device. This prevents anyone who has the device from accessing your Google or Microsoft data.

!!! danger "Do not delay reporting a lost or stolen device."
    Even if the device is locked with a PIN, an active Google or Microsoft session may be accessible. The IT admin can remotely revoke those sessions, but only after you report it.

---

## Quick Reference

| I noticed… | Report? | Immediate action |
|---|---|---|
| Sign-in from unknown location | Yes | Sign out all devices via account security settings |
| MFA prompt I didn't request | Yes | Deny the prompt immediately |
| Emails I didn't send in my Sent folder | Yes | Change password immediately |
| File shared with wrong person | Yes | Revoke sharing permissions in Drive/SharePoint |
| Lost or stolen device with active YSE session | Yes | Lock device remotely; report for session revocation |
| Unexpected app with account access | Yes | Revoke the app's permissions in account settings |
| Suspicious email targeting YSE | Yes | Report phishing in Gmail; warn the team |

---

*To report an incident, email **support@youthsecurity.org**. For guidance on recognizing phishing, see the [Phishing Awareness Guide](phishing-awareness.md).*
