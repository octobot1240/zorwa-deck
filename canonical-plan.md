# Zorwa Canonical Plan v2

March 6, 2026
Owner: Thiago Oliveira

This is the single execution document. Everything else is reference material.

Previous versions stay intact for traceability. This one supersedes all of them.

# 0. Assumption Dashboard

These are the variables. Change any of them and the rest of the plan adapts. The framework below is built on rules, not on fixed numbers.

| Variable | Current Setting | Test Range | Decision Rule |
|---|---|---|---|
| Annual price (USD) | 150 | 150 to 249 | Experiment 1 picks the winner by revenue per 100 trials |
| Trial duration (days) | 14 | 7 to 14 | Experiment 3 picks shortest window that doesn't hurt conversion |
| Monthly fallback price | TBD | 19.99 to 29.99 | Only shown after annual decline or as secondary on pricing page |
| Trial-to-paid floor | 12% | 8 to 30% | Below 8% for 2 iterations triggers pivot discussion |
| D30 retention floor | 20% | 15 to 40% | Below 15% triggers product loop fix before any acquisition spend |
| Paid media CAC ceiling (USD) | 120 | 80 to 150 | Any channel above ceiling for 2 consecutive weeks gets cut 30% |
| Launch window | Sep to Oct 2026 | Jun to Dec | Moves based on crisis resolution scenario and beta gate results |
| Primary market | UAE + Riyadh | UAE, KSA, broader GCC | Riyadh added at launch only if beta validates localization |
| Year 1 paid user target | 5K to 25K | Scenario-driven | Conservative 5K, Optimistic 15K, Moonshot 25K |
| Total Year 1 investment (AED) | 3.27M | 2.5M to 4M | Spend follows signal. Never scale with weak conversion. |

How this dashboard works: every section below references these variables with "if/then" logic. If the price changes from 150 to 199, you don't rewrite the plan. You update the dashboard, and the decision rules throughout still hold.

# 1. The Bet

30 seconds. If you read nothing else, read this.

Zorwa is a Gulf-specific career acceleration platform with gamification. The bet: job seekers in a market where ~285 people apply for the same role (and climbing during crisis) will pay $150/year for coaching that improves their odds.

Three things make this bet asymmetric:

1. GRG's 600K candidate database and 210 recruiters give us Day 1 distribution that no startup can replicate.
2. The current Gulf crisis increases career anxiety, which means higher demand for career tools and lower acquisition costs. Every crisis in the last 30 years has triggered education enrollment surges.
3. Nobody operates a gamified career acceleration platform in the Gulf. 16 competitors benchmarked. None have our combination of regional intelligence, recruiter network, and daily practice mechanics.

Core line: the crisis creates the audience. The recovery creates the revenue.

# 2. Market Reality

## 2.1 The numbers

| Data Point | Value | Confidence | Source |
|---|---|---|---|
| Applications per job listing, Dubai | ~285 in normal periods | B | LinkedIn data, Gulf News |
| LinkedIn members in GCC | ~25M (UAE 9.7M + Saudi 11.3M) | B | Apollo Technical, 2026 |
| GCC HR Tech market size (2023) | $2.56B, growing to $5.48B by 2032 | B | Industry reports |
| UAE cost per hire | AED 8K to 35K | B | Local market data |
| Active job seekers annually in GCC | ~3 to 5M | C | Estimate from LinkedIn + job board data |
| Professionals already paying for LinkedIn Premium Career in GCC | ~140K (estimated) | C | Derived from global penetration rates |
| LinkedIn Premium Career price | $360/year | A | LinkedIn pricing page |

Key point: 140K people in the GCC already pay $360/year for generic LinkedIn Premium Career. We offer Gulf-specific coaching, gamification, and recruiter integration at $150/year. 58% cheaper for something more relevant.

## 2.2 Crisis impact

Six historical benchmarks prove the same pattern. When labor markets tighten, demand for career development spikes.

| Crisis | What happened | Enrollment/demand change |
|---|---|---|
| COVID 2020 | Mass layoffs globally | Coursera +640% in 4 weeks. Udemy +425%. LinkedIn Learning 1.7M hours in one week. |
| 2008 Financial Crisis | Global recession | MBA applications +22%. Every recession since 1970 drove grad school enrollment up. |
| Employer behavior during recessions | Harvard/Fed study | Employers raised education requirements by one-third during Great Recession. |
| Dubai 2008 | Property crashed 50%, expats left | Population grew 30% within 5 years. Hiring exceeded pre-crisis peak by 2013. |
| Asian Crisis 1997 | 25M people laid off in Southeast Asia | Education enrollment rose in every affected country. China expanded university system. |
| Dot-com + 9/11 2001 | Combined economic + security shock | Graduate enrollment rose. Career services demand spiked. Recovery captured by those who invested during downturn. |

What this means for us:
1. Users start upskilling immediately during crisis, not months later.
2. Recovery hiring booms exceed pre-crisis levels.
3. Platforms that exist during the downturn capture the upswing.
4. The crisis makes Zorwa more strategically important to GRG: placement revenue drops during conflict, subscription revenue from Zorwa becomes a diversification hedge.

