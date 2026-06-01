# Project Closeout Checklist
**Aerial Professional Services LLC**
Last updated: 2026-06-01

> Complete this checklist before sending the client delivery email.
> Every box should be checked before the project is marked complete.

---

## Project Information

| Field | Value |
|---|---|
| **Client Name** | |
| **Project Name** | |
| **Project Location** | |
| **Shoot Date(s)** | |
| **Completion Date** | |
| **Delivery Date** | |
| **Delivery Link** | |
| **Password** | *(leave blank if not applicable)* |
| **Link Expiration Date** | *(leave blank if no expiration set)* |
| **Project Type** | ☐ Real Estate · ☐ Roof Inspection · ☐ Construction · ☐ Commercial · ☐ Events · ☐ Residential · ☐ Other |

---

## Deliverables Verification

### Photography
- [ ] Photos culled — selects identified, rejects removed
- [ ] Photos reviewed at 100% — focus, exposure, horizon confirmed
- [ ] Full-resolution exports completed (JPEG or TIFF as required)
- [ ] Web-sized exports completed *(if requested by client)*
- [ ] File count matches expected deliverable quantity
- [ ] File naming is consistent and client-ready

### Video
- [ ] Footage reviewed — clips selected, unusable footage excluded
- [ ] Edit completed and reviewed at full playback
- [ ] Final export completed at correct resolution and codec *(typically 4K MP4 H.264/H.265)*
- [ ] Audio reviewed *(music levels, no clipping)*
- [ ] Video length confirmed as appropriate for deliverable type
- [ ] Export file size reasonable for client download

### Reports & Maps
- [ ] Roof inspection report generated and reviewed *(if applicable)*
- [ ] Annotated images included in report *(if applicable)*
- [ ] Orthomosaic export completed and verified *(if applicable)*
- [ ] GIS/GeoTIFF files included *(if applicable)*
- [ ] PDF reports named consistently and saved to delivery folder

### Final File Review
- [ ] Watermarks removed where appropriate
- [ ] Duplicate files removed from delivery folder
- [ ] No partial exports or temporary files included
- [ ] Folder structure matches standard (see reference below)
- [ ] Client-specific requirements confirmed and met

---

## Quality Control

- [ ] Horizon is level in all delivered photographs
- [ ] Exposure is consistent across the image set — no blown highlights or crushed shadows
- [ ] Color balance and white point are consistent across images
- [ ] Color-graded video matches the tone requested or established in prior projects
- [ ] No compression artifacts visible at delivery resolution
- [ ] No unwanted objects in frame *(lens flare, obstructions, equipment)*
- [ ] GPS metadata stripped or retained as required by client
- [ ] All deliverables pass a final "would I send this to a high-value client" review

---

## Synology Drive Delivery

- [ ] Project folder created using standard naming convention
  `YYYY-MM-DD — [Client Last Name] — [Project Type] — [Location]`
- [ ] Subfolders created as needed (`/Photos`, `/Video`, `/Reports`, `/Maps`)
- [ ] All files uploaded to the correct project folder
- [ ] Upload verified — file count and sizes match source
- [ ] Synology share link generated for the project folder
- [ ] Password set on share link *(if required for this project)*
- [ ] Link expiration date set in Synology *(if applicable)*
- [ ] External access tested — link opened from browser outside local network
- [ ] Mobile access tested — link opens correctly on phone
- [ ] Password entry tested *(if password-protected)*
- [ ] Delivery link copied and confirmed correct before pasting into email

---

## Client Communication

- [ ] Delivery email drafted using client delivery email template
- [ ] Subject line includes project name
- [ ] Delivery link pasted correctly into email body
- [ ] Files included summary is accurate and complete
- [ ] Password included in email *(or noted to send separately)*
- [ ] Password sent separately via text *(if required for this project)*
- [ ] Link expiration date included *(if applicable)*
- [ ] Client advised to download and save files promptly
- [ ] Support contact information included *(719-308-0513)*
- [ ] Reference to `aerialprofessionalservices.com/client-deliveries` included *(optional for new clients)*
- [ ] Delivery email sent and delivery date recorded

---

## Archival & Backup

- [ ] Raw files confirmed present on primary NAS
- [ ] Edited project files confirmed on NAS
- [ ] Project folder copied to long-term archive location *(if applicable)*
- [ ] Raw footage retained per retention policy
- [ ] Synology share link expiration reviewed — date matches what was communicated to client
- [ ] Project marked complete in project log or CRM
- [ ] Invoice sent or confirmed *(if not already completed)*

---

## Notes

> Use this section for project-specific observations, client requests, follow-up items, or anything that does not fit the standard checklist.

