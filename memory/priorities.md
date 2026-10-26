# Agreed priorities — week of 2026-09-08 (prior week's wrap below)

1. **5 connector touches/week cadence** — at **3 of 5** (Gonzales 8/31, Dodds 9/2, McCandless 9/1). Micah Brandenburg + Paul Ellis still owed this week.
2. **Past-client / closed-lost reactivation emails** — Simpliphy, Spectrum, Verow, etc. — using the agent demo as the "new news" hook.
3. **Package the Spark Hire demo** as a forwardable asset. John's call 9/1: the **Spark Hire case study** is the next high-leverage thing (Notion: Case Study Tracker → "AI DRAFT Spark Hire", status In progress, requested 8/27). **v2 rework drafted 9/1** as a new tracker row: https://app.notion.com/p/3ce7a190681b81ae85e5edda3e8818e8 (buyer-facing, transcript-sourced numbers, technical appendix; original AI DRAFT left intact). Open items for John (in the page's internal callout): Tom Cruger's title (never stated in transcripts); client sign-off on quotes → Status "Client review"; three v1 data-quality findings (stale churn flags, departed contacts, unused-product health scores) not in any transcript — source from Slack logs or cut; keep/cut the reframed "$2k compute" quote. This is the FIRST case study — its structure is the template for Cyberknit/GLDN later. **GLDN case study v2 drafted 9/2** (new tracker row, AI DRAFT left intact): https://app.notion.com/p/3cf7a190681b81d488f7e4b7e95a2a86 — results from Eric Tucker's March 2026 GLDN Data Strategy Review (client-authored, marked Confidential), our scope from Harvest. **Corrects v1 overclaim**: Harvest shows Agreeable = the half-time Sr. DE seat (Rachel, ~90 hrs/mo since Feb 2026), NOT the Q2 2025 platform build. **Role confirmed by John 9/2: we were ALSO the Q3 2025 contract DE/DS surge crew (untracked in Harvest) — page updated to two phases (2025 surge → 2026 embedded seat); still not claiming the Q2 2025 assessment/platform stand-up.** Open items for John (in page callout): client sign-off now needs Jed/Deb since Eric left GLDN (ask on 9/3 call); Eric quote permission + title tense; what "Project Midas"/Silverdale cutover was (Jul–Aug 2026, ~80 hrs) — possible extra section; keep/soften the continuity ("doesn't resign") angle. Pipeline is ~half the size the goal requires (need 4–5 live deals, have 2), so this asset is the multiplier.

