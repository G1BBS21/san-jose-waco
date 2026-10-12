# Tarleton Journey – Plan for the Remaining Emails

Covers the seven emails that still need content: **Email-only 04, Email-only 05 and Both 01–05**. Block-level details (files, alt text, links with UTMs) are in [`tarleton-journey-build-sheet.md`](tarleton-journey-build-sheet.md). The graphics are in [`assets/tarleton/`](../assets/tarleton/).

## How every email is built

Each email uses the same stack as the finished Email-only 01–03, plus one addition: a short live-text block.

1. **Header:** the existing black "San Jose Jewelers" header.
2. **Live-text intro (new, recommended):** one headline, one or two sentences and a button, as real HTML text rather than an image.
3. **Graphic blocks:** full-width images, each with its own link and alt text.
4. **Footer:** the existing black footer.

**Why add live text:** the finished emails are image-only. Many inboxes block images by default, so readers can see a blank email. Image-only emails also score worse with spam filters. A short text block fixes both problems and gives the email a clickable button that works without images. If you prefer to match Email-only 01–03 exactly, skip it, but consider adding it to 01–03 as well later.

**Shrink the images before uploading.** The source files are about 1–1.8 MB each, so a four-image email weighs 5–6 MB and loads slowly on phones. Resizing them to 1200 px wide (2× a 600 px email) at about 80% JPEG quality brings each one to roughly 200–300 KB with no visible loss. I can produce these from the repo copies.

## Send timeline

| Day | Email-only branch | Both branch |
|---|---|---|
| 0 (+4h) | Email 01 ✅ | Both Email 01 |
| 1 | | Both Email 02 |
| 2 | Email 02 ✅ | Both Text 1 (builder) ✅ |
| 4 | | Both Email 03 |
| 5 | Email 03 ✅ | |
| 8 | | Both Email 04 |
| 9 | **Email 04** | |
| 10 | | Both Text 2 (get help) ✅ |
| 12 | **Email 05** | |
| 13 | | Both Email 05 |

✅ = content done. **Bold** or unmarked = still to build.

---

## Email-only 04 – Our Story, Reviews and Ring Care

**Role:** build trust. By day 9 the reader has seen the product three times. This email introduces the people behind it, shows proof from customers and removes the worry about what happens after purchase.

| Field | Proposed |
|---|---|
| Email name | Tarleton - Email 04 - Our Story and Ring Care |
| Subject | The family behind your Tarleton ring |
| Preview | Family-owned in Waco since 1985, and here for your ring long after graduation. |
| UTM campaign | `tarleton_welcome_04` |

**Live-text intro**
> **Meet the family behind your ring.**
> San Jose Jewelers has been crafting university rings in Waco since 1985. Here's a little about who we are, what our customers say, and how we take care of your ring for life.
> [Get to know us] → About page

**Graphic stack (Canva layout, recommended)**

| # | Graphic | Purpose | Link |
|---|---|---|---|
| 1 | e4-1 Your Ring. Our Personal Touch. | Hero; sets up the email | About |
| 2 | e4-2 The San Jose Story | Founder story, since 1985 | About |
| 3 | e4-3 From Our Customers | Social proof (approved excerpts only) | Reviews ("Read More Reviews") |
| 4 | e4-4 Care Beyond the Purchase | Lifetime care and warranty | Warranty |

*Alternative (handoff layout):* e4-2 → e4-4 → e4-1, without the reviews. I recommend the Canva layout because reviews are the strongest trust signal you have, and Both 04's subject already promises them.

## Email-only 05 – Beyond the Ring

**Role:** the last email. It widens the offer for readers who aren't ready for a ring, points to the sister store, and invites them to follow on social so the conversation continues after the journey ends.

| Field | Proposed |
|---|---|
| Email name | Tarleton - Email 05 - Beyond the Ring |
| Subject | More ways to wear your Tarleton pride 💜 |
| Preview | Bolo ties, cattle tags, custom pendants and more. |
| UTM campaign | `tarleton_welcome_05` |

**Live-text intro**
> **Tarleton pride, beyond the ring.**
> From western-inspired cattle tags and bolo ties to a pendant you design yourself, there's more than one way to carry your Tarleton story with you.
> [Shop Tarleton jewelry] → Tarleton jewelry collection

**Graphic stack**

| # | Graphic | Purpose | Link |
|---|---|---|---|
| 1 | e5-1 Cattletags & Western Jewelry | Lower-priced, giftable Tarleton items | Tarleton jewelry collection |
| 2 | e5-2 Custom Necklace Builder | A design-it-yourself option besides rings | Pendant builder |
| 3 | e5-3 Waco Diamonds | Cross-sell: engagement and bridal | wacodiamonds.com |
| 4 | e5-4 Follow Us On Our Socials | Keep in touch after the journey | Instagram |

---

## Both Email 01 – Collection Introduction

Subject and preview are already set (section 4.3). Content mirrors Email-only 01.