## 2.3 Three scenarios for timing

| Scenario | Probability | Description | Impact on Zorwa |
|---|---|---|---|
| Quick resolution | 35% | Ceasefire within 2 to 4 weeks. Markets normalize by May. | September launch still optimal. Beta could start earlier. |
| Extended tension | 45% | Sporadic activity 1 to 3 months. No ground ops in Gulf. Normalizes by Jul to Aug. | September is ideal. Build product and audience in the interim. |
| Major escalation | 20% | Sustained conflict 6+ months. Significant disruption. | Delay public launch to Q1 2027. Shift to KSA-first if UAE market shrinks. Content and beta only. |

Probability-weighted: 80% chance September 2026 launch is viable. 100% chance product development should continue now.

# 3. Product Architecture

## 3.1 Six modules

| Module | What it does | Retention mechanic |
|---|---|---|
| CV Studio | Audit mode for extraction and structuring. Tailor mode for role-specific optimization. | Users return every time they apply to a new role. |
| Interview Studio | Core HR prep, role-specific questions from CV context, post-interview feedback. | Practice sessions before every interview. |
| Job Hub | Full CV-to-JD fit analysis. LinkedIn-first ingestion with ATS sources in roadmap. Natural language search. | Daily job matching alerts. |
| Networking Hub | Weekly connection recommendations. Outreach message generation. Gmail workflow support. | Weekly nudges to expand network. |
| Personal Branding | Identity audit. Communication coaching. Profile perception guidance. | Ongoing profile optimization as career evolves. |
| Knowledge Hub | Expert content and curated learning. 5-minute daily learning loop. Personalized feed in roadmap. | Daily streak mechanic (Duolingo model). |

## 3.2 The Career Score (the long-term play)

The Career Readiness Score is the piece that makes everything compound.

How it works: a composite score based on CV quality, interview readiness, networking activity, skill development, and job market fit. Transparent components, but improving them requires using the product.

Why it matters:
1. It gives users a number to obsess over. "My score went from 62 to 78 this month."
2. It gives recruiters a signal to trust. GRG can prioritize high-score candidates.
3. If employers start referencing it in job listings (like IELTS for career readiness), it becomes a standard. Network effect kicks in.
4. More users generate more benchmarking data, which makes scores more accurate, which makes the score more valuable, which attracts more users.

This is the moat. Not the app. The data flywheel behind the score.

## 3.3 Product principles

1. Not a job board. Not AI doing everything for the user.
2. AI teaches and sharpens candidate quality. The user does the work.
3. Regional intelligence is the moat. Generic global templates are not competition.
4. Daily utility is mandatory for retention. If users don't open it daily, the habit loop is broken.
5. 60 to 70% proprietary GRG intelligence in workflows. This is what no competitor can replicate.

# 4. Business Model

## 4.1 Why annual-only, no free tier

| Free tier risk | Evidence |
|---|---|
| Anchors product at $0 value, users never upgrade | RevenueCat: free-to-paid is 1.5 to 2.7% from installs |
| Attracts low-intent users who inflate vanity metrics | ChartMogul: median B2C freemium conversion 3.8 to 5.0% |
| Support cost on free users burns cash for non-payers | Standard SaaS trap for pre-revenue companies |
| Harder to raise price later | "It was free, why pay now?" churn spike at monetization inflection |

| Annual plan advantage | Application to Zorwa |
|---|---|
| Immediate cash flow | Price per user upfront, no monthly billing friction |
| Zero churn for 12 months | First renewal is Month 12+. No monthly cancel risk. |
| Higher LTV | At 25% annual churn: LTV = Price / 0.25. At $150 that's $600. At $199 that's $796. |
| Signals commitment | Users who pay actually use the product and complete coaching |

Free tier is not off the table forever. It's an option held in reserve. If trial-to-paid falls below the floor after two product iterations, freemium becomes a test variable. Not a default.

Monthly is fallback, not hero offer. It exists as a safety net for users who resist annual commitment, but it's never the primary CTA.

## 4.2 Pricing experiments (pre-launch)

Four experiments, one variable at a time.

| Experiment | Question | Variants | Success metric | Decision rule |
|---|---|---|---|---|
| 1. Price sensitivity | Is current price the best opening annual price? | 150, 199, 249 | Revenue per 100 trials + retention | Pick strongest revenue per 100 trials with healthy D14 retention |
| 2. Positioning message | Which core message pulls strongest demand? | "Recruiter in your pocket 24/7" vs "Beat 285 applicants per role" vs "Built by GRG recruiters, not generic AI" | Landing page to trial start | Keep top two for segment-specific use |
| 3. Trial duration | What length gives best conversion quality tradeoff? | 7 days, 14 days | Trial-to-paid rate | Keep shortest window that doesn't hurt quality |
| 4. Monthly fallback | Where should monthly option appear? | After annual decline only vs visible on pricing page | Total paid conversion | Keep highest total conversion while preserving annual-first economics |

Minimum 300 trials per variant. Two full weekly cycles per test. CRM cohorts for warm traffic, organic for cold traffic. Holdouts for baseline.

## 4.3 Unit economics

