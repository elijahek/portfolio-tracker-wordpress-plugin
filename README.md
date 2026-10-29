# Portfolio Tracker: bringing a contracted WordPress plugin in-house

A member-facing WordPress plugin that lets a nonprofit's partners track investment portfolios. It was built by an outside development firm; I'm taking it over in-house: staging it, shipping the fixes leadership requested, and building a redesigned version alongside the current one.

**Status:** in progress (October 2026). The redesign is expected around the start of 2027.

## Approach

1. **Two staging sites.** One runs the current tracker plus the requested fixes; the other runs the redesign. Both are on the organization's managed WordPress host.
2. **Real data in staging.** Staging uses live partner data (with daily database backups) so migration problems show up before release, and prices are kept current day to day for testers.
3. **Fixes to the live plugin go through the original developers** as recommended code changes, so production stays supportable during the transition.
4. **Side-by-side demo.** The current tracker with fixes and the redesigned tracker will be shown together before a release decision.
5. **Documented as it goes** on the organization's internal docs site, so the plugin is no longer a black box.

## Redesign principles

- Easy for almost anyone to use, while still familiar to current partners.
- No trading. The tracker tracks; it never places trades.
- Optional AI features using the OpenAI API.
- Values-based screening data expected from a third-party screening API.

## What's in this repo

This README. Plugin source belongs to the organization and is not published.