| Field | Value |
|---|---|
| Subject / Preview | Your Tarleton ring. Your style. / Explore customizable Tarleton rings and meet the family behind your next favorite piece. |
| UTM campaign | `tarleton_welcome_both_email_01` |

**Live-text intro**
> **Your Tarleton story deserves a ring that feels like you.**
> Explore the Tarleton Collection: classic or bold, simple or a little extra sparkle, made to wear long after graduation.
> [Shop Tarleton rings] → Tarleton rings collection

**Graphic stack:** e1-1 Your Tarleton Story → e1-2 The Tarleton Collection → e1-3 The San Jose Experience → e1-4 Two Seals → Affirm banner (copy from Email-only 01) → e1-5 Something For The Guys.

## Both Email 02 – Two Ways to Shop

| Field | Value |
|---|---|
| Subject / Preview | Build it yourself or start from a design / Two easy ways to get your Tarleton ring just right. |
| UTM campaign | `tarleton_welcome_both_email_02` |

**Live-text intro**
> **Two ways to your Tarleton ring.**
> Love choosing every detail? Build it in our 3D ring builder. Prefer a little inspiration? Start from one of our Tarleton designs.
> [Build your Tarleton ring] → Tarleton 3D builder

**Graphic stack:** e2-1 Two Ways → e2-2 3D Ring Builder → e2-3 Pre-Designed Rings.

⚠️ **Overlap:** Both Text 1 (day 2, "Try the builder") repeats this email's builder message one day later. You could switch the text to the pre-designed angle, or move it after Email 03.

## Both Email 03 – Metals and Stones

| Field | Value |
|---|---|
| Subject / Preview | Which metal and stone fit your Tarleton ring? / Compare metals and stones to find the combination that feels like you. |
| UTM campaign | `tarleton_welcome_both_email_03` |

**Live-text intro**
> **Find your metal. Find your sparkle.**
> Platinum silver, 10K or 14K gold. Moissanite, lab-grown or earth-mined diamond. Compare your options, then bring your favorite combination to life in 3D.
> [Build your Tarleton ring] → Tarleton 3D builder

**Graphic stack:** e3-1 Your Metal. Your Sparkle. → e3-2 Which Metal → e3-3 About Our Stones → e3-4 Make It Yours.

## Both Email 04 – Reviews

| Field | Value |
|---|---|
| Subject | ⚠️ Current: "Why Tarleton grads trust San Jose Jewelers". **Proposed: "Why Texas grads trust San Jose Jewelers"** |
| Preview | ⚠️ Current: "Hear what Tarleton graduates say about their rings." **Proposed: "Hear from customers who've worn our rings and buckles."** |
| UTM campaign | `tarleton_welcome_both_email_04` |

**Why change the subject and preview:** nothing confirms that the two approved reviewers (Gaby M. and Desiree R.) are Tarleton graduates, and one review is about a buckle, not a ring. The current lines would make a claim the content can't back up. Keep them only if Chase confirms both reviewers are Tarleton grads.

**Live-text intro**
> **Real words from real customers.**
> We're a family business, and every ring we make is personal. Here's what customers say, plus how we care for your ring long after you take it home.
> [Read more reviews] → Reviews page

**Graphic stack:** same four blocks as Email-only 04 (e4-1 → e4-2 → e4-3 → e4-4). This keeps both branches identical and makes the journey easy to clone.

## Both Email 05 – Beyond the Ring

| Field | Value |
|---|---|
| Subject / Preview | More ways to wear your Tarleton pride 💜 / Beyond the ring: pendants, earrings and more. |
| UTM campaign | `tarleton_welcome_both_email_05` |

⚠️ **The preview mentions earrings,** but no graphic shows earrings. Proposed: "Beyond the ring: cattle tags, custom pendants and more."

**Live-text intro and graphic stack:** same as Email-only 05.

---

## Graphic gaps

None of the planned emails needs a new graphic: the 20 assets cover every block. Optional additions, if Chase wants them:

| Optional graphic | Where | Why |
|---|---|---|
| Affirm banner | End of Email 02 and 03 | The financing message appears only in Email 01, while the reader is still browsing. It also helps in the emails that push the builder. |
| "Order by" timing strip (5–10 week custom turnaround) | Email 03 or 04 | Sets expectations and adds gentle urgency without dates that go stale (turnaround is from the site FAQ; confirm first) |

**Keep dated promotions out of this journey.** The Christmas cutoff (10/18/26) and the Tarleton Ring Event (10/21/26) would be out of date within days. Send them as one-off campaigns instead.

## Decisions for Chase

1. Email 04 layout: Canva (with reviews, recommended) or the handoff version?
2. Add the live-text intro block to every email?
3. Rewrite Both 04's subject and preview (Tarleton grads claim) and Both 05's preview (earrings)?
4. Fix the Both Email 02 / Text 1 builder overlap?
5. Use the optional graphics (Affirm banner in 02/03, turnaround strip)?
6. Carried over: Smart Sending consistency, the empty Else branch, the exit rule, and the MMS image (e1-1 suggested).
