# Business-Prompt Library
A collection of production ready LLM prompts for business use across industries.

# 1) Tech Startup — 12-Month Product Roadmap
Role: Tech Startup Product Strategist
Task: Create a detailed 12-month product roadmap that prioritizes features for MVP, growth, and scalability.
Context: Early-stage SaaS with a small dev team (5 engineers), limited runway (12 months), pilot customers from two industries, and priority KPIs: activation, retention, and MRR.
Reasoning: A prioritized roadmap aligns engineering, sales, and investors on achievable milestones and clarifies resource trade-offs under a tight runway.
Output Format: Quarter-by-quarter roadmap (Q1–Q4) with 3–6 deliverables per quarter. For each deliverable include: objective, key features, owner (team), estimated effort (low/med/high), success metrics, and dependencies. Conclude with a 1-paragraph risk/mitigation summary.
Stop conditions: Stop when all four quarters are filled; each deliverable has objective, owner, effort, metric; and at least three risks with mitigations are listed.

# 2) Tech — AI Feature Specification (LLM Integration)
Role: AI Product Manager
Task: Produce a product spec for integrating an LLM-powered assistant into an existing web app.
Context: Mid-market B2B app aiming to add contextual help, automated summaries, and a chat interface. Requirements: data privacy, latency <1s for simple queries, ops budget capped.
Reasoning: A concise spec ensures engineering, legal, and design teams agree on scope, constraints, success criteria, and rollout plan.
Output Format: Feature spec with: user stories, acceptance criteria, API/data flow diagram described in text, privacy considerations, performance targets, rollout phases (beta/public), monitoring & fallback plan.
Stop conditions: Stop when user stories, acceptance criteria, performance/privacy constraints, and rollout phases are all specified.

# 3) Stock Market — Medium-Risk Portfolio Strategy
Role: Financial Analyst / Portfolio Advisor
Task: Create a 5-year medium-risk investment portfolio and rebalancing plan.
Context: Client age 35–45, time horizon 5 years, moderate risk tolerance, initial investable capital = PKR-equivalent of $100,000, prefers low-cost ETFs plus selective equities.
Reasoning: A structured portfolio and periodic rebalancing provide steady growth while controlling downside risk.
Output Format: Asset allocation table by percentage (equities, bonds, cash, alternatives), top suggested instruments per asset class with rationale, annual rebalancing rules, tax/fees considerations, and a stress-test scenario paragraph.
Stop conditions: Stop when asset allocation + instrument choices + rebalancing rules + one stress-test are provided.

# 4) Stock Market — Quarterly Earnings Analysis & Trade Idea
Role: Equity Research Analyst
Task: Analyze a company’s upcoming quarterly earnings and produce a short trade thesis (buy/hold/sell) with risk factors.
Context: Public company with visible revenue growth but margin compression; analyst has access to last four quarters of financials and industry comps.
Reasoning: Earnings event can create price dislocations; a concise thesis guides decision-making and risk management.
Output Format: One-paragraph summary of expectations, 3 key financial drivers to watch, valuation check vs comps, recommended trade (action, time horizon, position size rationale), and 3 stop-loss/exit rules.
Stop conditions: Stop when thesis, drivers, valuation comparison, trade recommendation, and exit rules are provided.

# 5) Restaurant — Menu Redesign & Pricing Strategy
Role: Restaurant Profitability Consultant
Task: Redesign the menu to improve margins and increase average check.
Context: 60-seat casual-dining restaurant with declining margins; historical sales data available showing top 10 selling items and food-cost percentages.
Reasoning: Menu engineering (pricing, placement, combos) can steer customers toward higher-margin items without sacrificing brand.
Output Format: Redesigned menu layout (categories + 6–10 recommended items each), suggested price points with markup rationale, 4 high-margin add-ons/combo ideas, and a simple AB-test plan to validate changes over 8 weeks.
Stop conditions: Stop when menu list, pricing rationale, combos, and an AB-test plan are included.

# 6) Restaurant — New Location Feasibility Study
Role: Restaurant Expansion Analyst
Task: Produce a feasibility study for opening a new location.
Context: Single profitable location wants to open a second outlet in a neighboring district; parameters include: expected monthly rent, projected foot traffic, target demographics.
Reasoning: Feasibility reduces risk by quantifying revenue potential, costs, and break-even timeline.
Output Format: Executive summary, revenue/cost model (monthly 18-month projection), break-even month, SWOT analysis, and 3 go/no-go criteria.
Stop conditions: Stop when projections, break-even, SWOT, and clear go/no-go criteria are presented.

# 7) Supermarket / Retail — Weekend Foot Traffic Campaign
Role: Retail Marketing Strategist
Task: Design a weekend-focused marketing campaign to increase in-store visits and basket size.
Context: Local supermarket with modest social presence and a loyalty program but flat weekend sales. Budget: small (PKR-equivalent $1,000) for a 4-week campaign.
Reasoning: Targeted promotions, localized ads, and loyalty incentives can shift weekend behavior and measurably grow sales.
Output Format: Campaign concept, 3 promotional offers, channel plan (social/WhatsApp/flyers), sample copy for each channel, timeline, and simple KPIs to track.
Stop conditions: Stop when offers, channel plan, sample copy, timeline, and KPIs are provided.

