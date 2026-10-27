# LinkedIn Smart Application Tracker (Product Concept)

> 🚧 **Status: In progress.** This is a course project for USC Marshall MOR 530 (Product Management), Fall 2026. The final presentation is in December 2026, and this repo will be updated as the work evolves.

**Live prototype:** https://beibei-kiki-huang.github.io/linkedin-application-tracker/

## The problem
Job seekers apply across LinkedIn, company career sites, Indeed, Handshake, and other platforms. Application history ends up scattered across inboxes and half-maintained spreadsheets. People lose track of what they applied to, where each application stands, and whether a role they're looking at is one they've already submitted.

Customer discovery started with a user interview. The interviewee applied across 4+ channels, kept an Excel tracker he rarely updated, and was hesitant about connecting his email because of privacy concerns.

## The concept
A tracker built into LinkedIn that organizes applications across platforms:
- **Free:** an application dashboard with manual records, plus optional Gmail/Outlook integration. The integration detects application, interview, rejection, and offer emails and suggests status updates for the user to review.
- **Premium:** cross-platform duplicate alerts. While browsing LinkedIn, the user sees *"You may have applied to this job on another website."* Each alert shows the earlier record, can be dismissed, and offers "Report incorrect match."
- **Privacy first:** email connection is optional and limited to job-related messages. Users can disconnect it and delete imported data at any time.

## How success would be measured (proposed)
- Detection and matching quality: share of application emails identified, and email-to-application match accuracy
- Weekly active use among users who connect email
- Less time spent on manual tracking and fewer duplicate applications
- Guardrail: privacy-related disconnect rate
- Before any paid launch, duplicate alerts must meet high precision and recall bars on labeled test sets

## What's here
| File | Description |
|---|---|
| `index.html` | Clickable prototype of the tracker dashboard and email-import flow, built with AI-assisted development |
| `assets/early-concept-duplicate-alert.png` | Early mockup of the "Looks familiar" duplicate-alert banner on a LinkedIn job page |

## Project work (ongoing)
- Customer discovery interviews
- PRD with goals, success metrics, and guardrails
- PR-FAQ (Working Backwards)
- Leadership memo recommending a time-boxed discovery phase with go/no-go gates
- Lean Canvas
- Clickable prototype ← this repo

## Next steps
- More user interviews, including users unwilling to connect email
- Usability testing of the prototype against users' current workflow
- Final presentation (December 2026)

---
*Author: Beibei (Kiki) Huang, M.S. Business Analytics, USC Marshall. This is an independent course concept, not affiliated with or endorsed by LinkedIn. All data in the prototype is fictional.*