## This week (10/13)
1. **Commerce / BigCommerce (Keith)** — **10/21 call: NOT WON; Oct 19 start dead.** Sharon Gee = exec sponsor; Anthony Leach (eng lead over data) must approve and hasn't met us; GRC/SOC 2 intake coming; funding "next year." Both next steps are Keith's with no dates. **John by Fri 10/23:** email Keith cc Sharon — recap in their words, two slots for the Anthony call, ask budget year + who signs. Hold the SOW re-date until after Anthony. Board SOW review + full call log in the Notion row.
2. **Omnificity / Eric** — moved to wk of 10/19 (John 10/16): engineer profiles + rates, target start + headcount. Confirm cost per engineer first.
3. **ThoroughCare Phase 2 (Barry)** — "fine" per John 10/16; call date + Curt 10/15 outcome still unlogged.
4. **Sean Reid / Unifi Healthcare** — re-ping SENT 10/16. Waiting on a slot.
5. **ASMBL** — re-check with Vince was ~Thu 10/9. Status?
6. **Toast** — 9/29 re-check never logged; Notion still Closed Lost.
7. Still owed: Dixie 9/22 outcome, Verow split in writing.
8. Anthropic partner application: 10-person minimum (at ~8, adding contractors); public case study done.
9. **Tom Cruger leaving Spark Hire (10/19)** — buyer + signer + the voice in the case study. Filed as a connector. Ask before his last day: quote permission, who inherits the agent, where he lands. Spark Hire case study sign-off now has a clock on it.
10. **Breezy ClickHouse case study — BREEZY SAID YES 10/22; v1 drafted 10/21.** Agreed framing (John 10/22): Justin built the AWS side (ClickHouse instance + PIS); Agreeable did the migration; we claim ClickHouse experience, not EC2 work. Draft: https://app.notion.com/p/4007a190681b81528714cd45f05d0a70 (Case Study Tracker, In progress). Story = the production comps engine (Supabase Postgres → ClickHouse on AWS, Apr–Jun 2026; PIS live 5/27), NOT the Sept DW (went Databricks 9/28; ClickHouse = app data only). Joint build: Justin DeWind (Breezy) wrote the PIS + first ClickHouse snapshot; Agreeable did the Cotality ETL, ClickHouse eval (4/8), QA, Glue→CH snapshots, OpenSearch, Postgres retirement. Before publishing: confirm the (call) quotes with James + Justin, get an after-latency number (none exists), confirm $5k/mo realized, titles, James's OK on the investor-report line. Purpose: proof of the "practice around ClickHouse" Keith sold Sharon; Anthony Leach will test it. Other ClickHouse proof: Wheelhouse LeadSherpa realtime scoring API, RudderStack crew.
11. **Carolina Handling via Ryan Tiller — NEW OP 10/26.** Ryan = VP Distribution & Fleet Services since Nov 2025 (year-one window, Q4 budget). Filed in Discovery tracker (Warm, Medium-High) + connector row updated. Angles: rental-fleet utilization / service dispatch / telematics ('ask the fleet anything'); his own playbook is Salesforce Service Cloud + Amazon Connect + Power BI. **10/26 pm: Ryan texted FIRST — Snowflake (rep Evans Blasche) pressing Carolina Handling, talking to their sellers; Ryan is rebuilding Order-to-Delivery on Power Apps + Dynamics CS, D365 ERP later, wants agentic AI, admits data isn't structured. John disclosed Snowflake partner bias and asked 'what for?' (good). Board: answer pros/cons honestly incl. the Microsoft/Fabric fit, then ask for 30 min THIS WEEK before his next Snowflake call. Either platform → the structuring work is ours; if Snowflake wins, we're the SI.** **Research 10/26 (3 agents): OEM (TMHNA) is rolling out a common DMS on Dynamics 365 Business Central; CH's IT (3 people, no CIO) already builds Fabric pipelines; comparable Raymond/Toyota dealer (Southern States) is on Fabric. Board verdict: Fabric is the default; Snowflake only if telematics/non-MS data at scale, data sharing with Snowflake-based customers/OEM, Fabric throttling, or a dbt-native team. OneLake↔Snowflake Iceberg interop (GA 2026) means Snowflake can be added later without re-landing data → kills rep urgency (SNOW quarter ends 10/31). Agreeable's lane = O2D data contract, dbt model, semantic layer, first agent (platform-agnostic). Full brief + CALL PREP (Mon 10/26 4:00 PM ET, 30 min) in the Discovery row: https://app.notion.com/p/4057a190681b81c2871cc3cce6e2bd86. After the call: log Ryan's words, DMS phase, telematics access, who signs, next step + date.** **Tech team / ICP (10/26, in the row): ~10-person IT, infra-led (Chad Young Dir IT), Power Platform devs, 0 data engineers; Manager of Fleet Analytics (Diebold) retired Oct 2024, no replacement visible; Jeanette Power = ex-Dynamics PM = DMS-fluent. O2D has been a BPI initiative since 2018 (Ashley Watkins). Revenue $300M+ (CBJ #23). ICP: B1 at the top of the band, 0–1 data people qualifier passes; risk = IT territory + DMS bandwidth.** **John 10/26: CoLinx (a Raymond iWAREHOUSE customer) → we pulled iWAREHOUSE hourly lift data into Snowflake (raw.iwarehouse.hourly_lift_data, deadman hours, Elementary tests) and built productivity tracking; integration was painful. = proof for Ryan on the telematics gating question. Don't name CoLinx unless referenceable.**

Connector holds set 10/16 (John): Bill Evans → follow up later (early Nov); David McCandless + Ken Apple → not now (re-check Dec). Unaddressed from the 10/16 list: Dodds thank-you, Vince/ASMBL re-check, Dixie one-pager, Toast decision.

