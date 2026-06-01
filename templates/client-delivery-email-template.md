# Client Delivery Email Template
**Aerial Professional Services LLC**
Last updated: 2026-06-01

---

## Overview

Use these templates when delivering final project files to clients via Synology Drive share link.
Each client receives a **unique, private link** generated specifically for their project.
No shared portal. No public file directory.

The public-facing delivery information page (for client reference) is:
`https://aerialprofessionalservices.com/client-deliveries`

Actual delivery links follow the format:
`https://files.aerialprofessionalservices.com/d/s/XXXXXXXX`

---

## Placeholders Reference

| Placeholder | Description |
|---|---|
| `[CLIENT NAME]` | Client's first name or full name |
| `[PROJECT NAME]` | Short project identifier (e.g., "Roof Inspection — 1234 Mesa Ave") |
| `[PROJECT LOCATION]` | City, address, or site description |
| `[DELIVERY LINK]` | Full Synology Drive share URL |
| `[PASSWORD]` | Share password if link is protected |
| `[EXPIRATION DATE]` | Date the link expires, if applicable (e.g., "July 15, 2026") |
| `[FILES INCLUDED]` | List of file types delivered (e.g., "32 aerial photos, 1 edited video") |
| `[NOTES]` | Any project-specific instructions or context |
| `[YOUR NAME]` | Sender name (Alex Stoen) |

---

## Subject Line Options

Use whichever fits the project type. Keep it specific — clients recognize their project faster.

```
Your aerial photos are ready — [PROJECT NAME]
```
```
[PROJECT NAME] — delivery files ready for download
```
```
Project files ready: [PROJECT NAME]
```
```
Your drone footage is ready — [PROJECT NAME]
```
```
Aerial Professional Services — delivery: [PROJECT NAME]
```

> **Recommended default:** `Your aerial photos are ready — [PROJECT NAME]`
> For video-primary deliveries, use the footage variant.

---

## 1 — Primary Email Template

> Use for all standard final deliveries.

---

**Subject:** Your aerial photos are ready — [PROJECT NAME]

---

Hi [CLIENT NAME],

Your project files are ready for download.

**Project:** [PROJECT NAME]
**Location:** [PROJECT LOCATION]

**Your delivery link:**
[DELIVERY LINK]

<!--
  If link is password-protected, include this block.
  If no password, delete the Password line entirely.
-->
**Password:** [PASSWORD]

---

**What's included:**
[FILES INCLUDED]

*Example: 28 full-resolution aerial photographs, edited and color-corrected. 1 highlight video, 4K MP4.*

---

**A few things to know:**

- Files are hosted on our private secure delivery server.
- Please **download and save your files** at your earliest convenience.
- This link [expires on [EXPIRATION DATE] / is available indefinitely — choose one].
- If you have any trouble accessing your files, reply to this email or text us at (719) 308-0513.

[NOTES]

*Example notes: "The video export is 2.1 GB — allow a few minutes for the download to complete."*
*Or omit this section entirely if there are no special instructions.*

---

It was a pleasure working on this project. If you need additional shots, a different format, or have any questions about the files, don't hesitate to reach out.

Alex Stoen
**Aerial Professional Services LLC**
FAA Part 107 Certified · $1M Insured · Veteran-Owned
(719) 308-0513 · info@aerialprofessionalservices.com
https://aerialprofessionalservices.com

---

## 2 — Short Version

> Use when the client is expecting the files, has already been briefed on the process, or for repeat clients who don't need full context.

---

**Subject:** [PROJECT NAME] — files ready

---

Hi [CLIENT NAME],

Files are ready for [PROJECT NAME].

**Download link:** [DELIVERY LINK]
**Password:** [PASSWORD] *(delete if not applicable)*

Includes: [FILES INCLUDED]

Link expires: [EXPIRATION DATE] *(delete if not applicable)*

Questions? Reply here or text (719) 308-0513.

— Alex
Aerial Professional Services

---

## 3 — Follow-Up / Replacement Link

> Use when a client reports their original link has expired, was not received, or needs to be regenerated.

---

**Subject:** Re: [PROJECT NAME] — replacement delivery link

---

Hi [CLIENT NAME],

