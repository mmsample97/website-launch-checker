---
name: website-launch-checker
description: "Check any website before go-live against a 15-point launch checklist, with extra checks for your website type. Use when a user asks to audit, check, review, or launch a website, or asks if a site is ready to publish. Works for [WEBSITE TYPE: small business, online store, portfolio, blog, landing page, agency, restaurant, clinic, SaaS, or other], in [LANGUAGE], for [MAIN GOAL: get leads, sell online, take bookings, show work, or other]. Give it a site URL, a folder of site files, or a live demo link and it returns a pass/fail report with evidence and fixes."
---

# Website Launch Checker

## Purpose

Check any website before it goes live, so nothing embarrassing ships.
The checker does not redesign the site. It checks readiness, reports
what is missing, and says exactly what to fix.

It works for any website type, not only small business sites.
First, ask the user for these variables, in [square brackets],
so the check fits their site:

- [WEBSITE TYPE: small business, online store, portfolio, blog,
  landing page, agency, restaurant, clinic, SaaS, or other]
- [LANGUAGE: English, Arabic, Hindi, or other, and if the site
  is in more than one language]
- [MAIN GOAL: get leads, sell online, take bookings, show work,
  share news, or other]
- [MAIN PAGES: Home, Services, Shop, About, Contact, or other]
- [HAS A FORM: yes or no, and what the form is for]
- [SELLS ONLINE: yes or no]
- [TAKES BOOKINGS: yes or no]

Use the answers to choose which extra checks apply below.
Do not check a shop checkout on a site with no shop, and do
not check bookings on a site with no bookings. Mark checks
that do not apply to this site type as "Not applicable yet".

## How to use it

1. Ask the user for the variables above, one at a time, in plain
   words. If they do not know a variable, use the most common
   answer for their website type and say so.
2. Ask the user for one of these:
   - A live URL
   - A folder of website files
   - A demo or staging link
3. If the user gives only a URL, say clearly what cannot be checked
   from outside. Do not guess those items. Mark them
   "Needs client confirmation" instead of Pass.
4. Check every item in the 15-point checklist below, in order,
   then check the extra checks that apply to this website type.
5. For each item, record evidence: the page, file, line, tag, or
   screenshot where you saw it. No evidence means no Pass.
6. Finish with the report format at the end of this file.

## The 15-point launch checklist

Check all 15. Do not skip one because it looks small.
These 15 apply to every website type.

### 1. Custom 404 page
- A visitor who types a wrong address sees a branded 404 page,
  not a server default or a blank page.
- The 404 page links back to Home and to Contact.
- Fail if there is no 404 page, or if it is the default one.

### 2. Unique page titles
- Every page has its own `<title>`.
- No two pages share the same title.
- No title is empty, and no title is just the business name on
  every page.
- Titles describe that page in plain words, in the site language.

### 3. Meta descriptions
- Every main page has a meta description.
- Each description is unique to that page.
- Each description is a short, plain summary of what is on
  that page, not keyword stuffing.
- Fail if a main page has no description.

### 4. Social preview images
- When the site link is shared on WhatsApp, Facebook, or
  other apps, it shows a proper preview image, title, and
  description.
- Check Open Graph tags (`og:title`, `og:description`,
  `og:image`) and that the image file actually exists.
- Fail if the preview image is missing, broken, or a
  placeholder.

### 5. Image alt text
- Every meaningful image has alt text that describes the
  image in plain words.
- Decorative images may have empty alt text, but say so.
- Fail if main images, product photos, or team photos have
  no alt text.

### 6. Internal links
- Pages link to each other in a sensible way: Home, Services,
  About, Contact, and any key pages for this website type.
- Click or check every internal link. No link goes to a
  missing page, a 404, or a placeholder like `#`.
- Fail on any broken internal link.

### 7. Sitemap and Google Search Console
- A `sitemap.xml` exists and lists the real pages.
- The site has been submitted to Google Search Console,
  or the owner has been told this step is still needed.
