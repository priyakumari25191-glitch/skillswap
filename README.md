# SkillSwap

## Hackathon
- **Track:** Track 2 — Real-World AI Products
- **Brief:** SkillSwap — Creator Economy
- **Hackathon ID:** `ADD_HACKATHON_ID_HERE`

> Replace the placeholder with the exact Hackathon ID before submission.

## Project Overview
SkillSwap is a creator gig marketplace where young creators can list their skills and clients can discover and book services.

**Create a gig → Discover gigs → Book → Creator reviews → Accept/Decline → Client tracks status**

## Required Features

### 1. Post a Gig
Creators can publish a service with a title, category, rate, pricing unit, creator name, and description. New gigs appear at the top of the marketplace.

### 2. Browse & Search
Clients can browse gigs, search gigs/creators/skills, filter by category, and see gigs ordered newest first.

### 3. Book a Gig
Clients submit their name, email, and requirements/details. New booking requests start as **Pending** and appear in My Bookings.

### 4. Creator Dashboard
Creators can view incoming booking requests and **Accept** or **Decline** them.

### 5. My Bookings
Clients can see their bookings and their status: **Pending, Accepted, or Declined**. Declined bookings provide a shortcut to similar gigs.

## Decision Points
See [`DECISIONS.md`](DECISIONS.md).

- **DP1 — Rejection:** A declined booking remains visible as Declined and provides **Find Similar Gigs**.
- **DP2 — Double Booking:** A gig can receive another booking while an earlier booking is still Pending.
- **DP3 — Discovery:** Marketplace gigs are ranked newest first.

## Access
No required login/password flow is used, so evaluators can access the product features directly.

## Demo Flow
1. Browse/search/filter gigs
2. Post a gig
3. Book a gig
4. Accept/decline a booking
5. Check the resulting status in My Bookings

The demo also shows all three Decision Point behaviors.

## Standard API
**Status: TO CONFIRM BEFORE SUBMISSION**

The final submission should state whether a standard API was implemented, according to the hackathon instructions.

## Live Demo
**Live URL:** `ADD_LIVE_URL_HERE`

## Repository
**GitHub:** `ADD_GITHUB_URL_HERE`

## Tech / Build
Built as a web application with Lovable-assisted development.