No problem — here is a new delivery link for your project files.

**Project:** [PROJECT NAME]
**New delivery link:** [DELIVERY LINK]
**Password:** [PASSWORD] *(delete if not applicable)*
**Link expires:** [EXPIRATION DATE]

If you continue to have trouble, reply to this email or text us at (719) 308-0513 and we will get you sorted out.

Alex Stoen
**Aerial Professional Services LLC**
(719) 308-0513 · info@aerialprofessionalservices.com

---

## 4 — Password-Protected Delivery (Separate Message)

> Use when you want to send the password in a **separate email or text** from the delivery link.
> This is the most secure delivery method for sensitive projects.

**First message — delivery link (email):**

---

**Subject:** [PROJECT NAME] — delivery files ready

Hi [CLIENT NAME],

Your project files are ready. The password for your delivery link will be sent separately.

**Delivery link:** [DELIVERY LINK]

Once you have the password, open the link above and enter it when prompted.

Files expire: [EXPIRATION DATE] *(delete if not applicable)*

Alex Stoen · Aerial Professional Services
(719) 308-0513 · info@aerialprofessionalservices.com

---

**Second message — password only (text or separate email):**

```
APS delivery password for [PROJECT NAME]: [PASSWORD]
```

---

## Notes for Use

**When to use each template:**

| Situation | Template |
|---|---|
| Standard final delivery | Primary (Template 1) |
| Repeat client, no explanation needed | Short (Template 2) |
| Expired or missing link | Follow-Up / Replacement (Template 3) |
| High-confidentiality project | Password Separated (Template 4) |

**Tone reminders:**
- Keep it professional and direct. This is a delivery, not a pitch.
- Do not use excessive exclamation points or marketing language.
- "It was a pleasure" at the end of the primary template is optional — remove it for purely transactional deliveries.
- Always spell out the phone number as `(719) 308-0513` in email — do not use SMS-style formatting.

**Link expiration:**
- If you set an expiration date in Synology Drive when creating the share, include it.
- If no expiration is set, use: "available indefinitely — please download at your convenience."
- Do not promise indefinite availability for large video files.

**Password delivery:**
- For most projects, including the password in the same email is fine.
- For real estate agents (who may forward delivery emails to clients or vendors), consider sending the password separately.
- Always test the link and password yourself before sending.

**File summary examples:**

| Project type | Example FILES INCLUDED text |
|---|---|
| Real estate listing | 24 full-resolution aerial photographs, edited and MLS-ready |
| Roof inspection | 18 high-resolution inspection images, annotated PDF report |
| Construction monitoring | 41 progress images organized by shoot date (3 sessions) |
| Commercial photography | 32 aerial photographs + 1 highlight video (4K MP4, 3:42) |
| Events / cinematic | 2 edited video exports (4K MP4), 14 select still frames |
| Residential aerial | 16 aerial photographs, full resolution, color-corrected |

---

## Recommended Folder Structure (Synology Drive)

Organize share folders consistently before generating the delivery link.
Suggested naming convention:

```
YYYY-MM-DD — [Client Last Name] — [Project Type] — [Location]
```

**Examples:**
```
2026-05-30 — Johnson — Real Estate — 4521 Mesa Ridge Rd CS
2026-05-28 — Hartwell Construction — Construction Monitoring — Academy Blvd Site
2026-05-12 — Smith — Roof Inspection — 1902 Tealwood Dr Falcon
```

**Subfolder structure for multi-file deliveries:**
```
/Photos
/Video
/Reports
/Raw (if delivering RAW files — rare)
```

Keep folder names clean — clients see them when they open the share link.

---

## Security Reminder

- Never share a delivery link in a public channel, group text, or social media message.
- Never post delivery links on the website or in the Google Business Profile.
- If a client shares their link with someone else and that person needs separate access, generate a new share link — do not reuse the original.
- Synology Drive share links include a unique token per share. Regenerating the link invalidates the old one.
- The public page at `https://aerialprofessionalservices.com/client-deliveries` explains the delivery process but does not expose any file directory or shared access point.

---

*Aerial Professional Services LLC · Colorado Springs, CO*
*FAA Part 107 · $1M Insured · Veteran-Owned · SDVOB Certified*
