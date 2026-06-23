# Vishing & Social Engineering

**Audience:** All YSE staff and volunteers  
**Last updated:** June 2026

---

## What Is Social Engineering?

Social engineering is manipulation, not hacking. Instead of exploiting software vulnerabilities, an attacker exploits **human psychology** (trust, authority, urgency, fear, or helpfulness) to get you to hand over information or take an action you otherwise would not.

Phishing (via email) is the most common form, but social engineering also happens over the phone, by SMS, through fake websites, and even in person. The techniques described in this guide require no technical skill on the attacker's part; only the ability to sound convincing.

---

## Vishing (Voice Phishing)

Vishing is social engineering conducted over a voice call. The attacker calls you, or tricks you into calling them, and impersonates a trusted party to extract credentials, personal information, or to get you to perform an action (e.g., approve a transfer, grant account access, share a one-time code).

### Common Vishing Scenarios

**IT support impersonation**

You receive a call from someone claiming to be from "Google support" or "Microsoft technical team." They say your account has been flagged for suspicious activity and they need to verify your identity. They ask for your password, a verification code, or ask you to grant remote access to your device.

!!! danger "Neither Google, Microsoft, nor YSE IT will ever call you to ask for your password or a verification code."
    Legitimate support teams do not initiate calls to request credentials. If you receive such a call, hang up and contact support@youthsecurity.org to verify.

**Colleague or leadership impersonation**

The caller claims to be a director, coordinator, or trusted colleague, possibly someone you know by name. They ask you to urgently approve something, share a document, reset an account, or make a payment. The urgency is deliberate: they want to prevent you from thinking carefully or verifying.

**External authority impersonation**

The caller claims to be from a government agency, law enforcement, a bank, or a partner organization. They present a scenario that requires immediate action on your part.

---

## AI Voice Cloning: A New and Serious Threat

Modern AI tools can clone a person's voice from as little as a few seconds of audio; publicly available material such as a recorded talk, a podcast appearance, a video interview, or a social media post is more than enough.

This means an attacker can call you and make it sound **exactly like your director, a trusted colleague, or a partner you know personally**. The voice will be familiar. It will match the person's accent, cadence, and tone.

!!! warning "Hearing a familiar voice is no longer sufficient proof of identity."
    If a call involves an unusual request (credentials, financial approval, access to accounts, urgent action), **verify through a separate channel**, regardless of how convincing the voice sounds.

**How to verify out-of-band:**

- Send a message to the person's known YSE Gmail address or Teams chat and ask them to confirm the call.
- Call them back on a number you already have stored. Do not use a number provided by the caller.
- Ask a colleague who knows the person to verify directly.

The few minutes this takes are worth it.

---

## Other Social Engineering Techniques

### Smishing (SMS Phishing)

Text messages with malicious links or urgent requests. SMS is particularly dangerous because:

- Messages feel more personal and immediate than email.
- URLs are harder to inspect on mobile screens.
- The `[EXT]` safeguards that protect your Gmail inbox do not apply to SMS.

Treat any unexpected SMS asking you to click a link, provide a code, or take urgent action with the same skepticism as a phishing email.

---

### Pretexting

The attacker constructs a believable backstory (a "pretext") before making contact. Examples:

- Spending days exchanging friendly emails to build trust before making a request
- Posing as a new volunteer asking innocent questions to map out YSE's structure, staff names, and processes: information that then enables more targeted attacks

Be thoughtful about how much organizational detail you share with people you cannot fully verify, even in seemingly innocent conversations.

---

### Quid Pro Quo

The attacker offers something (help, information, a resource) in exchange for access or credentials. For example, someone poses as IT support and offers to "fix a problem" with your account, asking you to share your screen or provide a verification code in return.

---

### Tailgating and In-Person Social Engineering

At events, conferences, or co-working spaces, an attacker may attempt to:

- Observe your screen or keyboard while you type credentials (shoulder surfing)
- Pose as a delegate or partner to extract information in conversation
- Leave USB drives or other physical media in hopes that someone picks them up and plugs them in. **Never plug in a USB drive you found or received unexpectedly.**

---

## Recognizing a Social Engineering Attempt

Across all channels and techniques, the same psychological levers keep appearing:

| Tactic | What it looks like | What to do |
|---|---|---|
| **Urgency** | "You need to act right now or lose access" | Slow down; urgency is manufactured to prevent verification |
| **Authority** | Impersonation of leadership, IT, government, or a known institution | Verify the person's identity through a separate channel |
| **Familiarity** | Use of your name, colleagues' names, internal details | These can all be gathered beforehand; familiarity is not proof of identity |
| **Fear** | "Your account has been compromised", "You will be fined" | Do not act on fear; report first, act after |
| **Helpfulness** | Caller offers to solve a problem you weren't aware you had | Unsolicited "help" requiring your credentials is almost always malicious |
| **Reciprocity** | Offers you something before making a request | The favour creates pressure to comply; recognize the pattern |

---

## What to Do During a Suspicious Call

1. **Stay calm.** You are not obligated to act immediately on any request, no matter how it is framed.
2. **Do not provide** passwords, one-time codes, or answers to security questions over the phone.
3. **Do not grant remote access** to your device to any unsolicited caller.
4. **If in doubt, end the call.** A polite "Let me verify this and call you back" is always appropriate. A legitimate caller will not object.
5. **Verify independently.** Use a contact method you already trust, not one provided by the caller.
6. **Report it.** Even if nothing was disclosed, let us know at **support@youthsecurity.org**.

---

## What to Do If You Were Targeted or Deceived

1. **Don't panic, and don't delay.** Report to **support@youthsecurity.org** immediately.
2. If you provided account credentials or a verification code, change your Google password now: [myaccount.google.com/security](https://myaccount.google.com/security).
3. If you granted remote access to your device, disconnect it from the internet and contact us before using it again.
4. Note everything you can recall: the caller's number, what was said, what information was shared, and the time of the call; include this in your report.

!!! warning "Do not let embarrassment delay your report."
    These attacks are specifically designed to bypass the defences of careful, intelligent people. Reporting quickly gives us the best chance to contain the damage.

---

## Quick Reference

| I received… | Red flag | Action |
|---|---|---|
| A call asking for my password or a verification code | Always | Refuse, hang up, report |
| A call from "IT support" I didn't initiate | High | Verify via support@youthsecurity.org before acting |
| A call from a familiar voice requesting urgent action | Possible AI voice clone | Verify out-of-band before acting |
| An SMS with a link or urgent request | High | Do not click; inspect carefully or report |
| An offer to "fix" my account remotely | Always | Refuse; report |
| A USB drive I didn't request | Always | Do not plug it in; report |

---

*To report an incident or suspicious contact, email **support@youthsecurity.org**. For guidance on email-based attacks, see the [Phishing Awareness Guide](phishing-awareness.md). For general incident reporting procedures, see the [Incident Reporting Guide](incident-reporting.md).*