| Metric | Value | Notes |
|---|---|---|
| Price | Dashboard variable (currently $150/year) | Annual-only |
| Annual churn at renewal | 25% modeled (conservative) | LinkedIn ~25 to 30%, Duolingo ~15% |
| LTV | Price / churn rate | At $150 and 25% churn = $600 |
| CAC: GRG CRM | $0 to 15 | Push notifications + recruiter referral |
| CAC: Organic/content | $20 to 40 | Social media + SEO + community |
| CAC: Recruiter affiliates | $30 to 45 | 20 to 30% commission on first year |
| CAC: Paid media UAE | $80 to 120 | Meta CPC AED 4.8 avg, Google higher |
| LTV:CAC blended | 5 to 20x | Healthy at all channel mixes |
| Payback period | Immediate | Annual upfront payment |

# 5. Distribution System

Six channels, exhaustive and non-overlapping. Each has an activation trigger, not a calendar date.

## Channel A: GRG CRM + Recruiter Outbound

Role: Primary demand capture. Highest trust. Zero acquisition cost.

Activation trigger: Product is testable end-to-end and CRM segments are defined.

| Parameter | Conservative | Optimistic |
|---|---|---|
| Active candidates pushed | 20,000 | 30,000 |
| Trial start rate (CRM push) | 20% | 30% |
| Trial-to-paid conversion | 20% | 30% |
| Paid users from CRM | 800 | 2,700 |
| Revenue from CRM | $120K | $405K |

KPIs: Reachable contact volume. Trial starts. Trial-to-paid by recruiter and segment. Revenue per segment.

## Channel B1: Organic Content

Role: Zero-cost audience growth. Captures career anxiety during crisis.

Activation trigger: Social Media Lead hired and content calendar approved.

Content engine: 3 to 5 posts/week across Instagram, TikTok, LinkedIn. Series concepts:
1. "How to stand out in a 400-applicant market"
2. "What recruiters in Gulf reject first"
3. "How to win interviews in a tight market"
4. Weekly "Gulf Job Market Intel" shareable infographic with Zorwa branding

KPIs: Weekly output. Qualified leads captured. Trial starts from content. Assisted conversion.

## Channel B2: Community Marketing

Role: Trust-based distribution through existing job seeker communities and career influencers.

Activation trigger: Product ready for early access. Influencer mapping complete.

Core thesis: career influencers like Aadhil (THE UAE HR, 120K LinkedIn followers) have audiences of exactly our target user. Frustrated, applying everywhere, getting ghosted. When someone like that recommends a tool, their audience doesn't question it. That credibility would cost thousands in ads, and people scroll past ads. They don't scroll past a recommendation from someone they follow.

Execution:
1. Map top 20 to 30 career content creators and community leaders in UAE and Saudi. LinkedIn, TikTok, Instagram, WhatsApp groups, Telegram channels.
2. Give them early access. Free Zorwa, let them play with it, form their own opinion. If the product is good, the content creates itself.
3. Selected partners get proper affiliate commission per signup.
4. Seed WhatsApp and Telegram job seeker groups (hundreds in UAE with 500 to 5,000 members each). Don't build our own community from zero. Show up in theirs.
5. GRG recruiters are already community leaders. Referral link makes them the most authentic distribution channel.

Sequence: community first to find working messages and angles, then scale with paid (Channel E).

KPIs: Influencer partners activated. Community-sourced signups. Community-to-trial-to-paid rate. CPA via community vs paid.

## Channel C: Recruiter Affiliate Network

Role: External distribution multiplier beyond GRG.

Activation trigger: Affiliate dashboard built and tested with 5 pilot recruiters.

Commission model: 20 to 30% of first year subscription.

KPIs: Active affiliates. Referred trial starts. Referred paid users. Commission-to-revenue ratio.

## Channel D: Referral Loop (Gamified Viral Engine)

Role: User-driven compounding. Active from Phase 1 via gamified waitlist.

Activation trigger: Waitlist system live with referral tracking.

Mechanics (see Race to the Peak strategy for full detail):
1. Every user gets a unique referral link on signup.
2. Points for referrals (+500), completing challenges (+200), social follows (+50), daily actions (+50/day).
3. Leaderboard: top 100 all-time, weekly top 20, city rankings (Dubai vs Riyadh vs Abu Dhabi).
4. Tier rewards: early beta access, free months, founding badges, recruiter intros, lifetime status.
5. Competitive triggers: "You're #847. Your friend just passed you." push notifications.

Anti-gaming: phone verification, IP cluster detection, quality gates (referred users must complete at least one action to count).

Viral coefficient target: 1.3+ (each user brings 1.3 new users on average).

KPIs: Invite rate. Invite-to-signup. Referral-to-paid. Share of total new paid users. Viral coefficient.

## Channel E: Paid Media

Role: Scaled growth only after message-market fit is proven.

Activation trigger: CRM and community channels demonstrate trial-to-paid above the floor for 2 consecutive weeks. Never before.

Spend control: hard CAC cap from dashboard. Any channel above ceiling for 2 weeks gets cut 30%. No exceptions.

