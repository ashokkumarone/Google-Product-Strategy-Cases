# Google Product Strategy Cases

Four independent product proposals by **Ashokkumar S** (November 2026).  
*Concept work written from an outside observer's point of view. Not affiliated with or endorsed by Google.*

[![Live Case Studies](https://img.shields.io/badge/Live_Reading_Portal-GitHub_Pages-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ashokkumarone.github.io/Google-Product-Strategy-Cases/)
[![Shorts App Flow](https://img.shields.io/badge/Shorts_App_Flow-7_Screen_Flow-EA4335?style=for-the-badge&logo=youtube&logoColor=white)](https://ashokkumarone.github.io/Google-Product-Strategy-Cases/shorts-app-flow.html)
[![Strategy Document PDF](https://img.shields.io/badge/Strategy_Document-10_Page_PDF-34A853?style=for-the-badge&logo=googledocs&logoColor=white)](Google-Product-Strategy-Cases.pdf)
[![Author](https://img.shields.io/badge/Author-Ashokkumar_S-FBBC05?style=for-the-badge&logo=linkedin&logoColor=black)](https://linkedin.com/in/ashokkumarone)

---

## At a Glance

| # | Case | Product Area | Problem in One Line | Core Idea | North-Star Metric |
|---|------|--------------|---------------------|-----------|-------------------|
| **1** | **Google Pay Gifting Vouchers** | Google Pay | UPI has no gifting moment; gift cards lock users to one brand | Money Voucher + Gift Voucher, redeemable at verified merchants | Activated receivers per 100 vouchers sent |
| **2** | **Search Campus Guild** | Search & Gemini | AI misreads regional languages and slang, such as Tanglish and Hinglish | Students review and correct AI answers, earn certificates | Agreement-checked corrections per active student per week |
| **3** | **YouTube Shorts Smart Bar** | YouTube Shorts | Cluttered screen, weak commerce, rigid feed | Clean screen, one hidden options sheet, Products drawer, personal top bar | Watch time per session without a drop in shares |
| **4** | **Google Meet Couple Pack** | Google Meet | Co-watching OTT over screen share breaks (black screen, audio lag) | OTT-branded Couple Pack with Meet as the co-watch layer | Active couple pairs per month |

---

## Read the Deliverables
- [**Web Reading Portal (`index.html`)**](https://ashokkumarone.github.io/Google-Product-Strategy-Cases/): Clean web presentation of all 4 case studies, decisions, metrics, and synthesis.
- [**Shorts Interactive App Flow (`shorts-app-flow.html`)**](https://ashokkumarone.github.io/Google-Product-Strategy-Cases/shorts-app-flow.html): 7-screen mobile walkthrough of the YouTube Shorts Smart Bar.
- [**Full Strategy Document (`Google-Product-Strategy-Cases.pdf`)**](Google-Product-Strategy-Cases.pdf): Complete 10-page unabridged strategy document.

---

## Case 1: Google Pay Gifting Vouchers

### Overview
A gifting layer on top of UPI with two products: a small-value Money Voucher and a brand-agnostic Gift Voucher. The cultural anchor is the Indian *moi* or *shagun* envelope: money given at a function with a personal touch.

### Problem
- **UPI is excellent for payments but flat for gifting:** Sending ₹501 for Pongal feels the same as paying a bill, so the emotional moment is missing.
- **Digital gift cards lock users to one brand:** Amazon, Swiggy and similar cards lock users to a single merchant, so the receiver may not want what the sender chose.
- **Unclaimed money anxiety:** Senders worry about money that is never claimed or never used.

### Users
- **Sender:** Working adult sending festival, birthday or function money to family and friends.
- **Receiver:** Family member, often older and less app-savvy. Each voucher is a chance to onboard them.
- **Merchant:** A local kirana, sweet shop or textile shop that already shows a UPI QR.

### Solution
1. **Money Voucher (small, cash-like):** Capped amount (start at ₹5,000 per voucher; tune the monthly cap in a pilot). Sent as a scratch card with a greeting message. The receiver reveals the amount, then claims it. If unclaimed in 7 days, the amount refunds automatically to the sender's bank account.
2. **Gift Voucher (choice, not cash):** Redeemable across partner brands (shopping, food delivery, OTT) through a "Pay with Gift Voucher" option at checkout. A reminder at day 90; if still unused, the full balance rolls into Google Play balance with no loss of value.
3. **Local Merchant Redemption:** Vouchers can be spent at verified merchants by scanning their QR. Merchants show a "GPay Voucher Accepted" sticker.
4. **Family Circle:** Family members scan each other's QR to join a circle and earn points. Points convert into free Gift Voucher credit for the next celebration.

### Key Decisions & Trade-offs
1. **Small cap:** Keeps the product gifting-sized rather than a transfer tool and limits fraud exposure. Cost: large gifts are excluded.
2. **Verified accounts only:** Sender, receiver and merchant must all be KYC-verified. Cost: friction at claim. Mitigation: light KYC at claim, full KYC later.
3. **Merchant payments only (P2M):** Voucher balance cannot be sent to a person's QR, which closes the cash-out loophole where a friend scans a personal QR to turn a voucher into cash.
4. **Gate on business verification, not account type:** Many small shops use savings-account QRs, so requiring a current account would miss target merchants.
5. **Rollover framed as value kept:** Revenue comes from the user later spending Play balance, not from keeping the unused amount.

### Success Metrics
- **North Star:** Activated receivers per 100 vouchers sent.
- **Secondary:** Claim rate within 7 days; auto-refund rate; merchants displaying the sticker; redemptions per merchant per month; repeat senders per festival; Family Circle credits issued.
- **Guardrails:** Cash-out attempt rate; complaint rate; KYC drop-off at claim.

### Rollout & Validation
1. Pilot Money Voucher only, in one state, around one festival.
2. Add Gift Voucher with 5 to 10 brands.
3. Add verified-merchant redemption and Family Circle.

---

## Case 2: Google Search Campus Guild

### Overview
A micro-annotation programme where college students review and correct Search and Gemini answers in any language, using their own slang, and earn recognition instead of cash.

### Problem
- **AI misses regional nuance:** AI answers often miss real-world context, regional nuance and code-mixed language in every Indian language, such as Tanglish (Tamil mixed with English) or Hinglish (Hindi mixed with English).
- **Students create slang, raters do not:** The people who create current slang are students, but most formal review work is done in standardized language.
- **Quality data is slow and expensive:** Quality data in these languages is expensive and slow to collect.

### Users & Differentiator
- **Contributors:** College and school students fluent in any language, including regional and code-mixed ones.
- **Colleges:** Want credible, skill-building activities for students.
- **Google teams:** Need high-quality evaluation and training data for regional queries.
- **Differentiator:** The campus channel and the focus on code-mixed regional slang, not generic rating.

### Solution
- **Daily micro-tasks:** Each student reviews 10 to 15 queries a day and judges whether the answer matches real intent, correcting where it does not.
- **Consensus check:** 3 to 5 students rate the same query. Only agreed answers count.
- **Gold questions:** Items with known answers are mixed in to catch careless or spam submissions.
- **Incentives without cash:** An official contributor certificate at milestones, college-level points and leaderboards, and fast-track consideration for internships.
- **Privacy:** Students see anonymised sample queries only, never real user data.

### Key Decisions & Trade-offs
1. **Certificate instead of pay:** Cheap to run and good for résumés. Risk: unpaid-labour criticism and weak retention. Mitigation: opt-in, clear value exchange, and a pilot test of stipends if retention is low.
2. **Campus-first distribution:** Colleges provide trust and reach. Cost: academic-calendar seasonality.
3. **Language scope:** Open to every language from day one, with students choosing the languages they know. Quality is checked per language.

### Success Metrics
- **North Star:** Agreement-checked corrections per active student per week.
- **Secondary:** Annotator agreement rate; share of items passing gold questions; active students per partner college; 30-day retention; measured error-rate drop on a fixed test set per language.
- **Guardrails:** Privacy incidents; student workload hours; spam rate.

### Rollout & Validation
1. Pilot with 5 colleges in one state for one term, covering the languages those students use.
2. Compare corrected-data impact against a baseline test set.
3. Decide on stipends, new states and college partnerships based on retention.

---

## Case 3: YouTube Shorts Smart Bar

*Companion: Interactive 7-screen flow at [`shorts-app-flow.html`](https://ashokkumarone.github.io/Google-Product-Strategy-Cases/shorts-app-flow.html).*

### Overview
A redesign of the Shorts viewing screen around three ideas: a clean screen with one hidden options sheet, a Products drawer for commerce, and a top bar the viewer arranges themselves.

### Problem
- The player is cluttered compared with competing short-video apps, with many icons competing for attention.
- The existing menu already contains a Clear Screen option, which suggests the clutter is acknowledged but the fix is buried.
- Heavy viewership has not translated into strong ad revenue per view.
- Shady or adult ads push away family audiences.
- The feed is hard to steer toward what a viewer wants.

### Users
- **Viewers:** Browse one-handed on a phone and want an uncluttered screen.
- **Creators:** Want to earn from products they already show in videos.
- **Brands:** Want safe, high-intent placements.

### Solution
1. **Smart Bar (clean UI):** Bottom bar with Home, Comments, Create (+), Search, and an arrow. All main actions sit in the thumb zone. The arrow opens a white sheet with Save, Description, Captions, Quality, Not interested, Hide channel, Report and Feedback. Tapping the video closes it. Remix is merged into Create because both capture video. Save and Watchlist become one Save (Watch later, with an option to choose a playlist). Share stays visible in the title row. The profile moves to top right.
2. **Like interaction:** Double-tap likes. The heart turns from outline to red, beats for a few seconds, and sends hearts floating up the right edge.
3. **Products drawer:** A Products chip appears under the title only when items are tagged or detected. Creator-tagged items earn higher affiliate commission. Untagged items can be matched by visual recognition and linked to partner shopping apps.
4. **Personal top bar:** Default chips (Food, Tech) plus a plus button. Viewers add states or interests such as Tamil Nadu and arrange them in their own order.
5. **Brand safety:** Stricter moderation on adult or shady ads and a one-tap Block Ad option.

### Key Decisions & Trade-offs
1. **Hide options, keep core ones visible:** Cost: lower discovery of hidden options. Mitigation: a first-time hint and a clear arrow.
2. **Share visible, Save inside the sheet:** Protects the viral loop while decluttering.
3. **Products chip only when relevant:** Avoids adding clutter to every video.
4. **User-arranged chips rather than fixed filters:** Gives control without a heavy settings screen.

### Success Metrics
- **North Star:** Watch time per session with no drop in share rate.
- **Secondary:** Share rate and save rate versus today; arrow open rate; Products chip tap rate and click-outs to partner apps; share of users who customise the top bar.
- **Guardrails:** Accidental-tap rate; ad complaint rate; creator earnings.

### Rollout & Validation
1. A/B test the Smart Bar layout with a small share of users.
2. Pilot the Products drawer with a few creators and shopping partners.
3. Test the personal top bar in one state.

---

## Case 4: Google Meet Couple Pack

### Overview
An OTT-branded Couple Pack, powered by Google Meet, that lets two people in different places watch the same show in sync with a simple video bubble.

### Problem
- Long-distance couples and friends who share a screen on Meet often hit a black screen because of content protection, and audio drifts out of sync.
- Third-party watch-party tools exist, but they need extensions, are unofficial and work poorly on TV and phone.
- Meet has no official way to co-watch in this way, so evening and weekend use stays low.

### Users & Partners
- **Couples and close friends in different cities:** In India this includes migrant workers and students away from home.
- **OTT platforms:** Want more subscribers and lower churn.
- **Google Meet:** Wants more non-work usage.

### Solution
- **Official partner integration:** Playback is synced by the OTT's own player, so there is no screen share, no black screen and no lag.
- **Couple Pack:** Sold by the OTT as a two-person plan (two linked profiles for long-distance pairs), with Meet as the co-watch layer.
- **Round video bubble:** The show plays full screen while the partner appears in a draggable round bubble. Audio ducks automatically when either person speaks.
- **Invite flow:** One person starts a session and the other joins through a link.

### Why the OTT Says Yes
- A second paying subscriber from the same household of interest.
- Lower churn, because couples who watch together stay subscribed longer.
- A long-distance segment that is not served well today.

### Key Decisions & Trade-offs
1. **Partner-led instead of Google charging per movie:** Removes the hard sell of an extra fee on top of a subscription. Cost: revenue depends on OTT agreements.
2. **Start with mid-size Indian OTTs:** They are hungry for subscribers, then approach larger platforms.
3. **Pricing as a test:** Price points are decided in the pilot, not fixed now.
4. **UX first:** The bubble and audio ducking are the strongest differentiator and can ship even before pricing is final.

### Success Metrics
- **North Star:** Active couple pairs per month.
- **Secondary:** Sessions per pair per month; average session length; churn of paired accounts versus solo accounts; conversion of the second profile.
- **Guardrails:** Sync failure rate; support tickets; partner satisfaction.

### Rollout & Validation
1. Pilot with one OTT on one corridor (for example Chennai and Bangalore) during a festival week.
2. Measure pair activation, sessions and churn against a control group.
3. Use the results to approach larger OTT platforms.

---

## Why These Four Matter for Google

| Case | What Google Gains | Main Lever |
|------|-------------------|------------|
| **1. Gifting Vouchers** | New activated receivers, festival-season engagement, a wider verified-merchant footprint, Play spend commission | Payments growth |
| **2. Campus Guild** | Low-cost multilingual evaluation data, better Search and Gemini answers for Indian users, an internship talent pipeline | Product quality and talent |
| **3. Shorts Smart Bar** | Commerce revenue, longer and cleaner sessions, safer inventory for premium advertisers | Monetization |
| **4. Couple Pack** | Non-work Meet usage, recurring revenue share with OTT partners | Engagement and partnerships |

### What the Four Share
- **India-first insight:** Festivals and moi culture, regional languages, local merchants, migrant families.
- **Built-in growth loops:** A voucher onboards the receiver, a contributor brings classmates, a creator tag feeds commerce, a pair needs two accounts.
- **Trust by design:** Verified accounts and caps, anonymised data, brand-safety controls, partner-led integrations.
- **Small first steps:** Every case ends with a pilot small enough for one team to run.

### Suggested Sequence
1. **Shorts Smart Bar and Gifting Vouchers first:** Closest to revenue and engagement, and Shorts changes can be A/B tested quickly.
2. **Campus Guild next:** A low-cost pilot with a few colleges.
3. **Couple Pack last:** Depends on OTT partner agreements.

---

## About the Author
**Ashokkumar S**  
Associate Product Manager · Product Analyst  
- [LinkedIn Profile](https://linkedin.com/in/ashokkumarone)  
- [GitHub Profile](https://github.com/ashokkumarone)  
- Other projects: [Tuning Music](https://ashokkumarone.github.io/Tuning-Music/) · [Flux](https://ashokkumarone.github.io/Flux/)

*Disclaimer: These are concept proposals written from an outside observer's point of view. Not affiliated with or endorsed by Google.*