# 8) E-commerce — Customer Retention Playbook
Role: E-commerce Growth Lead
Task: Develop a 90-day retention playbook to increase repeat purchase rate.
Context: Online store with high first-time buyers, low repeat rate (20%), monthly marketing budget limited. Key touchpoints: email, SMS, and on-site personalization.
Reasoning: Structured retention tactics (welcome flows, post-purchase, win-back) raise LTV and reduce CAC over time.
Output Format: 90-day calendar of actions (day 0, 1, 7, 30, 60), templates for emails/SMS, loyalty program mechanics, metric targets, and A/B test ideas.
Stop conditions: Stop when 90-day calendar, message templates, loyalty design, and measurable targets are all specified.

# 9) E-commerce — Product Listing SEO & Conversion Copy
Role: E-commerce SEO Copywriter
Task: Create an SEO-optimized product title, bullets, description, and 1 social caption for a product page.
Context: Single product (consumer electronics accessory) selling on own site and marketplaces; target keywords provided. Conversion focus: improve CTR and add-to-cart rate.
Reasoning: Clear, keyword-aligned copy increases discoverability and conversion by matching search intent and highlighting benefits.
Output Format: One SEO title (max 80 chars), 5 bullets (benefits + features), 150–250 word product description (includes target keywords naturally), and one 30–60 char social caption. Also include 3 suggested alt-text ideas for images.
Stop conditions: Stop when title, bullets, description, caption, and alt-texts are provided.

# 10) Real Estate — Rental Investment Analysis
Role: Real Estate Investment Analyst
Task: Assess a rental property opportunity and recommend whether to buy.
Context: 3-bedroom apartment in an urban area, purchase price PKR X, projected monthly rent PKR Y, local vacancy rates known, financing option available at Z% interest.
Reasoning: A quantitative model with clear assumptions reveals cash flow, cap rate, ROI, and downside scenarios.
Output Format: One-page investment memo: purchase assumptions, 5-year cash-flow projection summary, cap rate, cash-on-cash return, sensitivity analysis (best/expected/worst), and recommendation with rationale.
Stop conditions: Stop when memo includes projections, returns, sensitivity analysis, and a clear buy/hold/sell recommendation.

# 11) Healthcare — Small Clinic Operational Optimization
Role: Healthcare Operations Consultant
Task: Recommend operational changes to reduce patient wait time and improve throughput.
Context: Small outpatient clinic with average wait time 60 minutes, 4 doctors, and limited space. Data includes daily patient volumes and appointment/no-show rates.
Reasoning: Process and scheduling changes can improve patient experience and increase daily capacity without new hires.
Output Format: Top 6 recommended changes (scheduling, triage, staffing mix, digital check-in), estimated impact on wait times, simple implementation steps, and KPIs to monitor.
Stop conditions: Stop when 6 recommendations + expected impact + implementation steps + KPIs are provided.

# 12) Education — Online Course Launch Plan
Role: Online Course Product Manager
Task: Create a go-to-market plan for launching a paid online course.
Context: Subject-matter expert building a 6-module professional course aimed at early-career professionals; goal: 200 paid students in 3 months. Budget for ads: limited.
Reasoning: A clear GTM plan sequences content readiness, audience building, and conversion tactics to hit enrollment goals.
Output Format: Launch timeline (pre-launch, launch, post-launch), content checklist, marketing funnel (channels, creatives), pricing & discount strategy, and success metrics.
Stop conditions: Stop when timeline, funnel, pricing, and metric targets are specified.

# 13) Travel / Tourism — 7-Day Nature + Food Tour Package
Role: Travel Product Designer
Task: Design a 7-day curated tour package that blends nature experiences and local cuisine.
Context: Target customers: couples aged 25–45, mid-range budget, starting from a major city, wants a balanced mix of guided activities and leisure.
Reasoning: A themed package with clear daily itineraries and differentiators (local chefs, private guides) sells better and justifies premium pricing.
Output Format: Day-by-day itinerary with main activity, meal highlights, accommodation type, transport notes, price tier suggestions, and two upsell options.
Stop conditions: Stop when all 7 days have activities, meals, accommodation type, and price tier suggested.

# 14) Logistics — Last-Mile Delivery Route Optimization Plan
Role: Logistics Optimization Specialist
Task: Propose a plan to optimize last-mile routes to reduce cost per delivery and on-time rate.
Context: Urban delivery fleet of 15 vans, average 200 stops/day, peak congestion between 9–11am and 5–7pm, customers expect same-day delivery in city.
Reasoning: Routing improvements, time-window batching, and simple tech can reduce mileage and improve service levels.
Output Format: Optimization recommendations (routing algorithm types, batching rules, time-slot pricing, pickup/dropoff consolidation), estimated impact metrics, implementation roadmap, and required KPIs.
Stop conditions: Stop when recommendations, estimated impact, roadmap, and KPIs are provided.

# 15) HR / Recruiting — Scalable Hiring Plan for Early-Stage Startup
Role: Talent Acquisition Advisor
Task: Create a 6-month scalable hiring plan to grow from 12 to 25 employees while keeping culture intact.
Context: Seed-stage startup with priority hires in engineering, product, and sales; limited recruiting budget; founder-led hiring today.
Reasoning: A staged hiring plan with sourcing channels, interview process, and employer value proposition reduces time-to-hire and preserves culture.
Output Format: Hiring roadmap (month-by-month roles), sourcing channels per role, 6-step interview process template, offer negotiation guidelines, and cultural onboarding checklist.
Stop conditions: Stop when roadmap, channels, interview process, offer rules, and onboarding checklist are all defined.
