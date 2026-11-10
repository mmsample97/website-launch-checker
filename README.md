> Free version, here on GitHub: Check only. It tells you what is wrong, you fix it yourself.
>
> Paid version, ready fix kit: Same check, PLUS the fix ready to use. Templates, examples, and a client ready report. You do not start from zero.
>
> Get the paid version here:
>
> - Agensi, $10: [website-launch-checker on Agensi](https://www.agensi.io/skills/website-launch-checker)
> - PromptBase, $9.99: [Websitelaunchchecker on PromptBase](https://promptbase.com/skill/websitelaunchchecker)

---

# Website Launch Checker

An AI skill that checks any website before it goes live.

Give your AI agent your site URL, demo link, or folder of site files, answer a few questions, and it goes through a 15-point list, plus extra checks for your website type, then gives you a pass/fail report with evidence and fixes. No guessing. If something cannot be verified, it says so.

## What is new in v2

V2 works for any website type, with [square bracket] variables you fill in:
[WEBSITE TYPE], [LANGUAGE], [MAIN GOAL], [MAIN PAGES], [HAS A FORM], [SELLS ONLINE], [TAKES BOOKINGS].

## The 15 checks, for every website

1. Custom 404 page
2. Unique page titles
3. Meta descriptions
4. Social preview images
5. Image alt text
6. Internal links
7. Sitemap and Google Search Console
8. robots.txt
9. HTTPS everywhere
10. Spam protection on forms
11. Thank-you page after submit
12. Google Analytics
13. Privacy policy, with a cookie note
14. FAQ
15. Only real testimonials

## Extra checks, by website type

- Online store: price, cart, checkout, shipping, returns, out of stock
- Portfolio, agency, or freelancer: real work samples, clear next step
- Blog, news, or content: date, author, category, search, working links
- Restaurant, clinic, salon, or booking: booking steps, hours, location, price before booking
- Landing page: one clear goal, one clear button, works on a phone
- SaaS, app, or software: pricing, sign up, sign in, password reset, support

It also gives separate design notes: no AI slop layouts, consistent number formatting, works on a phone, and plain, readable information.

## Who it is for

Any website owner, and the people who build websites for them.
Small business, online store, portfolio, blog, landing page, agency, restaurant, clinic, SaaS, or other.
Made for any language, and for visitors who may read English as a second language.

## How to use it

1. Install the skill in your AI agent (see below).
2. Give your agent your site URL, demo link, or folder of site files.
3. Answer, in plain words: what type of site is it, what language, what is its main goal, does it sell online, does it take bookings?
4. Ask: "Check my website with website-launch-checker."
5. Read the report. Fix the blockers first: fake testimonials, a form with no spam protection, or a form with no thank-you confirmation will always block a "Ready" verdict.

Two steps need the site owner, and the skill will list them separately: Google Search Console and Google Analytics need the owner's Google account, and testimonials need to be confirmed as real, with permission to show them.

## Examples

- Example 1, online store: [WEBSITE TYPE: online store], [LANGUAGE: English], [MAIN GOAL: sell online], [SELLS ONLINE: yes], [TAKES BOOKINGS: no]. Report shows cart and checkout checks, plus the 15 core checks.
- Example 2, portfolio: [WEBSITE TYPE: portfolio], [LANGUAGE: English], [MAIN GOAL: show work], [SELLS ONLINE: no], [TAKES BOOKINGS: no]. Report shows real work sample checks, plus the 15 core checks.
- Example 3, restaurant: [WEBSITE TYPE: restaurant], [LANGUAGE: English and Arabic], [MAIN GOAL: take bookings], [SELLS ONLINE: no], [TAKES BOOKINGS: yes]. Report shows booking, hours, and location checks, plus the 15 core checks.

## How to install it

Works with any AI agent that can read a SKILL.md file, including Claude, Copilot, Cursor, Gemini, ChatGPT, DeepSeek, Hermes, OpenClaw and other AI tools.

Copy the `SKILL.md` file into your skills folder, in a folder called `website-launch-checker`, then restart your agent. The skill file itself is just instructions. It collects no data and sends nothing anywhere.

## What it will not do

- It will not redesign your site.
- It will not invent testimonials, statistics, or reviews.
- It will not mark a check as passed without evidence.
- It will not submit a real form, or place a real order, unless you say it may.

## Files

- `SKILL.md` - the full skill: instructions, checklist, hard rules, and report format.

## License

MIT - free to use and adapt. If you improve it, a credit is appreciated but not required.