```
Notes:




```

---

## Common Mistakes to Avoid

**Before export:**
- Exporting before completing a final cull — low-quality selects sometimes slip through on rushed projects
- Forgetting to check the horizon on low-altitude or tilted shots
- Leaving behind temporary Lightroom export folders or Premiere render caches in the delivery folder

**Folder & naming:**
- Inconsistent file naming (e.g., mixing `DSC_0001` and `APS_RealEstate_001` in the same delivery)
- Uploading to the wrong Synology project folder — always double-check the folder name before uploading
- Missing subfolders — clients who receive a flat folder of 40 files alongside 3 PDFs find it disorganized

**Synology share link:**
- Generating the share link before the upload is complete — always verify the upload first
- Forgetting to test external access — a link that works on your local network may not work outside it
- Setting an expiration date shorter than the client needs to act on the files

**Client communication:**
- Sending the delivery link before testing it
- Including the password in the same message when separate delivery was intended
- Not specifying what is included — clients should know exactly what they are downloading
- Omitting the expiration date when one has been set

**Archival:**
- Assuming NAS backup is complete without verifying — check the sync status
- Deleting local working files before confirming NAS copy is intact
- Marking the project complete before the invoice is sent

---

## Recommended Folder Structure

Use this structure when creating the project folder in Synology Drive.
Clients see the folder and subfolder names when they open their share link — keep them clean and readable.

### Folder Naming Convention

```
YYYY-MM-DD — [Client Last Name] — [Project Type] — [Location]
```

---

### Real Estate

```
2026-05-30 — Johnson — Real Estate — 4521 Mesa Ridge Rd Colorado Springs/
├── Photos/
│   ├── APS_RE_MesaRidge_001.jpg
│   ├── APS_RE_MesaRidge_002.jpg
│   └── ...
└── Video/                          ← include only if video was delivered
    └── APS_RE_MesaRidge_Highlight.mp4
```

**Notes:**
- MLS-ready JPEG exports only unless client requested otherwise
- Typical delivery: 20–40 photographs, optionally 1 highlight video
- Web-sized exports (2048px longest edge) for agents who request them

---

### Construction

```
2026-05-28 — Hartwell Construction — Construction Monitoring — Academy Blvd Site/
├── 2026-02-24 — Session 1/
│   ├── APS_CN_AcademyBlvd_Session1_001.jpg
│   └── ...
├── 2026-04-06 — Session 2/
│   ├── APS_CN_AcademyBlvd_Session2_001.jpg
│   └── ...
└── 2026-05-28 — Session 3 — Completion/
    ├── APS_CN_AcademyBlvd_Session3_001.jpg
    └── ...
```

**Notes:**
- Organize sessions by date — clients use these for milestone reporting
- Label the final session as "Completion" if it is the last documented flight
- Include orthomosaic or map exports in a `/Maps` subfolder if applicable

---

### Land

```
2026-04-15 — Peterson — Land Survey — 80 Acres Peyton CO/
├── Photos/
│   ├── APS_Land_Peyton_Overview_001.jpg
│   └── ...
├── Maps/                           ← include if orthomosaic or map was produced
│   ├── APS_Land_Peyton_Orthomosaic.tif
│   └── APS_Land_Peyton_Orthomosaic_Preview.jpg
└── Reports/                        ← include if a written report was delivered
    └── APS_Land_Peyton_SiteReport.pdf
```

**Notes:**
- GeoTIFF files can be very large — confirm client has software to open them before delivering
- Include a JPG preview of the orthomosaic for clients without GIS software
- Note coordinate system and resolution in the delivery email if technical specs matter

---

### Events

```
2026-08-31 — Balloon Classic — Event Coverage — Prospect Lake Colorado Springs/
├── Photos/
│   ├── APS_EV_BalloonClassic_001.jpg
│   └── ...
├── Video/
│   ├── APS_EV_BalloonClassic_Highlight_4K.mp4
│   └── APS_EV_BalloonClassic_Raw_Selects.mp4   ← include only if requested
└── Selects/                        ← optional: curated hero images for social/press
    ├── APS_EV_BalloonClassic_Hero_01.jpg
    └── ...
```

**Notes:**
- Event clients often need files quickly — prioritize turnaround
- Separate a `/Selects` subfolder if delivering a curated set alongside the full gallery
- Clarify usage rights in the delivery email for commercial or branded events

---

*Aerial Professional Services LLC · Colorado Springs, CO*
*FAA Part 107 · $1M Insured · Veteran-Owned · SDVOB Certified*
*info@aerialprofessionalservices.com · (719) 308-0513*