## Week of 9/21 (archived)
1. ~~Mon 9/21 Sean / Snowflake meeting~~ — CANCELED. Follow up wk of 9/28 (reminder set Mon 9/28 9am ET). **DONE 9/28: Sean Reid starts at client ~10/5; re-ping ~10/12 to book 30 min.**
2. **Mon 9/21 3–4pm ET — Commerce + Agreeable Data** (Keith's invite, Marissa on it). Likely the roadmap walkthrough / boss intro. Up-front contract at top; leave with retainer shape + who decides.
3. **Tue 9/22 8:45am — Dixie Plastics Visit #2** (Willz accepted). Revenue-first one-pager (standard parts + hose online → develop accounts) must be on paper BEFORE this. Ask who else should be in the room.
4. **Tue 9/22 11am — Cyberknit HOLD** (Jacob declined). Verow split in writing before first invoice.
5. **ASMBL:** delayed ~2 wks (John 9/25). Re-check ~10/9. Re-confirm staffing for the new window.
6. Rolled: Micah + Paul Ellis touches; McCandless debrief; GLDN Deb cadence owner + DG backup confirmed?

## Last week (9/14)
1. **Tue 9/15 8:15am — Dixie Rubber & Plastics site visit** (Drew Boswell, via Dodds). Qualify hard; leave with owners identified + next step + date. Thank Dodds after.
2. Commerce: MNDA watch — no MNDA by Fri 9/18 → ping Mon 9/21.
3. GLDN: Eric gone as of 9/11. Demo/show-and-tell week of 9/14 (Jed). Cadence with Deb. Backup named?
4. Touches: Micah Brandenburg + Paul Ellis (rolled 3 weeks). McCandless debrief.
5. **Cyberknit SIGNED 9/15** — settle Verow split in writing before first invoice; attach signed SOW to Notion; hand kickoff to PM agent.
6. **ASMBL 'BI Project'** (Vince Liu / Soheil Parsa, inbound 9/9) — confirm whether the Soheil call happened; if not, reply w/ two slots today.

## Last week (9/8)
1. **GLDN** (retained client — NO selling): Slack note in Data Dev by Wed 9/9 proposing an operating cadence (biweekly w/ Deb, monthly w/ Jed) + two demo slots week of 9/14 as show-and-tell. Rachel to lead the Snowflake persistence review inside the retainer. Eric asks by Wed 9/9 (quote permission, intro, landing spot).
2. **Touches**: Micah Brandenburg + Paul Ellis first (rolled from last week), then 3 more. Tiller lunch text (was Mon 9/7 — done?).
3. **Cyberknit**: SOW sent 9/1 — follow up today (9/8) if quiet; Verow reply on split?
4. **Gonzales** follow-up ~9/8.
5. McCandless debrief still owed.

## Week wrap (John, Wed 9/2 evening) — John OFF Thu 9/3
- Touches: **3 of 5** (Gonzales, McCandless, Dodds). Micah Brandenburg + Paul Ellis NOT touched — roll to week of 9/8 as first two touches.
- **GLDN reintro Thu 9/3 4pm (Jed + Deb)** — John is off that day. CONFIRM: still taking the call, or rescheduled? If rescheduled, it's the highest-priority reschedule of the month (agent pitch + case study sign-off + Rachel continuity).
- McCandless debrief still owed (partner lane? intro? next step?).
- Fri 9/5 9am accountability task fires regardless; expect it to flag Micah/Paul as untouched and Cyberknit SOW stage unconfirmed.
- Shipped this week: Spark Hire case study v2, GLDN case study v2 (both awaiting client sign-off), Cyberknit SOW ($90k, sent 9/1), Verow split email.

## Key dates
- **Mon 9/21 9am ET — board reminder scheduled** (send_later): Dixie starting point + sit-down owed this week; Verow split; Commerce boss meeting status.
- **Mon 9/21 9–10am ET — Sean / Snowflake meeting** (new deal, no details yet). Same hour as the reminder — read the reminder after the call.
- Mon 9/1 — Dodds nudge deadline if no podcast date.
- Thu 9/3 4pm — GLDN reintro call (Jed Paulson + Deb T).
- Fri 9/5 9am — `friday-pipeline-accountability` fires.
- Mon 9/7 — John texts Tiller for lunch.

## Upcoming
- **Oct 7–8 — Acquisition.com workshop, in person, Las Vegas** (booked 8/31): nail down the offer + sales channels. Travel days around it — protect the GLDN/Cyberknit follow-through that week. Guardrail agreed: this does NOT pause September selling — the current offer ($5–10k agent pilot → Snowflake retainer) is the offer until then. Prep with real data: Sept touch/intro/close numbers, win-loss notes, pricing history, where deals stall.

## Open questions for John
- Cyberknit 8/31 call outcome + dollar value?
- Toast re-check date?