- From a URL alone you cannot prove Search Console
  submission. In that case mark this "Needs client
  confirmation" and list it as an owner step. Do not
  mark it Pass on a guess.

### 8. robots.txt
- A `robots.txt` file exists at the site root.
- It allows the pages that should be found, and does not
  accidentally block the whole site.
- Fail if it is missing, or if it blocks everything.

### 9. HTTPS everywhere
- Every page loads over HTTPS, not HTTP.
- No mixed content warnings: images, scripts, and forms
  must also load over HTTPS.
- Fail on any HTTP page or mixed content.

### 10. Spam protection on forms
- Every form has spam protection, for example a captcha,
  honeypot, or a form service with spam filtering.
- Fail if a contact or lead form has no protection at all.
- If the site has no form at all, mark this "Not
  applicable yet" and add it to the fixes list as:
  "Needed when a real form is added." Do not mark it
  Fail for a form that does not exist.
- Do not submit a real form to test this unless the user
  says you may. Check the code or the form settings instead.

### 11. Thank-you page after submit
- After a visitor submits a form, they see a thank-you
  page or a clear thank-you message.
- The thank-you page confirms what happens next, for
  example "We will reply on WhatsApp within one working day."
- Fail if the form just reloads, clears, or shows no
  confirmation.
- If the site has no form at all, mark this "Not
  applicable yet" and add it to the fixes list as:
  "Needed when a real form is added." Do not mark it
  Fail for a form that does not exist.

### 12. Google Analytics
- Google Analytics, or an equivalent analytics tool the
  owner chose, is installed on every page.
- From a URL alone you cannot prove the owner can see
  the data. If you cannot verify access, mark this
  "Needs client confirmation" and list it as an owner step.
- Analytics needs the client's Google account. Say that
  plainly. Do not claim it is done without that account.

### 13. Privacy policy, with a cookie note
- The site has a privacy policy page.
- The policy is real: it names what data the site actually
  collects, for example form details, and how it is used.
- It includes a cookie note if cookies or analytics are used.
- Fail if the policy is generic boilerplate that does not
  match this site, or if it is copied text with another
  business name in it.

### 14. FAQ
- The site has an FAQ section or page.
- The questions are the ones real customers actually ask:
  price range, location, timing, how to book, what to bring.
- Fail if there is no FAQ, or if the answers are vague
  filler with no real information.

### 15. Only real testimonials
- Every testimonial on the site is real.
- No placeholder names, no invented reviews, no "John Doe",
  no stock quotes presented as customers.
- If a testimonial cannot be verified, mark it Fail and
  say: remove it, or replace it with a real one with
  permission.
- If the site has no testimonials at all, mark it
  "Missing" and say: none found, and no fake names
  found either. Do not call that "Fake". A missing
  testimonial section is a gap to fill, not a fake
  testimonial.
- A site with fake testimonials is a hard fail. It is
  not ready, even if everything else passes.

## Extra checks by website type

Check only the group that matches [WEBSITE TYPE].
Report these separately, after the 15 points above.
Mark a check "Not applicable yet" if that feature does
not exist on this site.

### A. Online store
- Product pages show a clear price, in one format, and
  what is included.
- Add to cart, checkout, and payment work, with no
  broken step. Do not place a real order unless the
  user says you may.
- Shipping, delivery, and returns are stated in plain
  words, with cost and time.
- Out of stock products say so, and do not allow checkout.

### B. Portfolio, agency, or freelancer site
- Work samples are real projects, with a name, what was
  done, and a result or statistic where possible.
- Contact details and a clear next step are easy to find
  on every work page.
- No sample work is presented as client work when it is
  not a real client.

### C. Blog, news, or content site
- Articles have a clear date, author, and category.
- Older articles still load, with no broken images or links.
- Search and categories work, and a reader can find a
  topic in two clicks.

### D. Restaurant, clinic, salon, or booking site
- Booking or appointment steps work, with a clear date,
  time, price, and confirmation message.