Channels: Meta, Google, TikTok. KSA and UAE split. Messaging uses winners from Experiment 2.

KPIs: CAC by campaign. Trial quality. Trial-to-paid from paid traffic. Payback speed.

## Channel F: B2B Employer Lane

Role: Revenue diversification and strategic moat.

Activation trigger: 1,000+ active users generating engagement data worth selling to employers.

Model: employers pay for bulk licenses, candidate access, or sponsored content. Start with pilot conversations in beta phase. Don't force it before there's data to sell.

KPIs: Pilot count. Pipeline value. Signed contract value.

# 6. Growth Acceleration

## 6.1 Race to the Peak: Gamified Launch

Instead of a passive waitlist and a traditional launch, the entire lifecycle is a social game. This is on-brand because the product IS gamification.

Precedents:
1. Robinhood: 1M waitlist users pre-launch via gamified queue.
2. Harry's: 100K signups in one week via tiered referral rewards.
3. Dropbox: 3,900% growth in 15 months via referral program.

Phase 1 integration (build phase): Gamified waitlist with points, referrals, leaderboard. Users sign up, see their queue position, earn points by referring, completing career quizzes, following social, doing daily micro-challenges. Tier rewards unlock: beta access at 500 pts, 1 month free at 1K pts, founding badge at 2.5K pts, full year free + recruiter intro at 5K pts.

Phase 2 integration (beta): Top leaderboard users get beta access first. Beta users earn new points for completing onboarding, using features, giving feedback, reporting bugs, referring during beta. Top 50 become "Zorwa Ambassadors" with real perks. City vs city competitions: "Dubai has 2,340 climbers. Riyadh has 1,890."

Phase 3 integration (public launch): 7-day "Race to the Peak" launch sprint. Daily challenges tied to product features (Day 1: Career Score, Day 2: CV, Day 3: Interview, etc.). Daily leaderboard with daily prizes. Grand prize: top 10 get full year free. Conversion trigger: "Lock in your position with annual plan."

GRG CRM integration: CRM sends waitlist invites in waves. Wave 1 (1K): test mechanics. Wave 2 (10K): optimize. Wave 3 (50K+): full push with proven loop. Each wave measures signup rate, referral rate, daily engagement, quiz completion.

Budget: ~$7K total ($2K waitlist phase + $1.5K beta phase + $3.5K launch phase). Compare to $50K+ for a traditional paid launch campaign.

Tech: Viral Loops ($99/mo) for waitlist phase. Migrate to native when product launches. Don't build from scratch.

## 6.2 Growth operations model

Lucas Antunes owns complete growth operations. One senior operator with full AI tooling.

Scope: paid media setup and optimization, CRM automation and lifecycle flows, community marketing execution, referral and affiliate program ops, analytics infrastructure and dashboards, content distribution, growth experiment design and analysis.

Why one person instead of a team: pre-PMF stage needs speed and learning, not headcount. GRG funds the team but expects capital efficiency. AI tools in 2026 genuinely enable one person to run what took a team of 5 two years ago. Validate channels first, hire specialists when a channel proves ROI.

Success criteria: all active channels running without bottleneck. Minimum 2 to 3 experiments per week. Weekly dashboards with zero manual assembly. When a channel proves ROI, evaluate hiring a specialist.

# 7. Team and Operations

## 7.1 Team structure

| Role | Person | Start | Monthly Cost (AED) | Year 1 Cost (AED) |
|---|---|---|---|---|
| Head of Product and Growth (CPO) | Thiago | Month 1 | 45,000 | 540,000 |
| Head of Recruiter Ecosystem | Sara Heck | Month 1 | 30,000 | 360,000 |
| Growth/Data/CRM/Paid Media | Lucas Antunes | Month 1 | 45,000 | 540,000 |
| Social Media Lead | TBH (rockstar level) | Month 2 | 30,000 | 330,000 |
| Designer/UX (hybrid: UI + research) | TBH (Lucas has a lead) | Month 3 | 22,000 | 220,000 |
| External Agency | TBH (traditional mkt/events) | Month 4 | 20,000 | 180,000 |
| Dev team (6 engineers) | Already working | Month 1 | 132,000 | 1,584,000 (GRG-covered) |

Operating team Year 1: AED 2,170,000 (~$590K USD)
Dev team: GRG-covered separately

## 7.2 Operating cadence

| Cadence | What | Owner |
|---|---|---|
| Weekly | Product and growth review. Metrics dashboard. Sprint check. | Thiago |
| Weekly | Founder review with decision log | Thiago + Mark + Osama |
| Biweekly | Deep dive: retention, conversion, or channel performance | Thiago + Lucas |
| Monthly | Decision review: scenario update, assumption check, spend control | All founders |

## 7.3 Communication setup

1. GRG email for Thiago (pending setup).
2. Slack workspace for product and tech execution.
3. WhatsApp for broader team communication.
4. Trello board as external-facing strategy hub for founders and stakeholders.

# 8. Financial Model

## 8.1 Three scenarios

All scenarios use dashboard variables. Change the price and the revenue math adjusts. Change the conversion rate and the user count adjusts. The framework holds regardless of which numbers plug in.

