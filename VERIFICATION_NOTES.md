# Verification Notes — Top 10 Demos

**Built:** April 28, 2026
**Source data:** Outscraper export + agent web research + live Chrome browsing

This document is for you, Tyler. It lists what's verified-from-data versus what came from agent web research (and might need a 30-second spot-check before you walk into the call).

---

## What's verified across ALL 10 demos

These came directly from your Outscraper export and are accurate:

- Business name
- Phone number
- Street address, city, state, zip
- Google rating (e.g. 4.9★)
- Google review count
- Working hours
- Email (where present in the data — leads 4 and 8 only)
- Google Maps URL
- Google Reviews URL (the "Open real Google reviews" buttons)
- "Verified by Google" status

## What's research-derived (verify before pitching)

| Lead | Researched fact | Source | Risk if wrong |
|---|---|---|---|
| 1. National Leak Detection | Owner = Kent S. (Yelp shows him replying as "Business Owner") | Yelp business page (live-fetched) | Low — name confirmed via Yelp owner-reply |
| 1. National Leak Detection | "Kent Stubbs" full name | Agent web research | Medium — verify before saying full name |
| 1. National Leak Detection | Founded 2011 | Agent web research | Low — claimed by self-description "Over 10,000 water leaks detected" |
| 1. National Leak Detection | Team names: Laura, Paul, Ken, Chase, Sean | Yelp reviews (live-fetched) | Low — multiple reviews mention them |
| 2. Flores Strawing | Owner = Ruben Flores; bookings = JoAnna | Agent web research | Medium |
| 2. Flores Strawing | Founded 2008 / 17 years | Agent web research | Medium |
| 3. Marietta Radiator | Owner = Tommy Kemp, President | Agent web research | Medium |
| 3. Marietta Radiator | Founded 1975 / 51 years | Agent web research | Medium |
| 4. Pulliam HVAC | Owner = Joey Pulliam | Email username + agent research | Low — email is `pulliamjoey05@...` |
| 4. Pulliam HVAC | Founded 1991 / 35 years / 5 locations | Agent web research | High — verify before pitching |
| 5. Atlanta Plumber For Less | Yelp marked them CLOSED (Oct 2025) | Agent web research | **Critical — confirm operating status before any outreach** |
| 6. 1st Class HVAC Contractors | Owner identity | Not publicly available | N/A |
| 7. Atlanta Heating & Cooling | Generic-name business | Agent flagged | **Critical — verify it's a real distinct business** |
| 8. Jones Plumbing | Owner = James "Jay" Jones | Agent + email handle | Medium |
| 8. Jones Plumbing | 25+ years, A+ BBB | Agent web research | Medium |
| 9. 1ST Class HVAC Atlanta | Same address as Lead 6 | Outscraper data | **Possibly same operator or duplicate listing — confirm** |
| 9. 1ST Class HVAC Atlanta | Outscraper had garbage prefix `19956 James Couzen Fwy` | Data quality artifact | Stripped from demo; real address is Defoor Hills |
| 10. DA Plumbing & Septic | Owner = D.A. (initials only) | Agent | Medium |

## Reviews status

| Lead | Reviews on demo | Action needed |
|---|---|---|
| 01 | **5 real Yelp reviews loaded** with verified attribution (Lynn E., Taylor M., Nancy W., Jamee M., Brent D.) | None — ready to show |
| 02 | 1 Yelp snippet found ("Very inexpensive, high quality mulch...") + 3 placeholder slots | Click "Open real Google reviews" on demo, paste 2-3 |
| 03–10 | Placeholder review slots with one-click button to open real Google reviews | Click button on each demo, copy 2-3 best, paste in |

Pasting reviews takes ~2 minutes per demo. The button on each placeholder card opens that business's real Google reviews directly.

## Files in this folder

- `00_index.html` — portfolio overview, links to all 10 demos
- `01_national_leak_detection.html` — Editorial deep-blue (real reviews loaded)
- `02_flores_strawing.html` — Warm earth-tone family business
- `03_marietta_radiator.html` — Vintage Americana
- `04_pulliam_hvac.html` — Stately heritage rebrand
- `05_atlanta_plumber_for_less.html` — Modern green value
- `06_1st_class_hvac_contractors.html` — Premium black/gold luxe
- `07_atlanta_heating_and_cooling.html` — Modern dev-tool aesthetic
- `08_jones_plumbing.html` — Solo-operator personal
- `09_1st_class_hvac_atlanta.html` — Tech-forward dark
- `10_da_plumbing_septic.html` — Industrial bold (orange + navy)
- `VERIFICATION_NOTES.md` — this document

## How to use in a meeting

1. **Pre-meeting (5 min total):** open the demo, click the "Open real Google reviews" button, paste 2-3 of their best Google reviews into the placeholder slots in your editor or save-as a copy.
2. **In the meeting:** screen-share the demo. Say *"I built this to start the conversation. Every detail of your business is in there — your phone, your address, your reviews. If we're a fit, I can have it live in seven days."*
3. **Close:** ask if they want to make any changes before you take it live. Their answer is the close.

## Caveats

- These are **demos**, not production sites. They use placeholder pricing, illustrative service descriptions, and stock-pattern hero treatments. Real production work would replace those with the prospect's actual specifics during onboarding.
- Each demo includes a small "DEMO" badge in the bottom-right corner so you can show internal screenshots without confusion.
- Three pages (4, 5, 7, 9) carry warning banners about data-quality issues you should resolve before reaching out.
