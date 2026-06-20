---
name: summer-income-planner
description: Use this skill to create practical 6-week summer income plans for students, freelancers, and side-hustle beginners, including weekly action steps, beginner-friendly offer ideas, simple trackers, outreach routines, and quality-control checklists. Trigger when the user asks for summer income ideas, a 6-week money plan, a student side-hustle plan, a freelance starter plan, or a short-term income roadmap. Do not use to promise earnings, guarantee clients, replace professional financial, legal, or tax advice, or recommend unsafe, illegal, deceptive, or age-restricted work.
---

# Summer Income Planner

## Purpose

Help an agent turn a user's skills, available time, constraints, and short-term goal into a practical 6-week summer income plan.

The plan can include:

- Best-fit offer ideas for students, freelancers, and side-hustle beginners.
- A 6-week roadmap with weekly action steps.
- Simple outreach, delivery, admin, and review routines.
- Trackers for time, outreach, leads, tasks, actual income, expenses, and lessons learned.
- Quality-control checklists for offer clarity, safety, delivery, customer communication, and end-of-week review.

The skill must keep income goals framed as planning targets, not promises. It must never guarantee earnings, clients, business success, or return on effort.

## When to use

Use this skill when the user asks for help such as:

- "How can I make money this summer?"
- "Make me a 6-week summer income plan."
- "I am a student and need a side hustle plan."
- "Help me turn my skills into a short-term freelance offer."
- "Give me weekly steps, offer ideas, and a tracker."
- "I have 5 to 10 hours a week and want a realistic plan."
- "Build a beginner side-hustle roadmap without hype."

Also use it when the user has a short seasonal window and needs a structured plan for testing offers, doing outreach, delivering work, improving quality, and tracking actual results.

## Do not use

Do not use this skill when:

- The user wants guaranteed earnings, guaranteed customers, or business-success promises.
- The user asks for investment, trading, gambling, crypto speculation, or high-risk financial tactics.
- The user asks for regulated professional advice such as legal, tax, accounting, medical, immigration, or licensed financial advice.
- The request involves unsafe, illegal, exploitative, deceptive, spammy, or age-restricted work.
- The plan would require collecting sensitive personal data, bank logins, account credentials, exact home addresses, Social Security numbers, government ID numbers, or private school or employer records.
- The user needs emergency support for basic needs, debt, housing, food, or safety. In those cases, provide a brief practical response and suggest appropriate local support resources rather than a side-hustle plan.

## Required inputs

Use information the user already gave. Ask only for missing information that is essential. If the user wants a quick answer, proceed with reasonable assumptions and label them.

Recommended inputs:

- User type: student, freelancer, side-hustle beginner, or other.
- Goal: desired outcome or planning target. Treat dollar amounts as goals, not guarantees.
- Timeline: default to 6 weeks unless the user gives another window.
- Available time per week and any schedule constraints.
- Skills, experience, interests, credentials, tools, transportation, and workspace.
- Preferred work style: online, local, solo, team-based, creative, physical, service-based, product-based, or tutoring/coaching.
- Starting budget and materials already available.
- Location or broad region only when local rules, safety, seasonal demand, or pricing matter.
- Age bracket when relevant to work eligibility, safety, payment setup, or transportation. Do not ask for exact date of birth.
- Constraints: exams, family duties, health limits, safety boundaries, no in-person work, no phone calls, no cold outreach, etc.

Default assumptions when inputs are sparse:

- Timeline: 6 weeks.
- Time: 5 to 10 hours per week.
- Budget: low or no upfront budget.
- Experience: beginner unless stated otherwise.
- Strategy: test 1 to 3 simple offers before scaling effort.
- Safety: avoid risky in-person work, age-restricted work, high upfront costs, and deceptive tactics.

## Workflow

1. Confirm scope and guardrails.
   - State that the plan is practical planning support, not an earnings guarantee.
   - Treat income targets as planning targets and track actual outcomes separately.
   - Reject unsafe, illegal, deceptive, spammy, age-restricted, or regulated work.

2. Build an intake snapshot.
   - Summarize the user's skills, time, budget, goal, constraints, and preferred work style.
   - List assumptions clearly if key details are missing.
   - If local laws, platform policies, current prices, or current market conditions matter, use reliable current sources when available and cite them.

3. Translate constraints into plan criteria.
   - Estimate weekly capacity in hours.
   - Identify low-risk, low-cost offer categories that match the user's skills and access to potential customers.
   - Prioritize offers that can be tested quickly, delivered safely, and improved with feedback.

4. Generate offer ideas.
   - Provide 5 to 10 offer ideas unless the user requests fewer.
   - For each idea, include target customer, simple offer wording, required setup, why it fits, risks or constraints, and a first validation step.
   - Include both online and local options when appropriate.
   - Avoid get-rich-quick models, fake reviews, academic dishonesty, spam outreach, resale schemes that require large upfront spend, and anything that depends on misleading claims.