Revenue formula: Paid Users x Annual Price = B2C Revenue. Plus B2B.

### Conservative: 5,000 paying users by Month 12

| Month | New paid | Cumulative | Cash (USD) |
|---|---|---|---|
| 1 to 3 | 0 | 0 | $0 (building) |
| 4 | 100 | 100 | 15,000 |
| 5 | 200 | 300 | 30,000 |
| 6 | 300 | 600 | 45,000 |
| 7 | 500 | 1,100 | 75,000 |
| 8 | 600 | 1,700 | 90,000 |
| 9 | 700 | 2,400 | 105,000 |
| 10 | 800 | 3,200 | 120,000 |
| 11 | 900 | 4,100 | 135,000 |
| 12 | 900 | 5,000 | 135,000 |

B2C: $750K. B2B: $50K. Total: $800K.
Channel mix: GRG CRM 60%, organic 25%, affiliates 15%.

### Optimistic: 15,000 paying users by Month 12

B2C: $2.25M. B2B: $200K. Total: $2.45M.
Channel mix: GRG CRM 30%, paid media 35%, organic 20%, affiliates 15%.

### Moonshot: 25,000 paying users by Month 12

B2C: $3.75M. B2B: $500K. Total: $4.25M.
Channel mix: GRG CRM 20%, paid media 40%, organic 15%, affiliates 15%, B2B enterprise 10%.

### Scenario comparison

| Metric | Conservative | Optimistic | Moonshot |
|---|---|---|---|
| Paying users M12 | 5,000 | 15,000 | 25,000 |
| Year 1 revenue | $800K | $2.45M | $4.25M |
| ARR at M12 | $750K | $2.25M | $3.75M |
| Trial-to-paid needed | 18% | 22% | 28% |
| Blended CAC | $40 | $55 | $75 |

## 8.2 Zero-paid-media acquisition (worst case floor)

Even without a single dollar of paid media, the math works:

| Channel | Conservative paid users | Conservative revenue | Optimistic paid users | Optimistic revenue |
|---|---|---|---|---|
| GRG CRM push | 210 | $31,500 | 1,013 | $151,875 |
| Recruiter personal outreach | 563 | $84,375 | 5,513 | $826,875 |
| Organic content | 90 | $13,500 | 440 | $66,000 |
| Total (no ads) | 863 | $129,375 | 6,966 | $1,044,750 |

Investment for zero-paid channels: ~$120K to $161K USD (CRM tooling + Social Media Lead salary + affiliate commissions).
Conservative ROI: 1.08x (break-even). Optimistic ROI: 6.5x.

The floor is break-even with zero ad spend. Everything above that is upside.

## 8.3 Break-even

| Definition | Monthly cost (AED) | Paying users needed |
|---|---|---|
| Operating break-even (ex-dev) | ~330,000 | ~7,200 |
| Full cost break-even (incl dev) | ~462,000 | ~10,100 |

Conservative scenario (5K users) has a small gap of AED 334K that closes in early Year 2 as the base renews at 75%. Optimistic and Moonshot are profitable in Year 1.

## 8.4 Total Year 1 investment

| Line item | Amount (AED) |
|---|---|
| Operating team | 2,170,000 |
| Paid media (activated only after gates pass) | 400,000 |
| Infra, tools, content, WhatsApp Business, legal, affiliates, contingency | 700,000 |
| Gamified launch (Race to the Peak) | 25,700 (~$7K) |
| Dev team | GRG-covered |
| Total | ~3,296,000 (~$897K USD) |

Spend follows signal. If channels don't validate, paid media budget doesn't get spent.

# 9. Execution Roadmap: 30-60-90-180-365

Each phase has entry criteria, actions, exit criteria, and kill rules. Phases advance based on gate results, not calendar dates. If a gate isn't met, the phase extends until it is or until the kill criteria triggers.

## 30 Days: Foundation and Instrumentation

Entry: Team hired, platform access granted, agency handoff started.

| Action | Owner | Success Signal |
|---|---|---|
| Complete core product (6 modules end-to-end testable) | Dev + Thiago | Full user journey works in staging |
| Ship gamified waitlist landing page with Viral Loops | Lucas + Dev | Live, tracking referrals, points system working |
| Set up measurement stack (trial start, conversion, D7/D14/D30 events, segment tags) | Lucas | All events firing correctly in analytics |
| Collect agency deliverables (UX flows, Customer.io maps, copy bank, design system) | Thiago | Full inventory with owners and status |
| Finalize brand guidelines and bilingual logo system | Robin + Designer | Approved guidelines, consistent across app/CRM/landing/social |
| Arabic-first onboarding QA and usability review | Dev + QA | QA complete, no blocking issues |
| GRG email and Slack workspace setup for Thiago | GRG ops | Access confirmed |
| Build recruiter affiliate dashboard (referral tracking and payout) | Dev | Tested with 5 pilot recruiters |
| Launch free career content on social (3 to 5/week) | Social Media Lead | Content calendar live, first week published |
| Map top 20 to 30 career influencers in UAE and Saudi | Lucas + Sara | List complete with reach, platform, engagement data |
| Build waitlist and intent capture from content | Lucas | Waitlist live, capturing emails + phones |
| Set up CRM segments for beta push (GRG database) | Sara + Lucas | Segments defined, push workflows ready |

