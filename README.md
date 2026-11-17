# ConfNet — Networking Platform for Conference Participants (MVP)

**ConfNet** is an interactive web MVP of a B2B networking platform designed for conference attendees and organizers.

It was built from a technical specification (ТЗ) dated 2025-11-05, extracted from a voice note. The goal is to provide attendees with persistent networking and retention between events, while giving organizers a marketing-base and audience management tool.

## Product Vision

- **For attendees**: Unified account across conferences, interest-based matching, in-app chats, proximity discovery (“who’s nearby”), stories, loyalty program, event registration, and feed of announcements.
- **For organizers / B2B**: Cabinet for announcements, push notifications, audience management, and retention campaigns (e.g. re-inviting past participants of Web Summit).
- **Monetization model** (as per TZ): Free for users; value captured via marketing base for organizers/sponsors.

## Implemented Features (current MVP)

| Feature | Status | Notes |
|---------|--------|-------|
| Unified login / registration | ✅ | Single account, role selection (Participant / Organizer) |
| Interest-based matching | ✅ | Score + “Write” button |
| In-app chats & communities | ✅ | Chat list + live messaging with demo replies |
| Stories | ✅ | Horizontal story rings + full-screen viewer |
| Who’s nearby (proximity) | ✅ | Visual map with dots + distance list |
| Loyalty program | ✅ | Points, levels (Silver → Gold), rewards list |
| Feed & announcements | ✅ | |
| Event registration & promo codes | ✅ (basic) | |
| B2B cabinet | ✅ | Announcements, push, re-invite past attendees |
| Retention mechanics | ✅ | Re-invite flow |
| Mobile-first responsive UI | ✅ | Bottom navigation, Tailwind CSS |

## Tech Stack (MVP)

- Pure HTML + Tailwind CSS (CDN) + vanilla JavaScript
- Lucide icons
- Single-file prototype for easy demo and iteration
- No backend (client-side demo data)

## How to Run

1. Clone the repo
2. Open `index.html` in any modern browser
3. Log in with the pre-filled demo credentials (or change them)
4. Switch role to **Organizer** to access the B2B cabinet

## Roadmap (from original TZ)

- Native iOS + Android clients
- Real matching algorithm + profile enrichment from public sources
- Geo + Bluetooth/NFC proximity
- White-label vs multi-event aggregator decision
- Full research package: competitor analysis, GTM, product offering, social reviews (X etc.)
- Loyalty rewards redemption, speaker corner, partner programs
- GDPR-compliant data handling

## Origin

Created as an interactive prototype based on the draft technical specification for a conference networking platform. All requirements were extracted without invention from the source voice note.

---

**Repository**: https://github.com/jenyago/confnet-mvp  
**Author**: Evgeny Goncharov (jenyago)  
**Date**: November 2026
