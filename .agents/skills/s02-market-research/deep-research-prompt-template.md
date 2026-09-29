# R02 deep research prompt template

Fill this in after the learner approves the research brief, and save the result as `R02-deep-research-prompt.md`. A research sub-agent runs it and sees nothing else: not R01, not the brief, not this conversation. The finished prompt must stand on its own.

## How to fill it in

- **Copy the fixed text as written.** Replace every `<...>` with content for this learner's field, groups, and countries, and remove the brackets. You may add sentences or bullets, but never change or delete fixed text, a rule, or a heading. If a section truly does not apply, keep the heading and say why in one line.
- **Name real things, from what you know.** Where a slot asks for sources, platforms, communities, channels, tools, search phrases, claims, or misreadings, write the actual names you know for this field and these countries: "U.S. Small Business Administration, SCORE, and Small Business Development Centers", not "government programmes"; "r/smallbusiness and r/Entrepreneur", not "Reddit". A name is a place to check, not a finding, and the researcher confirms it. A wrong name costs one search; a generic category gives the researcher nothing to act on. Don't search to check names while writing.
- **Add method, never findings.** Add as many sources, tests, search phrases, and calculations as the decision needs. Do not write prices, statistics, market sizes, trends, or provider details.
- **Keep the approved scope.** The decision, groups, countries, and limits stay exactly as the brief says, and the brief's places not to enter are added to the research boundary. Do not add a group, country, or decision, and do not drop a limit.
- **Carry over everything in the brief.** Each group's research questions and likely evidence sources go into its group paragraph. The brief's source rules go into the research parameters. Anything the brief wants in the report beyond the standard sections goes into Required output.
- **Use only what R01 and the brief say about the learner.** For anything they don't state (a budget, working hours, time zones), write "not stated" and tell the researcher not to assume it.
- **Keep the learner's facts at their strength.** Unverified results stay unverified. Goals and price ideas are labelled as goals or guesses. The brief's labels ([Learner], [Unknown], and so on) don't go into the prompt; say each fact's strength in plain words. Describe clients without names or identifying details, and tell the researcher not to look them up.
- **"For example" lists are menus.** Keep what fits the field, drop the rest, and add what is missing.
- **The sample targets are fixed.** You can't know in advance whether a field is too small, so don't lower them; the researcher reports any shortfall and why.
- **Languages.** Write the prompt in the language the learner uses with you, unless they asked for the report in another. Search in every language the learner can serve these customers in, and say which customers that leaves out.

## Template