Exit gate: End-to-end product flow stable. Instrumentation complete. Waitlist live with 1K+ signups. CRM segments ready. Brand guidelines locked.

Kill rule: if product is not testable end-to-end by Day 30, pause all GTM work and focus exclusively on product until it is.

Budget: Operating team costs only. No paid media. $297 for Viral Loops.

## 60 Days: Controlled Beta with GRG Segments

Entry: 30-day gate passed.

| Action | Owner | Success Signal |
|---|---|---|
| Send Wave 1 (1K candidates from GRG CRM) | Sara + Lucas | Measure signup rate, referral rate, quiz completion |
| Activate pricing experiment 1 (150 vs 199 vs 249) | Lucas + Thiago | 300+ trials per variant, clear winner emerging |
| Activate positioning experiment 2 (3 message variants) | Lucas | Landing page conversion data per variant |
| Start 5 to 10 influencer early access partnerships | Sara + Lucas | Influencers have access, first organic content appearing |
| Joint review call with agency, close integration gaps | Thiago | All artifacts received, gaps documented and assigned |
| Run D7/D14 retention analysis on first beta cohort | Thiago + Lucas | Cohort data available, trends visible |
| Send Wave 2 (10K candidates from GRG CRM) | Sara + Lucas | Optimize messaging based on Wave 1 data |
| Test recruiter personal outreach scripts | Sara | Response rates and trial starts by recruiter |
| Onboard first 20 external recruiter affiliates | Sara | Affiliates active, first referred trials coming in |

Exit gate: Wave 1 and 2 data analyzed. Pricing experiment has a leading variant. Trial-to-paid above the floor. D7 retention above 30%. CRM response rates above 15%.

Kill rule: if trial-to-paid stays below 8% after pricing adjustments, trigger pricing rethink or product pivot discussion with founders.

Budget: Operating team + CRM tooling (AED 5K/mo for WhatsApp Business + email platform) + influencer early access (no cost, just free Zorwa).

## 90 Days: Validation Sprint and Pricing Lock

Entry: 60-day gate passed.

| Action | Owner | Success Signal |
|---|---|---|
| Lock annual price based on Experiment 1 results | Thiago | Price decision documented with data |
| Run trial duration experiment (7 vs 14 days) | Lucas | 300+ trials per variant, conversion data clear |
| Run monthly fallback placement experiment | Lucas | Total conversion impact measured |
| D30 retention analysis on first cohorts | Thiago | D30 above floor (currently 20%) |
| Send Wave 3 (50K+ from GRG CRM) with proven messaging | Sara + Lucas | Full CRM push with optimized sequence |
| Activate recruiter affiliate network at scale (50+) | Sara | Affiliate-driven trials coming in consistently |
| WhatsApp/Telegram community seeding (10+ groups) | Lucas | Community-sourced signups measurable |
| Riyadh-specific coaching content and scoring checks | Thiago + Dev | KSA localization validated with small cohort |
| Early B2B pilot conversations with 3 to 5 employers | Thiago | Interest confirmed, pilot terms discussed |
| Publish KPI snapshot v1 for founders and GRG leadership | Thiago | Dashboard live, shared in weekly review |

Exit gate: Price locked. Trial duration decided. D30 retention above floor. Total paid users above 500. Clear data on which channels convert best. Riyadh readiness confirmed or deferred with reason.

Kill rule: if D30 retention below 15%, stop all acquisition and fix product value loop. If trial-to-paid below 12% after two iterations, revisit pricing and product with founders.

Budget: Operating team + CRM tooling + Wave 3 volume (all zero-paid-media costs).

## 180 Days: Public Launch into Recovery Wave

Entry: 90-day gate passed.

| Action | Owner | Success Signal |
|---|---|---|
| Public launch in UAE and Riyadh (if validated) | All | Live product, pricing locked, all channels active |
| 7-day "Race to the Peak" launch sprint | Lucas | 30%+ of signups participate, daily challenge completion tracked |
| Activate paid media with proven messaging and strict CAC caps | Lucas | Campaigns live, CAC below ceiling from Day 1 |
| Scale CRM, organic, affiliates, referral simultaneously | Sara + Lucas | All channels contributing, no single-channel dependency |
| Expand B2B pilots to 5 to 10 employers | Thiago | First B2B revenue or signed LOIs |
| Launch KSA features if Riyadh beta validated | Dev + Thiago | 20%+ of new users from KSA |
| Monthly operating review with scenario check | All founders | All metrics above kill thresholds |

Exit gate: 500+ new paid users in launch month. Blended CAC below ceiling. Retention stable. Multiple channels contributing. Path to operating break-even visible.

Kill rule: if paid CAC stays above ceiling for 4 weeks, cut paid 50% and shift to organic/CRM. If total paying users below 1,500 at this point, narrow scope to UAE-only and reduce team.

Budget: Full operating team + paid media (AED 400K budgeted for Month 4 to 12, but only activated here if gates pass) + launch event prizes (~$3.5K).

