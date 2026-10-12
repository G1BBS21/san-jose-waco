# Tarleton Journey – Build Sheet

Journey: **Joined a Segment - Text + Email - Tarleton [COPY] 10-08-26 03:40:03**
Working copy: https://ui.attentivemobile.com/journeys/1004752/revision/1755933/edit
Do not edit the original (journey 989403). Keep the copy in Draft: never Turn on or Schedule.

This sheet lists every image block still to build or fix, with alt text and click-through URL, ready to enter in the Attentive editor. To clone it for another school, swap the tokens in the "Per-school tokens" section.

## Per-school tokens

| Token | Tarleton value |
|---|---|
| `{SCHOOL}` | Tarleton |
| `{SCHOOL_FULL}` | Tarleton State University |
| `{slug}` | tarleton |
| `{MENS_RING_URL}` | https://www.sanjosewaco.com/products/tarleton-mens-ring |
| `{EVENT_URL}` | https://www.sanjosewaco.com/blogs/jewelry-talk/tarleton-state-university-ring-event |

## UTM convention (unchanged from section 4.2)

Add to every sanjosewaco.com and wacodiamonds.com click-through:

- Email-only N: `?utm_source=attentive&utm_medium=email&utm_campaign={slug}_welcome_0N`
- Both Email N: `?utm_source=attentive&utm_medium=email&utm_campaign={slug}_welcome_both_email_0N`

Social profile links get no UTMs.

## Base URLs (from the 2026-10-12 site fetch, re-verify before publishing)

| Key | URL |
|---|---|
| BUILDER | https://www.sanjosewaco.com/collections/customizable-university-rings |
| PREDESIGNED | https://www.sanjosewaco.com/collections/the-university-collection-pre-designed-rings |
| MENS | https://www.sanjosewaco.com/collections/signet-mens-rings |
| PENDANT_BUILDER | https://www.sanjosewaco.com/collections/customizable-college-pendants |
| REVIEWS | https://www.sanjosewaco.com/pages/san-jose-jewelers-reviews |
| WARRANTY | https://www.sanjosewaco.com/pages/warranty |
| CONTACT | https://www.sanjosewaco.com/pages/contact-us-today |
| APPOINTMENT | https://www.sanjosewaco.com/pages/schedule-an-appointment |
| WACO_DIAMONDS | https://www.wacodiamonds.com/ |
| INSTAGRAM | https://www.instagram.com/sanjosejewelry/ |

---

## Email-only 04: Our Story and Ring Care (FIX FIRST)

Remove the stand-in Email 01 layout, then build:

| # | Graphic | Alt text | Click-through |
|---|---|---|---|
| 1 | The San Jose Story | The San Jose Story: a family-owned Waco jeweler crafting custom university rings | CONTACT + `?utm_source=attentive&utm_medium=email&utm_campaign=tarleton_welcome_04` |
| 2 | Care Beyond the Purchase | Care Beyond the Purchase: ring care and warranty from San Jose Jewelers | WARRANTY + `…tarleton_welcome_04` |
| 3 | Your Ring. Our Personal Touch | Your Ring. Our Personal Touch. Personal help from the San Jose Jewelers team | CONTACT + `…tarleton_welcome_04` |
| – | Footer (keep) | – | – |

## Email-only 05: Beyond the Ring (blank)

| # | Graphic | Alt text | Click-through |
|---|---|---|---|
| 1 | Cattletags & Western Jewelry | Cattletags and western jewelry from San Jose Jewelers | **TBD**: no collection URL confirmed; ask Chase |
| 2 | Custom Necklace Builder | Design a custom Tarleton necklace in our pendant builder | PENDANT_BUILDER + `…tarleton_welcome_05` |
| 3 | Waco Diamonds | Waco Diamonds, our sister store for fine diamond jewelry | WACO_DIAMONDS + `…tarleton_welcome_05` |
| 4 | Follow Us On Our Socials | Follow San Jose Jewelers on Instagram, Facebook, TikTok and Pinterest | INSTAGRAM (an image block holds one link; for all four, add a Social block or slice the graphic) |

## Email-only 01–03: alt text and link check

The images are swapped already. The click-through links are still the old ones, so check each block's current URL before you change it. If a link doesn't match its graphic, use the recommendation below.

| Email | Graphic | Alt text | Recommended link |
|---|---|---|---|
| 01 | Your Tarleton Story. Your Style. | Your Tarleton Story. Your Style. Custom Tarleton rings from San Jose Jewelers | current Tarleton collection link |
| 01 | The Tarleton Collection | The Tarleton Collection of customizable class rings | current Tarleton collection link |
| 01 | The San Jose Experience | The San Jose Experience: family-owned, personal service in Waco | CONTACT |
| 01 | Two Seals. Your Tarleton Pride. | Two Seals. Your Tarleton Pride. Choose your Tarleton seal | current Tarleton collection link |
| 01 | Something For The Guys | Something for the guys: Tarleton men's rings | `{MENS_RING_URL}` |
| 02 | Your Tarleton Ring. Two Ways. | Your Tarleton Ring, Two Ways: build your own or start from a design | BUILDER |
| 02 | 3D Ring Builder | Build your Tarleton ring in our 3D ring builder | BUILDER |
| 02 | Pre-Designed Rings | Shop pre-designed Tarleton rings | PREDESIGNED |
| 03 | Your Metal. Your Sparkle. Your Style. | Your Metal. Your Sparkle. Your Style. Choose metals and stones for your ring | BUILDER |
| 03 | Which Metal Is Right For You? | Which metal is right for you? Compare ring metals | BUILDER |
| 03 | About Our Stones | About our stones: compare stone options for your ring | BUILDER |
| 03 | Make It Yours | Make it yours: customize your Tarleton ring | BUILDER |

Use the matching campaign code on each link: `tarleton_welcome_01`, `_02` or `_03`.

## Both Emails 01–05 (blank)

Each one copies the Email-only email listed below, with the same graphics, alt text and links. Only the `utm_campaign` changes, to `tarleton_welcome_both_email_0N`.

| Both | Copies | Notes |
|---|---|---|
| 01 | Email-only 01 | Keep the Affirm banner as it is in Email-only 01 |
| 02 | Email-only 02 | |
| 03 | Email-only 03 | |
| 04 | **From Our Customers** (single graphic) | Alt: "From our customers: reviews from Tarleton graduates". Link: REVIEWS. Use only the approved graphic and don't add any other review text |
| 05 | Email-only 05 | Same TBD Cattletags link |

## Text-only 1 MMS image

Best guess is **Your Tarleton Story. Your Style.** Confirm with Chase before swapping.

## Cleanup

- [ ] Delete the template "TEMP Tarleton Email 01" (Settings → Templates). Ask first.
- [ ] Remove the stand-in content from Email-only 04.

## Decisions for Chase

- Smart Sending is on for Email 03 only. Make it consistent?
- Both branch: Email 01 → Email 02 → Text 1 all go out within about 2 days. Spread them out?
- The Else branch sends nothing. Is that intended?
- The exit rule hasn't been inspected yet.
- The site says both "since 1985" and "over 35 years". Which claim should we use?
- Cattletags link target.
- Time-sensitive: Christmas order cutoff is 10/18/26 and the Tarleton Ring Event is 10/21/26. Mention them anywhere?