5. Select the primary plan.
   - Recommend 1 primary offer and 1 backup offer, or 2 to 3 parallel micro-tests if the user has enough time.
   - Explain selection using fit, safety, time to first test, budget, customer access, and delivery complexity.

6. Create the 6-week roadmap.
   - Week 1: choose offer, define customer, set up basic materials, create tracker, draft outreach, complete safety check.
   - Week 2: validate demand with small, respectful outreach or warm-network conversations; refine offer based on responses.
   - Week 3: deliver first small projects, pilots, or practice samples; collect feedback with permission.
   - Week 4: improve workflow, quality checklist, pricing structure, and referral ask; continue outreach.
   - Week 5: repeat what worked, reduce friction, document process, and build simple proof such as portfolio snippets or testimonials with permission.
   - Week 6: review results, calculate actuals, decide whether to continue, pause, raise scope, change offer, or turn the work into a school/freelance portfolio asset.

7. Write weekly action steps.
   - For each week, include objective, time budget, tasks, outreach or customer-discovery actions, delivery actions, admin actions, and end-of-week review questions.
   - Keep actions specific enough to execute without implying guaranteed outcomes.
   - Include scripts or message templates only when they are respectful, truthful, personalized, and not spammy.

8. Add trackers.
   - Include tracker fields for week, date, hours planned, hours done, offer tested, outreach count, conversations, leads, projects, tasks, actual income, expenses, net actual, blockers, lessons, and next action.
   - Separate target, estimate, and actual columns whenever money is involved.
   - Use Markdown tables by default; provide CSV columns when the user wants a spreadsheet-ready version.

9. Add quality-control checklists.
   - Offer clarity: who it helps, what is delivered, when it is delivered, and what is not included.
   - Safety and compliance: age, local rules, transport, payment method, in-person boundaries, platform rules, and data privacy.
   - Delivery quality: scope, deadline, communication, review process, revisions, file handoff, and customer confirmation.
   - Outreach quality: truthful, personalized, non-pushy, no fake scarcity, no income claims, and easy opt-out.
   - Weekly review: actuals, feedback, blockers, next experiment, and whether to continue, adjust, or stop.

10. Final review.
    - Check that the final answer is practical, beginner-friendly, time-boxed, safe, and aligned with the user's constraints.
    - Remove hype, guarantees, pressure tactics, and exaggerated claims.
    - Include a note that outcomes depend on execution, demand, local rules, timing, and fit.

## Output format

For a complete plan, use this structure:

1. Safety and assumptions note.
2. Intake snapshot.
3. Best-fit offer menu.
4. Recommended primary offer and backup offer.
5. 6-week roadmap table.
6. Weekly action steps.
7. Outreach or customer-discovery scripts, when useful.
8. Trackers in Markdown or CSV-ready format.
9. Quality-control checklist.
10. End-of-week review prompts.
11. Next-step recommendation for what to do first today.

For a lightweight response, provide:

- 3 to 5 offer ideas.
- A compact 6-week roadmap.
- A simple tracker.
- A short quality-control checklist.

## Quality checklist

Before finalizing, confirm that:

- The plan covers exactly 6 weeks unless the user requested a different period.
- Weekly steps are concrete and realistic for the user's stated time budget.
- Offer ideas match the user's skills, tools, budget, age or safety constraints, and customer access.
- Income goals are framed as planning targets, not promises.
- Actual income and expenses are tracked separately from targets or estimates.
- The plan includes offer ideas, weekly actions, trackers, and quality-control checklists.
- The plan avoids unsafe, illegal, deceptive, spammy, age-restricted, or regulated work.
- The plan avoids confidential data collection and risky payment instructions.
- Any local, legal, platform, or pricing claims are current or clearly labeled as assumptions.
- The language is direct, practical, and hype-free.

## Safety and privacy

- Do not promise earnings, clients, profits, conversion rates, or business success.
- Do not tell users they will make a specific amount of money.
- Do not provide legal, tax, accounting, investment, medical, or licensed professional advice.
- Do not encourage scams, fake reviews, academic dishonesty, spam, misleading outreach, illegal resale, unsafe labor, or evasion of platform rules.
- For minors or younger students, recommend checking local work rules and involving a parent, guardian, school counselor, or trusted adult for payment setup, transportation, and in-person work.
- Avoid recommending in-person meetings alone, sharing exact home addresses, or transporting strangers.
- Do not ask for or store sensitive personal information, credentials, private IDs, bank logins, or unnecessary personal records.
- Keep all templates and scripts deterministic, non-destructive, and free of secrets.