## 365 Days: Scale What Works

Entry: 180-day gate passed.

| Action | Owner | Success Signal |
|---|---|---|
| Scale proven channels only, kill underperformers | Lucas | Blended CAC healthy, no dead-weight channels |
| Expand B2B from pilots to pipeline | Thiago | $200K+ B2B pipeline |
| Year 1 retention cohort analysis and renewal preparation | Thiago + Lucas | Renewal rate tracking, churn predictions modeled |
| Evaluate Year 2 expansion (supply markets, enterprise seats, new verticals) | All founders | Data-driven expansion plan, not aspiration |
| Post-hire value tracks to reduce renewal churn | Dev + Thiago | Alumni features live (career growth, salary benchmarking) |
| Team scaling decisions: hire specialists for proven channels | Thiago | One hire per channel that proves ROI |

Exit gate: Year 1 revenue on track for scenario. Retention trend positive. Clear path to break-even within 3 months (if not already there). Expansion plan backed by data.

Kill rule: if no path to operating break-even by Month 15, renegotiate team size or pivot business model.

# 10. Risk System

## 10.1 Tigers (real threats that can kill the plan)

| Tiger | Owner | Mitigation | Decision Deadline |
|---|---|---|---|
| Conversion misses after two product iterations | Thiago | Test pricing variants, extend trial, add recruiter-boosted onboarding | 90-day gate |
| Retention collapses after first month | Thiago | Prioritize product loop fixes before any acquisition scale | 90-day gate |
| CRM data quality weaker than expected | Sara | A/B messaging, add recruiter personal outreach, segment by recency | 60-day gate |
| Regional disruption lasts beyond scenarios | Thiago | Content-only mode, shift KSA-first, reduce burn | Monthly scenario review |
| Agency deliverables incomplete or incompatible | Thiago | 2-week handoff sprint with acceptance checklist, escalate gaps to founders | 30-day gate |

## 10.2 Paper tigers (loud fears, low real impact)

1. Perfect brand polish before beta. Ship then iterate.
2. Waiting for perfect macro certainty. 80% is enough.
3. Over-focusing on vanity social metrics. Trial starts and paid users are what matter.

## 10.3 Elephants (issues teams avoid saying out loud)

| Elephant | Status | Resolution Plan |
|---|---|---|
| Pricing conviction is still fragmented across legacy docs | Being resolved via Experiment 1 | Data decides. Not opinions. 90-day gate. |
| Free tier debate is ideological, not test-driven | Parked as option with trigger rule | If trial-to-paid fails floor after 2 iterations, test freemium. |
| Some benchmark numbers have more confidence than data quality supports | Addressed via CoVe tags in Section 13 | Use confidence tags in all founder presentations. |
| GRG placement revenue drop during crisis creates internal pressure | Zorwa becomes diversification hedge | Position Zorwa as strategic revenue insurance in founder discussions. |
| Abdurrahman's role vs Thiago's: potential overlap | Needs explicit conversation | Recommend RACI matrix in first 30 days. |

# 11. Competitive Position

16 competitors benchmarked. None operate a gamified career acceleration platform in the Gulf.

| Competitor | Region | Price | Gamification | Gulf-specific | Recruiter Network |
|---|---|---|---|---|---|
| Bayt.com | GCC | Free (job board) | No | Partial | No |
| GulfTalent | GCC | Premium listing | No | Partial | No |
| LinkedIn Premium | Global | $360/yr | No | No | No |
| Teal | US | $9/week | No | No | No |
| Careerflow.ai | US | Free+ | No | No | No |
| VMock | US/Global | B2B | No | No | No |
| Kickresume | Slovakia | $60 to $120/yr | No | No | No |
| Interviewing.io | US | $200+/session | No | No | No |
| Handshake | US | Free (students) | No | No | No |
| Jobiri | Italy/EU | B2B2G | No | No | No |
| Naukri.com | India | Freemium | No | No | No |
| Rezi.ai | US | $29/mo | No | No | No |
| Final Round AI | US | $99+/mo | No | No | No |
| Big Interview | US | $79/mo | No | No | No |
| Yoodli | US/Global | Free (Google-backed) | No | No | No |
| aiApply | UK | $9.99/mo | No | No | No |
| Zorwa | GCC | $150/yr | Yes | Yes | Yes (GRG, 210 recruiters) |

Nobody has our three-way combination: gamification + Gulf-specific intelligence + recruiter network. Individual features can be copied. The combination with GRG's data and distribution cannot.

Additional competitive references:
1. Calvin James: validates paid candidate community model in GCC.
2. Job Direto (Brazil): R$10/referral affiliate model reference.

# 12. Open Decisions for Founders

These need explicit decisions before or during the first 90 days.