```markdown
# R02 Deep Research Prompt: <the decision, as a plain question>

Prepared: <date> · Based on: R01-capability-brief.md and R02-research-brief.md (approved <date>)
Status: Research prompt. It contains no findings. The course assistant's research sub-agent runs it, and the results go in R02-market-research-report.md.

---

# ROLE

Act as a combination of:

- Senior market researcher
- Buyer-behaviour analyst for <these customers>
- Competitive-intelligence researcher
- Small-business economics analyst for <this kind of service>
- Free-, AI-, and do-it-yourself-alternatives analyst
- YouTube, podcast, and online-community researcher
- Skeptical investigative journalist
- <Three to five more roles specific to this field, these customers, and these countries>

Your task is not to sell me on this idea, talk me out of it, or repeat generic statements such as <two or three clichés people repeat about this field>. Your task is to find out, from current real-world evidence, <the decision in one clause>.

# CENTRAL DECISION

As of the date this research is performed:

> <The decision from the brief, as one question.>

Answer these as separate questions for every group:

1. Do people in the group actually have <the problem>?
2. What makes it important enough for them to act, and how often does that happen?
3. Do they spend money on it, and on what: <the kind of help I offer>, or something else, such as <courses, software, credentials, done-for-you services, …>?
4. Do they pay enough to justify the selling, preparation, delivery, and support involved?
5. Can a new provider with <my actual proof> reach them and win their trust at a reasonable cost?
6. Which parts of this market are crowded, commoditized, or already handled well by free, AI, or do-it-yourself help?
7. Which parts still show paid demand that is not being met?
8. Does what they want fit my ability, my limits, and <my delivery format and capacity>?
9. What evidence would make this group a poor choice?
<Any further question the brief's decision needs.>

A large industry, many people talking about the problem, or many providers selling help does not establish demand for my specific service. The answer may be that no group qualifies yet.

# ABOUT ME: KEEP THESE FACTS AND LIMITS INTACT

- <What I can help with, and the experience behind it.>
- <My proof so far, and exactly how much of it is verified. Unverified results must not be presented as proof or generalised to other fields.>
- <What I will do, and what I will not do.>
- <Who I can serve: languages, countries, time zones, online or in person, delivery formats, hours per week.>
- <What customers must already be able to do or have.>
- <What is outside my experience or qualifications.>
- <Goals or price ideas I have mentioned, labelled as goals or guesses, not expected results.>
- <What counts as serious interest for me. Likes, views, follows, and compliments do not.>

# CUSTOMER-PROBLEM GROUPS TO COMPARE

<For each approved group:>
**<Letter>. <Type of person> · <their situation> · <the problem>.** <Why this group is here (its link to my experience); who counts as a strong fit and who to record separately; the triggers to test; the brief's research questions for this group; the alternatives to check; where the brief says evidence may be found.> Shortlist it only if <the brief's shortlist condition>. Set it aside if <the brief's reject condition>.

Treat every group as a hypothesis. If a person fits two groups, record their actual situation and count them once.

# RESEARCH PARAMETERS

- **Research date:** State the date the sources were checked.
- **Perspective:** A new provider, not an established brand, starting with <my proof>. <What R01 or the brief says about my time and budget; "not stated, do not assume" for anything they don't say.>
- **Customers:** <the groups, in one line>.
- **Markets:** <countries, or regions within a country if the brief splits them>, each reported separately. Do not transfer one market's prices, buying behaviour, purchasing power, rules, or competition to another. If a source does not show its country, write "Country unknown"; a currency symbol, a spelling, or a platform domain does not prove it.
- **Languages to search:** <the languages I can serve these customers in>. Report language: <language>. Note which customers this leaves out.
- **Period:** Prioritise the last 24 months <or the brief's period>. Use older sources only for trends or before-and-after comparisons, and label them.
- **Units:** Individual buyers and prospects, actual purchases, and competing offers. A person's repeated posts or reviews count once; reposts count as one underlying account.
- **Delivery formats to compare:** <my formats, plus the realistic alternatives, for example one-to-one, course plus feedback, group, self-paced, free help, AI-assisted self-help, and done-for-you services as a substitute I do not provide>.
- **Platforms and tools in this field:** <the platforms, marketplaces, software, and AI tools that customers and providers use>.
- **Research boundary:** Public material only: what can be read without joining, logging in, being approved or invited, or paying. Do not create accounts; sign up for trials, webinars, lead magnets, or waitlists; join groups; post; comment; message anyone; submit inquiry or booking forms; book calls; or pose as a buyer. <Places the brief says not to enter, if it names any beyond this rule.>
- **Text only:** Read web pages, documents, and transcripts. Never open a browser to play, stream, or watch a video; never listen to audio; and never take screenshots or screen recordings or use a video- or audio-analysis feature. These use huge amounts of usage and add nothing a transcript lacks.
- **My source rules:** <the brief's include and exclude rules>.
- **Prices:** Record what providers publicly charge and what buyers say they paid, with currency, country, and date. Do not choose my final price; that decision comes later.
- **Target outcome:** Decide which group(s), if any, deserve further investigation, which to set aside, and what evidence is still missing.

# REQUIRED RESEARCH STANDARD

This must be investigative research, not an internet summary.

Do not rely on SEO articles such as <four to six realistic titles in this field, for example "Is <field> still worth it in <year>?", "<N> <field> statistics you need to know", "How I made $10k a month as a <role>">. They can point to original sources; they are not evidence.

When a page cites a statistic, follow it to the original report, dataset, filing, or survey, and cite that. If the original cannot be read, say so instead of repeating the number.

Every source named in this prompt is a place to check, not a confirmed fact. Confirm that it exists and is current before relying on it, and say when one does not.

## Tier 1: Primary and high-reliability evidence

Prioritise these, checking the ones named:

- Official statistics on businesses, self-employment, and the occupations involved: <agencies in each country>
- Regulators, licensing or professional bodies for this work: <names, or "none known: confirm for each country">
- Consumer-protection enforcement actions and complaint records about this kind of service: <agencies in each country>
- Filings and investor reports of public companies whose platforms serve this market: <companies>
- Original surveys by governments, universities, or independent researchers that disclose their sample and method: <surveys or bodies>
- Official pricing and product pages: <platforms and tools>
- Public procurement, grant, or funded-programme records, if organisations buy this help: <portals in each country, or "not relevant" and why>

## Tier 2: Direct market observation

- Marketplaces, job boards, and request boards where people ask for this help and state budgets: <names>
- Expert or mentor marketplaces that show prices and review counts: <names>
- Course platforms and marketplaces that show enrolments, prices, and reviews: <names>
- Provider pricing pages, and their archived versions (Wayback Machine) to see price changes
- Review sites with verified buyers and stated prices: <names>
- Directories of providers: <names>
- Event and workshop listings with prices: <names>
- Ad libraries that show who is paying to advertise: Meta Ad Library, Google Ads Transparency Center
- Publicly visible offer pages, sales pages, booking pages, and profiles of prospective customers
- Keyword and trend tools, with their geography, period, settings, and units recorded: <names>

## Tier 3: Practitioner and buyer testimony

<Name them: subreddits, forums, public groups, public Discord or Slack archives, YouTube channels, podcasts, founder retrospectives, Indie Hackers or Hacker News threads.> These show triggers, objections, failed attempts, and operating reality. They are not a representative sample.

## Tier 4: Promotional or weak evidence

Treat cautiously: <this field's versions of course sellers and gurus, affiliate "best X" pages, provider testimonials, undocumented income screenshots, surveys by vendors or associations that sell to this market, generic market-size reports, and statistics copied across blogs>. Use them only when corroborated, or to analyse the industry's own narrative and incentives.

# RESEARCH FRAMEWORK

## Phase 1: Define the market properly

Before judging demand or crowding, split this market into the distinct things people buy or use instead:

<Ten to twenty offer types for this field, for example free content, templates, self-paced courses, cohort courses, paid communities, group coaching, one-to-one diagnosis, ongoing one-to-one guidance, done-for-you services, software, certification.>

Find out whether crowding, falling prices, and free or AI substitution affect all of these equally, or mainly the generic, low-complexity end.

Keep these separate throughout: "people have this problem" · "they want to fix it now" · "they will pay someone" · "they will pay enough" · "a new provider like me can reach them economically".

## Phase 2: Competing hypotheses

Investigate each fairly and state which evidence supports or weakens it.

- **A. Paid demand is real and reachable for a new provider**, because <five or more reasons specific to this field>.
- **B. The market is unattractive for a new provider**, because <five or more reasons specific to this field, for example free or AI help is good enough, providers are many and cheap, trust goes to established names, buyers want someone to do it for them, or reaching buyers costs too much>.
- <Any further hypotheses from the brief.>

Do not start from a preferred conclusion.

# DIRECT MARKET TESTS

For every test, report the sample reached against its target, the collection dates, the sources, and what could not be accessed. Do not treat a few convenient examples as representative. If a target cannot be met after focused searching, say how many qualified and why.

## 1. Buyer and prospect accounts

At least 20 independent first-person accounts per group, from at least three kinds of source, spread across <countries>. Record: link; date; country or "Unknown"; which group and why; stage and skills; problem; what made it urgent; what they tried; whether they sought feedback, bought guidance, bought something else, used free help, or did nothing; the amount paid, only if stated; what was delivered and whether they used it; the outcome as reported, not as verified; whether they are reachable through a public channel; and whether the account is positive, negative, or inconclusive evidence. Include people who turned down paid help, regretted a purchase, solved the problem with free help, or gave up.

## 2. Offers already on sale

At least 30 current offers across several providers and countries, including at least 10 of the kind I offer. Tag each as <this field's categories, for example guidance like mine, general coaching, certification, course, community, software, done-for-you>, and never mix categories in one price range. Record: provider, country, audience, promised result, format, what the client must do, price or "Not public", term, refund terms, proof shown, date seen, and whether the claims are provider-controlled. Calculate the median and range of public prices per category and country wherever there are at least five prices (list them otherwise), the share of offers with public prices, and how similar the positioning and promises are.

## 3. Spending evidence

A separate table of accounts that explicitly report spending, split into <this field's kinds of spending, for example credentials, courses, personalised guidance, software, done-for-you work>. Keep the currency, country, date, and product. Distinguish charged, paid, refunded, and disputed. An inquiry or a booked call is not a purchase, and "I joined" does not state a price.

## 4. Public requests and budgets

At least 100 recent public requests for this kind of help across at least three sources: <marketplaces, job boards, request boards, tenders>. Record: platform, date, buyer country, type of request, stated budget, fixed or hourly, number of proposals or applicants, the buyer's hiring history, whether it looks serious, whether the scope fits the budget, and whether they want guidance, done-for-you work, or a combined outcome. Calculate: the median and range of budgets by request type and country; the share of workable versus unrealistically cheap requests; competition per request; new versus established buyers; generic versus specialised requests; and signs of growth or decline. Use only requests visible without an account. If fewer requests are publicly visible than the target, report how many qualified and add the closest observable demand signal, counted separately: <for example public posts asking for recommendations or for feedback>.

## 5. Prospect observation audit

Observe at least 100 real, publicly visible prospects across the groups and countries, using <what is visible in this field, for example offer pages, sales pages, booking pages, profiles>. Record the observable problems: <this field's list>, and the signs that no help is needed. Estimate the share with a plausible need, the share likely able to pay, the share for whom fixing the problem would create measurable value, and the share who probably would not benefit enough to buy. A prospect needs both a meaningful problem and the ability to pay; a weak page alone is not an opportunity. Observe only; contact no one, and record each prospect by the link to their public page, not their contact details. If a group has nothing public to observe, say so and use the closest visible substitute: <for example public posts announcing plans>.

## 6. Access audit

Where can these people be observed, where do they actively ask for help, and where could a new provider reach them ethically: <communities, search, directories, partnerships, newsletters, events, referrals, platforms>? For each channel, record how much existing trust, proof, audience, or niche credibility it seems to require. Being visible on a platform does not make someone a reachable paying prospect.

# YOUTUBE AND PODCAST RESEARCH (TEXT ONLY)

Read these sources; never watch or listen to them. Get each transcript as text, in this order:

1. A transcript already published as text: the podcast's transcript page or show notes, the talk's transcript page, or the creator's written version of it (blog post, newsletter, article).
2. If a command-line tool that saves captions only is already installed, use it for the captions file alone, in one language, for example `yt-dlp --skip-download --write-subs --write-auto-subs --sub-langs en --sub-format vtt <video link>` (change `en` to the video's language code). Do not install any software.
3. Otherwise, do not analyse the video. List it as "not analysed: no text transcript", with its title and link, and move on.

Choose videos by their titles and descriptions first, and fetch transcripts only for the ones you will analyse. Try at most two routes per video. Read only the parts of a transcript that bear on these research questions, and cite them by timestamp.

Analyse at least 25 long-form sources, mainly from the last 24 months: videos and podcast episodes read from text transcripts, plus written interviews and founder retrospectives if transcripts run short. Report how many of each. Include several from each category:

<Eight to ten categories for this field, for example people saying it is saturated or dying; people saying it is still an opportunity; operators showing revenue, costs, and client-acquisition numbers; established providers; small providers without big audiences; buyers describing what they bought; people who quit or failed; tool and AI commentators; course and coaching sellers, labelled as interested parties.>

Search both supportive and negative phrasing, including:

- <Sixteen to twenty-five search phrases for this field, at least half of them skeptical or negative>
- <The same kinds of phrases in each other language the customers use>

For each important source, log: title, channel, upload date, URL, how the transcript was obtained, relevant timestamps, the speaker's apparent experience, main claim, evidence shown, whether figures are revenue, profit, cash collected, or contracted value, whether costs are included, the creator's financial incentive (courses, coaching, software, affiliate links), whether the claim is corroborated elsewhere, and evidentiary weight (high, medium, low).

Never claim to have analysed a video when only its title or description was available; list it as "not analysed". Treat comments as anecdotal, and use them only where they can be read as text without opening the video in a browser; where you can, compare top comments with the newest, because ranking distorts apparent consensus. Creators repeating each other is not consensus.

# COMMUNITY AND FORUM RESEARCH

Search public discussions by both buyers and sellers in the communities named in Tier 3<, plus any others these topics call for, in every relevant language>.

Look for: <this field's topics, for example difficulty finding clients, falling prices, what people paid for and whether it helped, regret and refunds, switching from free to paid help, replacing providers with AI, successful specialisation, failed outreach, burnout, leaving the field>.

Separate the speaker: people who never ran a business, beginners, established providers, course sellers, buyers, employees, and people who left the field. Prioritise recent, detailed posts with context and numbers. Correct for survivorship bias (people selling success over-report it) and failure-reporting bias (complaints are over-represented in forums).

# COMPETITIVE SATURATION ANALYSIS

Do not define saturation as "many providers exist". Measure it through: the number and apparent quality of providers; proposals or applicants per public request; how often extreme underpricing appears; how similar positioning and promises are; generic versus specialised providers; paid-ad competition; search-result and directory density; sales-cycle length; close rates, only where reliable data exists; price trends; closures, pivots, and people leaving the field; dependence on referrals; buyer switching costs and trust objections; the availability of free and AI substitutes<; plus signals specific to this field>.

Conclude, for each group and country, whether the market is: oversupplied overall · oversupplied only at the low end · undersupplied in specialised segments · healthy but hard for undifferentiated newcomers · viable mainly through an existing network · viable through outbound outreach · viable through partnerships or referrals · viable through a recurring model · unknown.

# FREE, AI, AND DO-IT-YOURSELF ALTERNATIVES

Map the current alternatives: <free official support in each country; free creators and resources; templates; communities; and the AI tools and platform features relevant to this problem, by name>.

Using official product documentation, independent tests and reviews, and a repeatable example of your own where no account is needed, assess whether they can independently handle: <ten to twenty capabilities specific to this problem, each one something documentation or a test could confirm, for example diagnosing an individual's real bottleneck from their own data, personalised feedback, accountability, …>.

Determine: what they have already commoditized; what they have made faster; whether buyers now expect lower prices or different help; whether they create more competitors; whether they let a small specialist compete with larger providers; and whether value is moving from information to diagnosis, feedback, implementation support, and accountability for results. Keep tool capability, buyer adoption, and buyer satisfaction separate.

# ECONOMICS FOR A NEW PROVIDER

Model at least 3 delivery models: <my formats from the brief, split into at least three concrete models if the brief names fewer, for example a one-off diagnosis, several weeks of guidance, and a course plus feedback>. For each, give conservative, base, and strong cases for:

- price or contract value (observed ranges, with sources)
- delivery hours per client, including preparation, review, and follow-up
- sales and prospecting hours per client won
- revisions, support, and administration
- course creation and upkeep, if any
- software, contractor, and payment costs
- customer-acquisition cost
- lead-to-conversation and conversation-to-sale rates
- sales-cycle length and payment delays
- refunds, non-payment, and disputes
- retention or churn, and client lifetime value
- how many clients fit in <my weekly hours, or "every 10 hours a week" if they are not stated, and whether selling, administration, and course work come out of those hours; if the brief doesn't say, model both>
- effective earnings per hour after all unpaid time: selling, administration, support, and collections

Use sourced values where they exist, and label everything else "modelled assumption". Do not invent industry-average close rates, margins, or prices. Keep revenue separate from take-home income. Say where the economics depend on proof, referrals, or an audience beyond what I have described. None of this is a forecast.

# SEGMENT RANKING

Rank at least 10 segments within and across the groups (by stage, niche, country, or preferred format) on: the value of solving the problem for them; urgency; evidence that they pay for this kind of help; ability to pay; competition; free and AI substitution; ease of reaching the decision-maker; trust and proof needed; fit with my ability and limits; repeat or recurring potential; and sales-cycle length.

| Segment | Problem | Value of solving it | Spending seen | Competition | Substitutes | Ease of reaching them | Fit with me | Overall | Key evidence |
|---|---|---|---|---|---|---|---|---|---|

Do not rank a segment highly just because its members visibly struggle; show why solving the problem is worth money to them. <Local factors in each country that change the ranking, for example languages, platforms, payment methods, messaging apps, buying norms.>

# SOURCE-BIAS RULES

For every major source, ask: Who produced it, and what do they sell? Was the speaker a buyer, seller, provider, employee, or commentator? Is it firsthand and dated? What country and customer stage does it describe? Is an amount an asking price, a payment, revenue, or profit? What was the sample, how large was it, and was it self-selected? Is it global, national, or platform-specific? Does it represent survivors more than people who failed? Is it current? Is the method visible? Was it copied from another source? Does it support the exact claim being made?

Do not present:

- a vendor or association survey as neutral industry truth
- a course seller's or guru's income as typical
- a platform's gross transaction value as provider income
- growth in the number of providers as proof of profitable demand
- search interest, views, likes, or followers as buyers, or keyword data without its geography, period, settings, and units
- a few forum threads as consensus
- proposals or applicants as proof that work was awarded
- revenue without delivery, acquisition, and platform costs as profit
- provider testimonials as typical results
- <misreadings specific to this field>

When sources conflict, show the conflict and explain the likely reason.

# REQUIRED OUTPUT

Write the report in <language>, in Markdown, with these sections in this order. Use tables where shown.

1. **Direct answer.** Put it first. Which group(s), if any, merit further investigation, which need more evidence, and which to set aside. Confidence from 0 to 100, with the reasons and what would move it. What looks viable; what looks crowded, commoditized, or solved by free or AI help; for whom this is attractive and for whom it is a poor choice; and the three conditions that must hold for the strongest group.
2. **Executive summary.** The problem and its triggers, spending evidence, saturation, observed prices, economics for a new provider, reachability, free, AI, and do-it-yourself alternatives, the best opportunities, the greatest dangers, and the main uncertainty.
3. **Market map.** Each offer type from Phase 1 classified as declining, commoditized, stable, growing, potentially attractive, attractive only with specialisation, or unknown, with the evidence.
4. **Findings by group.** For each group: the strongest evidence for; the strongest evidence against; triggers seen; what people tried; spending seen, by type; alternatives and what people say about them; whether I can realistically reach them; fit with my ability and limits; contradictory evidence; missing or inaccessible evidence; and the single finding that could most change the conclusion.
5. **Group comparison.**

   | Group | Evidence for | Evidence against | Spending seen | Reachable? | Fits me? | Status: Shortlist / Needs more evidence / Set aside |
   |---|---|---|---|---|---|---|

6. **Evidence scorecard.** Score each group from 1 to 10, where higher is better for me, on: problem frequency; urgency; paid demand for this kind of help; preference for my delivery format; pricing power; competitive pressure; resistance to free and AI substitutes; reachability for a new provider; ease of winning the first ten clients; repeat or recurring potential; fit with my ability; long-term durability; and overall. Explain every score with evidence. Write "insufficient evidence" instead of guessing.
7. **Consensus versus evidence.**

   | Common claim | Who tends to make it | Evidence for | Evidence against | Final assessment |
   |---|---|---|---|---|

   Test at least these claims: <six to eight claims people in this field repeat>.
8. **Quantitative findings.** For each direct market test: the sample reached against its target, dates, medians, ranges, and distributions, by country, with limitations. Include any official statistics used, with their geography and period.
9. **YouTube, podcast, and community findings.** A table of the most informative sources (link, date, timestamps, speaker role, incentive, claim, evidence quality), then the common positive themes, common negative themes, where operators agree, where they conflict, and claims that look exaggerated.
10. **Free, AI, and do-it-yourself alternatives.** What they already replace, what they cannot reliably do, how buyer expectations are changing, what help stays defensible, and what may be obsolete in three to five years.
11. **Economics and workload.** The models and cases, with every source and assumption visible and revenue kept separate from take-home income, then:

    | Model | First-client difficulty | Observed price range | Hours per client | Clients that fit my hours | Earnings per hour (conservative / base / strong) | Revenue stability | Support load | Exposure to AI | Overall |
    |---|---|---|---|---|---|---|---|---|---|

12. **Segment ranking.** The ranked table.
13. **Failure analysis.** Why a new provider in my position would fail to win or keep paying clients: <for example weak proof, a vague promise, the wrong customer stage, broad positioning, no way to reach buyers, underpricing, scope creep, clients who do not implement, support load, competing with free help>. Rank them by probability and severity for me, not by generic frequency.
14. **Implications for my next decisions.** Without making them: which group(s) to study competitors for next; who to learn from directly and what to ask; the offer formats and price ranges observed (observations only; my final offer and price come later); what not to offer; what proof buyers seem to need; and, if no group qualifies, the most promising adjacent problems that use the same ability, with the evidence for each.
15. **Validation plan (to review, not to run).** A low-cost 60- to 90-day plan that tests real willingness to pay before I commit: the narrow problem hypothesis; a sample deliverable I could show (for example a short diagnostic); where to find suitable prospects through public, ethical channels; how many conversations; message variations to compare; the minimum number of paid pilots or deposits to seek, with test prices taken from the observed ranges and labelled as tests; the questions to ask people who decline; the metrics to record; pass, warning, and fail thresholds; and the most time and money to spend before reassessing. It must measure payment, not likes, survey answers, or compliments. Do not contact anyone or collect money as part of this research.
16. **Decision matrix.** For each group, one of: Shortlist now · Shortlist only with specialisation · Investigate further first · Side project only · Set aside · Choose an adjacent problem instead. State exactly what new evidence would change each decision.
17. **Sources and research audit.**

    | # | Source (link) | Source type | Customer behaviour or provider marketing? | Published | Inspected | Geography | Sample size | What it shows | What it does not show | Group |
    |---|---|---|---|---|---|---|---|---|---|---|

    Then list video timestamps, videos not analysed for lack of a text transcript, unmet sample targets, inaccessible or paywalled sources, duplicate accounts merged, claims that could not be corroborated, and the search queries used, so the research can be repeated.

# CITATION REQUIREMENTS

- Cite every material factual claim immediately after it, with a direct link to the original source wherever possible.
- Do not cite search-result pages.
- Do not invent quotes, people, prices, budgets, sample sizes, countries, publication dates, or video contents.
- For videos, give the URL and the relevant timestamps.
- Keep direct evidence, inference, and modelled assumptions visibly separate, and label the assumptions.
- If a source is paywalled or inaccessible, say what could and could not be checked, and cite only what the accessible part establishes.
- Never cite a source for a stronger claim than it makes.
- Avoid long verbatim quotations.

# COMPLETION AND STOPPING RULES

Keep researching until all of these are true:

1. Every group has been tested against both positive and negative evidence.
2. Real buyer behaviour and spending have been examined, with spending on this kind of help kept apart from other spending.
3. Offers, prices, and competitive pressure have been measured with observable signals, not provider counts.
4. Free, AI, and do-it-yourself alternatives have been assessed from their current capabilities.
5. Every direct market test has run, with its sample reported against its target.
6. At least 25 long-form sources have been read as text, with the number of videos and podcast episodes among them reported, and no video or audio was played.
7. Each country is reported separately.
8. The economics rest on sourced values and labelled assumptions.
9. A practical validation plan exists.
10. Every major conclusion traces to cited evidence.
<11. Anything in the brief's stopping point that rules 1 to 10 don't already cover.>

Stop when these hold and the leading conclusions have converged. Do not keep searching just to pile up generic sources. If an important target cannot be met, mark the research "Partial" and list the gaps precisely in section 17. Never fill missing evidence with general knowledge.

The purpose of this research is <a sound decision about which group to investigate further>, not <an exciting story about this market>.
```