- Opening hours, location, and phone or WhatsApp are
  correct and easy to find.
- Prices, services, and any deposit or cancellation
  rule are stated before booking.

### E. Landing page or single page site
- One clear main goal is visible at the top, with one
  clear button.
- The page loads fast on a phone, with no broken section.
- The form or button works, and the visitor sees what
  happens next after they tap it.

### F. SaaS, app, or software site
- Pricing is clear, with what is included in each plan,
  and no hidden step at sign up.
- Sign up, sign in, and password reset work.
- Help, support, and contact are easy to find.

## Extra design checks

These are not part of the 15 points above, but report them
separately as "Design notes". Do not mix them into the
15-point score.

- No AI slop: no purple gradients, no centred headline
  plus three identical cards as the whole design, no
  generic layout repeated on every section.
- Premium, polished, liveable layout: clear hierarchy,
  readable type, real photos or real project details
  where possible.
- Numbers are consistent site-wide: one format, one size
  system. Do not mix "AED 500", "500 AED", and "500"
  for the same kind of price.
- Project details, where used, are shown as statistics,
  not as vague claims.
- Key information is easy for a weak English reader:
  short simple sentences, clear headings, and contact
  details that are easy to find.
- Works on a phone: text is readable without zooming,
  buttons are easy to tap, and no section is cut off.

## Hard rules

- Never mark Pass without evidence.
- Never invent a testimonial, a statistic, a customer
  count, or a review.
- Never say Search Console or Analytics is done without
  the client's Google account step.
- Never say a site is ready if a form has no spam
  protection, no thank-you confirmation, or fake
  testimonials. Those are blockers. A site with no
  form at all is different: use "Not applicable yet"
  for checks 10 and 11, not Fail.
- Never use a placeholder to fill a gap. Report the gap.
- Keep the report in plain, short sentences. The owner
  may not be a technical reader.

## Report format

Always finish with this format, in this order:

### Launch report: [site name or URL]
### Website type: [WEBSITE TYPE] | Language: [LANGUAGE] | Main goal: [MAIN GOAL]

**Verdict: Ready / Not ready / Not ready - blockers found**

Use "Ready" only if there is no Fail, or if the only
open items are owner steps the client has confirmed they
will do on launch day. "Not applicable yet" and
"Missing" do not by themselves block a Ready verdict,
but list them as gaps. Otherwise use "Not ready".

**Results**

| # | Check | Result | Evidence |
|---|-------|--------|----------|
| 1 | Custom 404 | Pass / Fail / Needs client confirmation / Not applicable yet / Missing | page or file |
| 2 | Unique page titles | ... | ... |
| 3 | Meta descriptions | ... | ... |
| 4 | Social preview images | ... | ... |
| 5 | Image alt text | ... | ... |
| 6 | Internal links | ... | ... |
| 7 | Sitemap and Search Console | ... | ... |
| 8 | robots.txt | ... | ... |
| 9 | HTTPS everywhere | ... | ... |
| 10 | Spam protection on forms | ... | ... |
| 11 | Thank-you page after submit | ... | ... |
| 12 | Google Analytics | ... | ... |
| 13 | Privacy policy with cookie note | ... | ... |
| 14 | FAQ | ... | ... |
| 15 | Only real testimonials | ... | ... |

**Extra checks for this website type: [WEBSITE TYPE]**

| Check | Result | Evidence |
|---|---|---|
| [extra check name] | Pass / Fail / Not applicable yet | page or file |

**Fixes, in priority order**

1. Blocker first: [what to fix, on which page, in plain words]
2. Next fix: ...
3. ...

**Owner steps - needs the client**

- [For example: give Google account access for Search Console]
- [For example: confirm testimonials are real and give permission to show them]
- [For example: write the real privacy policy text]

**Design notes**

- [Any note from the Extra design checks section, or "None".]

**What was not checked, and why**

- [For example: Search Console submission could not be verified from a URL alone.]