| Decision | Options | Recommendation | Deadline |
|---|---|---|---|
| Phase-based timeline and launch window | Confirm Sep to Oct 2026 or adjust | Confirm. 80% probability holds. | 30-day review |
| Beta database access scope and owner | Sara leads, with CRM team support | Confirm Sara as owner with defined segment access | 30-day review |
| Pricing test envelope | 150 to 249 range, annual-only | Confirm range. 150 is floor, 249 is ceiling. Data decides. | Pre-beta |
| Paid media activation rule | Only after CRM proves conversion above floor | Confirm. No premature spend. | 90-day gate |
| Who owns weekly operating review | Thiago chairs, founders attend | Confirm cadence and attendance. | Week 1 |
| Recruiter leaderboard: internal-only or public? | Internal for GRG recruiter competition | Start internal. Go public only if it amplifies brand. | 60-day review |
| Race to the Peak naming and prizes | $7K total budget across all phases | Approve budget and naming. | Pre-waitlist launch |
| GRG CRM wave testing sequence | 1K, 10K, 50K+ in controlled waves | Confirm sequence and volume access. | Pre-beta |
| RACI matrix for Thiago vs Abdurrahman | Define decision boundaries | Schedule explicit conversation in first 2 weeks. | Day 14 |
| Year 2 expansion direction | Supply markets, enterprise, new verticals | Not now. Revisit at 365-day gate with data. | Month 12 |

# 13. Source and Confidence Registry

Confidence tags: A = primary source or direct filing. B = strong secondary with cross-checks. C = directional estimate, use with caution.

### Crisis and demand behavior
| Source | Tag |
|---|---|
| Coursera COVID enrollment data | B |
| Udemy COVID growth | B |
| LinkedIn Learning usage spike COVID | B |
| MBA application surge 2008 (GMAC) | B |
| Harvard/Fed employer upskilling study (Review of Economics and Statistics, 2020) | A |
| Dubai post-2008 recovery pattern (Dubai Statistics Center, IMF) | B |
| Asian financial crisis education response (ILO, UNESCO, World Bank) | B |
| Dot-com + 9/11 career services demand (BLS, Pew, EPI) | B |

### Product and monetization
| Source | Tag |
|---|---|
| LinkedIn Premium revenue ($1.7B, 2024) | A |
| LinkedIn Premium subscriber count | C (not publicly disclosed, treat as estimate) |
| RevenueCat subscription/trial conversion data | B |
| ChartMogul conversion benchmarks | B |
| Duolingo engagement and paid model references | A to B |

### Market data
| Source | Tag |
|---|---|
| GCC HR Tech market size ($2.56B) | B |
| LinkedIn GCC member counts | B |
| Dubai applications per job (~285) | B |
| UAE cost per hire | B |
| GCC active job seekers (3 to 5M) | C |

Policy: competitor feature comparisons are valid for strategy. Revenue and user counts from secondary aggregators (Latka, Growjo, LeadIQ) are directional only until reconfirmed from primary sources. Any presentation to founders must tag confidence levels.

# 14. Document Map

| Document | Purpose | Location |
|---|---|---|
| Canonical Plan v2 (this file) | Single source of truth | This file |
| 30-60-90-180-365 Action Plan | Practical execution roadmap | zorwa-action-plan-30-60-90-180-365.md |
| Gamified Launch Strategy | Full Race to the Peak spec | zorwa-gamified-launch-strategy.md |
| Crisis Impact Assessment | 6 benchmarks, 3 scenarios | zorwa-crisis-impact-assessment.md |
| Strategic Plan v3 | Detailed financials and channel math | zorwa-strategic-plan-v3.md |
| Pricing Experiments v1 | 4 experiments with decision rules | zorwa-pricing-positioning-experiments-v1.md |
| Agency Integration Handoff | 4 tracks, 2-week sequence | zorwa-agency-integration-handoff-v1.md |
| Board Audit with CoVe | 54 cards classified, 23 attachments audited | zorwa-board-audit-cove-2026-03-03.md |
| Ideas Master | Running collection of ideas and options | zorwa-ideas-master.md |
| Trello Board | External-facing strategy hub | https://trello.com/b/5zNx6SPu |
| Prototype | Live gamification flow | https://octobot1240.github.io/massar-app/ |

# 15. Changelog

2026-03-03: v1 created. Legacy and reference logic integrated. Crisis meeting sequence embedded. CoVe confidence policy added.

2026-03-06: v2 created. Major changes:
1. Added Assumption Dashboard for plan flexibility. Framework now adapts to variable changes without rewrite.
2. All timeline logic converted from calendar dates to decision gate triggers.
3. Integrated gamified launch strategy (Race to the Peak) into Phase 1, 2, and 3.
4. Added Channel B2 (Community Marketing) with full execution plan.
5. Added Growth Operations model (Lucas as AI-first one-man army, Section 6.2).
6. Created 30-60-90-180-365 execution roadmap with entry/exit gates and kill rules.
7. Absorbed CPO Innovation Layer ideas: Career Score as long-term moat, community strategy, viral loop engineering, post-hire retention.
8. Absorbed crisis impact assessment into Market Reality section with confidence tags.
9. Absorbed pricing experiments into Business Model section.
10. Added zero-paid-media acquisition floor analysis.
11. Added all open founder decisions with deadlines and recommendations.
12. Added elephant: RACI for Thiago vs Abdurrahman.
13. Full competitive landscape with 16 benchmarks and CoVe policy.
14. Document map updated.
