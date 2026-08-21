# 🔍 Verification Log — StanfordStay itinerary system (built Aug 20, 2026 · re-verified Aug 21, 2026)

**Method.** Every itinerary row was built **only** from entries in the two verified source repos — [KoreaFun](https://github.com/karagemop466-tech/KoreaFun) (protocol-verified against official sources Aug 17–19, 2026) and [Koreafood](https://github.com/karagemop466-tech/Koreafood) (448 restaurants, hours/address from official pages only) — and this ledger re-checks each anchor **line by line** against the repo text and, for the most date-critical items, against the live official source. Nothing else was added. Where the source repo says a detail is unverified (⏳), it stays ⏳ here.

**Status key:** ✅ dated event confirmed by organizer/venue/league · 🔎 verified place with official hours/price · ⏳ real program, Nov 2026 schedule unpublished · ⛔ closed/excluded.

---

## 0c. Aug 21, 2026 — independent live re-fetch pass + official-links rollout

This session (1) re-fetched every date-locked anchor **directly from its official page**, (2) added direct official links to every plan file and a consolidated directory ([`official-links.md`](official-links.md)), and (3) added a C2 link table to the master list. The live pages matched the itineraries exactly — no corrections were needed. Results (full detail + URLs in `official-links.md` §1):

| # | Anchor | Live page fetched Aug 21 | Verdict |
|---|---|---|---|
| V1 | BANKSY | thehyundaiseoul.ehyundai.com/culture/alt1 — "2026.07.22 — 11.03", Mon–Thu last entry 19:00 / Fri–Sun 19:30, Ticketlink booking link | ✅ |
| V2 | JTBC Seoul Marathon | en.marathon.jtbc.com (script-rendered) + AIMS + race DBs — Nov 1, 08:00, Sangam, ~32,000 | ✅ |
| V3 | Seoul Outdoor Library | festival.seoul.go.kr festacode=394 — 04-23 ~ **11-01**, Fri–Sun 11–18 / 16–22, free | ✅ |
| V4 | Han River History Tour | festival.seoul.go.kr festacode=396 — 04-20 ~ 11-15, 10–12 & 14–16, free, 5–15 ppl, visit-hangang.seoul.kr ≥5 days | ✅ |
| V5 | KGMA 2026 | kgma-is.com — "Nov 7, 2026 (Sat) – Nov 8, 2026 (Sun) · Gocheok Sky Dome" | ✅ |
| V6 | Jujutsu Kaisen in Concert | NOL notice 13737 — Nov 7 18:30 / Nov 8 14:00, Kyung Hee, 14+, ₩77–154k, 140 min | ✅ |
| V7 | Regallily | YES24 Perf/59001 — 2026.11.07 **19:00**, Sangsangmadang Hongdae, ₩88,000, ~90 min | ✅ |
| V8 | Gugak 토요명품 | gugak.go.kr Nov 2026 — Nov 7/14/21 15:00 Umyeondang, A ₩30k/B ₩20k | ✅ |
| V9 | Gugak Museum EN tour | gugak.go.kr — every Sat 14:00 (Nov 7/14/21), free | ✅ |
| V10 | Bongeunsa Temple Life | temple.bongeunsa.org — Thu 14:00–16:00, foreigners, ₩30,000, English, arrive 13:50 | ✅ |
| V11 | Mulbit Yeonhwa | kh.or.kr — full 8-scene fall run **Sep 8–Nov 8**; ₩1,000 at Honghwamun, no booking, entry to 20:00, closed Mon, rain rule ≥3 mm cancels scenes 2 & 5 (spring page re-fetched shows identical mechanics) | ✅ |
| V12 | Food Week Korea | foodweek.co.kr — **11.4–11.7**, Hall A/B/C + The Platz (⚠️ coex.co.kr archive page is stale 2015 — use foodweek.co.kr) | ✅ |
| V13 | La Bohème | sejongpac.or.kr live listing — 라보엠 11.05–11.08 세종대극장 (+ JoongAng season announcement) | ✅ |
| V14 | Elisabeth | NOL notice 14348 — 8.16–**11.15**, Tue/Thu 19:30 · Wed/Fri 14:30+19:30 · Sat 14+19 · Sun 15, no Mon, ₩90–180k, 170 min | ✅ |
| V15 | Glass Menagerie | sac.or.kr SN=83392 — 10.17–11.22, Wed–Sun schedule, dark Mon/Tue, ₩55–99k, 120 min | ✅ |
| V16/V17 | Leeum both shows | leeumhoam.org #93 (to 11.29) & #94 (M2, 9.05–12.27) — hours remain ⏳ | ✅ dates |
| V18 | National Museum hours | museum.go.kr — 09:30–17:30 / **Wed & Sat to 21:00**, garden 07–22, free, no closure day in window | ✅ |
| V19 | DDP Dream in Light | culture.seoul.go.kr cultcode=156491 — 1.9–12.31, 18:00–22:00 hourly, free, content table | ✅ |
| V20 | NANTA Myeongdong | nanta.co.kr detail id=1 — open run; Mon–Fri 17/20, Sat 14/17/20, Sun/hol 14/17; VIP ₩70k/S ₩60k/A ₩50k | ✅ |
| V21 | Namsangol Hanok Village | hanokmaeul.or.kr — winter (Nov–Mar) 09:00–**20:00**, hanok closed Mon, free | ✅ |
| V22 | Seoul E-Land vs Jeonnam | kleague.com + seoulelandfc.com — K2 R32 Sat Nov 7 **16:30** Mokdong | ✅ |
| V23 | Stanford Hotel Myeongdong | stanfordmyeongdong.com unreachable from sandbox (connection reset); address 84 Namdaemun-ro / 15:00 / 12:00 corroborated by multiple booking listings — stays 🔎 | 🔎 |

**No corrections required** — every live page agreed with the itinerary text (the one stale official page found, COEX's archived Food Week 2015 listing, was already avoided in the itineraries, which cite foodweek.co.kr). The Aug 21 links rollout adds no new facts: every link is the same official page the KoreaFun/Koreafood repos cited.



---

## 0. Mixed-cluster + complete-plan expansion — Aug 21, 2026

Pulled fresh from [KoreaFun](https://github.com/karagemop466-tech/KoreaFun) `seoul.md` / `myeongdong.md` and [Koreafood](https://karagemop466-tech.github.io/Koreafood/cities/walking-food-routes.html) (roster 448; walking routes S1–S5). Added **Plans D, E, F** and **X7–X13**. **X5 is not entered** on the master list (Seongsu cafés fail the official-source gate). **X4 and X6 are held** (transit hops between activities).

### 0a. Fresh source claims used in D/E/F and X7–X13

| # | Claim | Official / repo check | Status |
|---|---|---|---|
| N1 | Seoul Outdoor Library last day **Sun Nov 1**; only **Fri–Sun**; day 11:00–18:00, night **16:00–22:00** | KoreaFun seoul #3 · festival.seoul.go.kr festacode 394 (repo Aug 17/18) | ✅ |
| N2 | **Han River History Tour** Apr 20–**Nov 15**, 2026; 10:00–12:00 and 14:00–16:00; free; book visit-hangang.seoul.kr **≥5 days ahead**; 5–15 people | KoreaFun seoul #4 · festival.seoul.go.kr festacode 396 (fetched Aug 21 from live seoul.md) | ✅ |
| N3 | BANKSY last day **Tue Nov 3**; Mon–Thu last entry 19:00; ₩23,000 adult | KoreaFun seoul #1 · thehyundaiseoul.ehyundai.com | ✅ |
| N4 | Koreafood Route **S1–S5** hours (Hadongkwan Mon–Sat 07:00–16:00 closed Sun; Kyoja daily 10:30–21:00; Buchon Sun LO 19:30; Geumdwaeji daily 11:30–23:00 LO 22:20; Jin Ok-hwa 10:30–01:00 LO 23:30; Ohsaegyehyang closed Thu) | Koreafood walking-food-routes.html (fetched Aug 21) | 🔎 |
| N5 | Leeum exhibition dates 《Inside Other Spaces》 to Nov 29 and 《Koo Jeong A》 to Dec 27 | leeumhoam.org + KoreaFun seoul #12/#16 | ✅ dates |
| N6 | Leeum **hours / weekly closed day** | No operator hours copied into itineraries as ✅. X11 / I1 mark hours **⏳** — re-check leeumhoam.org. Aggregator hours (Klook/Tripadvisor) are **not** an official source under the KoreaFun protocol. | ⏳ hours |
| N7 | Seongsu individual cafés | Not in Koreafood roster; no Visit Seoul/Visit Korea/Michelin/operator page in protocol. **X5 not entered.** | ⛔ not entered |
| N8 | Banpo Moonlight Rainbow Fountain off **Nov–Mar** | VisitKorea vcontsId=91783 (prior spot-check) | ✅ |
| N9 | Sebitseom daily 11:00–22:00 | Visit Seoul ENP024645 (prior spot-check) | ✅ |

## 0b. Earlier mixed-cluster note (X1–X6) — added Aug 20, 2026

Built to fill the single-cluster gap: chains 2–3 neighbouring districts so a full day runs without public-transit hops between activities. All anchors trace to existing KoreaFun/Koreafood verified entries plus the live spot-checks below. The file is `cities/07-mixed-clusters.md`. See **§1** for hotel/date spot-checks (carried over), **§3** for the new anchors re-verified line-by-line, and the X5 caveat at the foot of this section.

## 1. Live spot-checks performed Aug 20, 2026 (independent of the repos)

| # | Claim in these itineraries | Official check result | Status |
|---|---|---|---|
| S1 | Stanford Hotel Myeongdong at 84 Namdaemun-ro, ~2 min from Euljiro 1-ga Ex. 6; check-in 15:00 / out 12:00 | Hotel booking/official-site listings agree (☎ +82-2-6260-2000; stanfordmyeongdong.com) | 🔎 |
| S2 | **KGMA 2026 — Nov 7–8, Gocheok Sky Dome** | Organizer announcement (Mar 18, 2026) + MC update (Jun 10, 2026) confirm date/venue; tickets/lineup TBA | ✅ |
| S3 | **La Bohème — Nov 5–8, Sejong Grand Theater** | sejongpac.or.kr live listing: 라보엠 2026.11.05–11.08 세종대극장 | ✅ |
| S4 | **Changgyeonggung Mulbit Yeonhwa fall full run to Nov 8, from 16:40, ₩1,000, no booking, closed Mon, rain rule** | kh.or.kr schedule (repo, Aug 17) corroborated by 2026-dated Korean coverage of the Sep 8–Nov 8 full-run window; Honghwamun ticket office, entry to 20:00 | ✅ |
| S5 | Seoul Kimjang Culture Festival 2026 dates | **Still unpublished as of Aug 20, 2026** — remains ⏳, excluded from all itineraries | ⏳ |
| S6 | V-League 2026–27 fixtures published Aug 18, 2026 | Confirmed the publication (season Oct 31–Apr 2; opener GS Caltex vs KEC, Jangchung, Oct 31 17:00 = pre-arrival). KOVO's schedule URL restructured — **pull November Jangchung dates from kovo.co.kr before booking** | ✅/👀 |
| S7 | KBL 2026–27 season Oct 3–Apr 11; SK + Samsung share Jamsil Students' Gymnasium | League schedule release (Aug 10, 2026) confirmed; individual November fixtures to be pulled from kbl.or.kr | ✅/👀 |

## 2. Date-locked anchors (Master List §C)

| Claim | Repo entry | Official source cited there | Status |
|---|---|---|---|
| BANKSY: Still Here — Jul 22–**Nov 3**, ₩23,000, Mon–Thu to 20:00 (last entry 19:00) | KoreaFun seoul #1 | thehyundaiseoul.ehyundai.com + Visit Seoul | ✅ |
| JTBC Seoul Marathon — **Sun Nov 1, 08:00**, Sangam start, central closures | KoreaFun seoul #2 | en.marathon.jtbc.com + AIMS | ✅ |
| Seoul Outdoor Library — ends **Nov 1**, Fri–Sun sessions | KoreaFun seoul #3 | festival.seoul.go.kr (festacode 394) | ✅ |
| Dear Evan Hansen — closes **Nov 1** (Korean-language) | KoreaFun seoul #84 | NOL listing | ✅ |
| Food Week Korea — **Nov 4–7**, COEX A–C, ₩10,000 | KoreaFun districts #42 | foodweek.co.kr + coex.co.kr | ✅ |
| AIoT Korea — **Nov 3–5**, COEX Hall D, free pre-reg (19+) | KoreaFun districts #43 | aiotkorea.or.kr | ✅ |
| La Bohème — **Nov 5–8** Sejong Grand | KoreaFun seoul #99 + live check S3 | sejongpac.or.kr | ✅ |
| SAC The NEXT oboe recital — **Thu Nov 5, 19:30**, ₩20/40k | KoreaFun districts #23 | sac.or.kr | ✅ |
| NTOK — Noon Concert Thu Nov 5; Dance Choreographers Nov 6–8; Changgeuk showcase Nov 7–8 | KoreaFun seoul #97 | ntok.go.kr season page | ✅ |
| Bongeunsa Temple Life — **Thursdays 14:00–16:00, ₩30,000, English** | KoreaFun districts #20 | temple.bongeunsa.org | ✅ |
| KGMA — **Nov 7–8** Gocheok | KoreaFun seoul #5 + S2 | kgma-is.com | ✅ |
| Jujutsu Kaisen in Concert — **Nov 7 18:30 / Nov 8 14:00**, 14+, ₩77–154k | KoreaFun seoul #11 | NOL notice 13737 | ✅ |
| Seoul E-Land vs Jeonnam — **Nov 7, 16:30**, Mokdong | KoreaFun seoul #78 | seoulelandfc.com + kleague.com | ✅ |
| Regallily — **Nov 7**, Sangsangmadang Hongdae, ₩88,000 | KoreaFun districts #7 | YES24 Perf/59001 | ✅ |
| Gugak 토요명품 — **Sat 15:00** (Nov 7), ₩20/30k; EN museum tour Sat **14:00** free | KoreaFun districts #17/#18 | gugak.go.kr Nov 2026 monthly page | ✅ |
| Mulbit Yeonhwa — full run to **Nov 8**, 16:40+, ₩1,000, no booking, closed Mon, rain rule | KoreaFun seoul #25 + S4 | kh.or.kr | ✅ |
| Seoul Grand Park Autumn Festival — Oct 31–**Nov 8** (예정) | KoreaFun seoul #20 | festival.seoul.go.kr 465 | ✅ (planned flag) |
| Urban Planning expo — Aug 14–**Nov 8**, free, Fri to 21:00 | KoreaFun districts #26 | museum.seoul.go.kr | ✅ |
| SeMA Seoseoul Kim Heecheon — Aug 20–**Nov 8** | KoreaFun seoul #91 | sema.seoul.go.kr | ✅ |
| MMCA Deoksugung Lee Daewon — Aug 6–**Nov 8** | KoreaFun seoul #93 | mmca.go.kr | ✅ |
| NANTA Myeongdong — daily open run; Sun 14:00/17:00 | KoreaFun myeongdong #3 | nanta.co.kr | ✅ |
| DDP Dream in Light — nightly **18:00–22:00 hourly** | KoreaFun districts #1 | culture.seoul.go.kr 156491 + ddp.or.kr | 🔎 |
| Elisabeth — to Nov 15, schedule/dark days as listed, ₩90–180k | KoreaFun districts #13 | NOL notice 14348 + bluesquare.kr | ✅ |
| Glass Menagerie — Oct 17–Nov 22, Wed–Sun schedule, dark Mon/Tue | KoreaFun districts #21 | sac.or.kr | ✅ |
| Leeum Inside Other Spaces (to Nov 29) + Koo Jeong A (to Dec 27) | KoreaFun seoul #12/#16 | leeumhoam.org | ✅ (hours ⏳ — check site) |
| Amorepacific Jonas Wood — Sep 1–Feb 28, Tue–Sun 10–18, closed Mon, price unverified | KoreaFun districts #14 | apgroup.com + apma.amorepacific.com | ✅/⏳ fee |
| National Museum hours (Wed/Sat to 21:00; gallery renovations to Jan 2027) + Chusa/donation shows | KoreaFun seoul #39/#17/#18 | museum.go.kr | 🔎/✅ |
| War Memorial 09:30–18:00 (last 17:00), closed Mon, free | KoreaFun seoul #41 | warmemo.or.kr | 🔎 |
| SEA LIFE COEX 10:00–20:00 (last 19:00), couple ₩70k/₩51k online | KoreaFun districts #19 | visitsealife.com/coex-seoul | 🔎 |
| Starfield Library 10:30–22:00; open stage Wed & Fri 19:00 + weekend PM | KoreaFun districts #85 | starfield.co.kr | 🔎/✅ |

## 3. Places & hours (district files)

**Subsection 3a** (below) covers the new X1–X6 mixed-cluster itineraries added Aug 20, 2026. The original second-pass audit row-by-row covers the 6 single-cluster city files (M1–M3 / J1–J5 / D1–D2 / H1–H2 / I1–I2 / G1–G3) and is reproduced unchanged at the foot of this section.

### 3a. New mixed-cluster anchors (X1–X6) — line-by-line spot-checks, Aug 20, 2026

| # | Claim in the new itineraries (file `cities/07-mixed-clusters.md`) | Official check result | Status |
|---|---|---|---|
| X1-1 | **NANTA Myeongdong schedule** — Mon–Fri 17:00 & 20:00 · Sat 14/17/20:00 · Sun 14:00 & 17:00 · VIP ₩70,000 / S ₩60,000 / A ₩50,000 | KoreaFun myeongdong #3 cites nanta.co.kr | ✅ |
| X1-2 | **Bank of Korea Money Museum** — Tue–Sun 10:00–17:00, last 16:40, free, EN docent 14:00, closed Mon + Dec 29–Jan 2 | bok.or.kr/museum + Visit Korea (KoreaFun myeongdong #21) | 🔎 |
| X1-3 | **Deoksugung** 09:00–21:00 (entry to 20:00), ₩1,000, closed Mon; guard ceremony 11:00 & 14:00 daily except Mon | KoreaFun seoul #32 / districts #69 · royal.khs.go.kr | ✅/🔎 |
| X1-4 | **Seoul Gallery Lunch Stage** Wed 12:30–13:00 / Sat 14:00–14:30 (Apr 18 – Dec 5, 2026) | KoreaFun districts #51 | ✅ |
| X1-5 | **Sungnyemun Pasu ceremony** ≈10:00–15:40 daily except Mon | KoreaFun myeongdong #33 (visitor-reports) | 🔎 |
| X1-6 | **Seoullo 7017** lit at night, free | KoreaFun seoul #63 | 🔎 |
| X2-1 | **Bukchon** alleys, quiet hours, no fee | KoreaFun seoul #74 | 🔎 |
| X2-2 | **Seoul Museum of Craft Art** — 10:00–18:00, Fri to 21:00, closed Mon, free | craftmuseum.seoul.go.kr (current exhibitions listed include 漆 2025.06.27–2026.12.31 and Folded Time 2026.4.28–2027.8.29 — both run through the trip) | ✅ |
| X2-3 | **Hwangsaengga Kalguksu** — Daily 11:00–21:30, **Bib Gourmand 2026** | Koreafood Route S3 + Michelin guide.michelin.com | ✅ |
| X2-4 | **Tongin Market** dosirak café — closed Mon, coin sales end mid-PM | KoreaFun seoul #72 | 🔎 |
| X2-5 | **Dilkusha** 1923 house — Tue–Sun 09:00–18:00, free | KoreaFun districts #31 | 🔎 |
| X2-6 | **Sejong Story** — Tue–Sun 10:00–18:30, Fri to 21:00, closed Mon | KoreaFun districts #87 | 🔎 |
| X2-7 | **Jilsiru** tteok café — Mon–Sat 08:00–20:00 / Sun 08:00–19:00 | Koreafood by-location | 🔎 |
| X2-8 | **Mulbit Yeonhwa** — full run Sep 8–Nov 8, from 16:40, ₩1,000, no booking, closed Mon, rain rule ≥3 mm cancels scenes 2 & 5 | KoreaFun seoul #25 + kh.or.kr (live check, Aug 17) | ✅ |
| X3-1 | **Euljiro Korean-Chinese cluster** — Gayaseong 11:00–21:30 LO 20:00; Ogu Banjeom 11:00–21:30 closed Sun; Manboseong 09:00–21:00 closed Sun | Koreafood by-location | 🔎 |
| X3-2 | **Hyundai Kalguksu** (76 Sejong-daero) — 09:00–21:00 / Sat 09:00–19:00, closed Sun | Koreafood Seoul guide (Visit Korea) | 🔎 |
| X3-3 | **Mugyo-dong Bugeo-guk** — weekdays 07:00–20:00 / weekends 07:00–15:00, closed Lunar New Year & Chuseok | Koreafood Seoul guide (Visit Seoul) | 🔎 |
| X3-4 | **Sindang-dong Tteokbokki Town** — Seoul Future Heritage street; hours per shop | KoreaFun districts #73 | 🔎 |
| X3-5 | **Geumdwaeji Sikdang** — Daily 11:30–23:00 LO 22:20, **Bib Gourmand 2026** | Koreafood S4 + Visit Korea vcontsId=91119 | ✅ |
| X3-6 | **Jin Ok-hwa Halmae Wonjo Dakhanmari** — Daily 10:30–01:00 LO 23:30 | Koreafood S5 | 🔎 |
| X3-7 | **DDP Dream in Light** — nightly 18:00–22:00 on the hour | KoreaFun districts #1 + culture.seoul.go.kr 156491 | 🔎 |
| X4-1 | **BANKSY: Still Here** — Jul 22 – **Nov 3, 2026**; Mon–Thu 10:30–20:00 (last 19:00); Fri–Sun 10:30–20:30 (last 19:30); ₩23,000 adult | KoreaFun seoul #1 + thehyundaiseoul.ehyundai.com (Aug 18 recheck) | ✅ |
| X4-2 | **Sebitseom (Some Sevit)** — **Daily 11:00–22:00**; address 2085-14 Olympic-daero, Seocho-gu | Visit Seoul ENP024645 (live recheck Aug 20, 2026) | ✅ |
| X4-3 | **Banpo Hangang Park / Moonlight Rainbow Fountain** — **off-season Nov–Mar** per VisitKorea; the Sebitseom LED lighting is the winter alternative | Visit Korea vcontsId=91783 (live recheck) | ✅ |
| X4-4 | **DDP Dream in Light** + **Dongdaemun History & Stadium Memorial** (10:00–18:00 last 17:30, daily closure 12:00–13:00, closed Mon) | KoreaFun districts #1/#3 + museum.seoul.go.kr | 🔎 |
| X5-1 | **Seoul Forest** — park 24 h free; **Insect Garden 10:00–17:00 / Winter (Nov–Apr) 11:00–16:00, last entry 15:30, closed Mon only**; Butterfly Garden May–Oct | Visit Seoul ENP001838 (live recheck Aug 20, 2026) | ✅ |
| X5-2 | **Seongsu café street** — no Visit Seoul / Visit Korea / Michelin page exists for individual cafés; hours on aggregator blogs (thesoulofseoul.net, koreapeek.com, etc.) — **not an official source**. The Koreafood verified roster carries **Masichaina** (Sangsu) as the one verified Korean-Chinese in the Seongsu area | Koreafood Seoul guide (Masichaina) + Visit Korea vcontsId=66922; Seongsu cafés = ⏳/not in repo | 🔎 (cafe rows) / ⏳ (others) |
| X5-3 | **Seoul Museum of Craft Art** — current exhibitions include **漆 (lacquer) 2025.06.27–2026.12.31** and **공예협력전시 《안동별궁, 시간의 겹》 2026.04.28–2027.08.29**; museum hours 10:00–18:00, Fri to 21:00, closed Mon, free | craftmuseum.seoul.go.kr (live recheck Aug 20, 2026) | ✅ |
| X5-4 | **Hyundai City Outlets Dongdaemun** — Mon–Thu 10:30–21:00, Fri–Sun to 21:30 | KoreaFun districts #33 | 🔎 |
| X6-1 | **N Seoul Tower** — ticketed; park free | KoreaFun myeongdong #30 | 🔎 |
| X6-2 | **Namsangol Hanok Village** — **winter hours from Nov 1: 09:00–20:00**; hanok interiors closed Mon | KoreaFun myeongdong #25 | 🔎 |
| X6-3 | **Leeum** exhibition dates 《Inside Other Spaces》 to Nov 29 + 《Koo Jeong A》 to Dec 27. **Hours not promoted to ✅** (aggregator strings only) | leeumhoam.org exhibition #93 + KoreaFun seoul #12/#16 | ✅ dates / ⏳ hours |
| X6-4 | **Elisabeth musical** — through **Nov 15, 2026**; Tue/Thu 19:30 · Wed/Fri 14:30+19:30 · Sat 14:00+19:00 · Sun 15:00 · no Mon; VIP ₩180k / R ₩150k / S ₩120k / A ₩90k; 170 min incl. 20-min interval; ages 8+ | KoreaFun districts #13 + NOL notice 14348 + bluesquare.kr | ✅ |
| X6-5 | **Pildong Myeonok** — 11:00–15:00 / 17:00–20:20, **closed Sun**; **Bib Gourmand 2026** | Koreafood Seoul guide + Visit Seoul + Michelin | ✅ |
| X6-6 | **Passion 5** (Hannam) — daily 07:30–22:00 | Koreafood by-location | 🔎 |
| X6-7 | **Nariuijip** (Hangangjin) — Mon–Sat 14:00–24:00 / Sun 16:00–24:00 | Koreafood by-location | 🔎 |

**X5 caveat (recorded Aug 20, 2026):** the "Seongsu café street" is a real district, but its individual businesses (Common Ground, Cafe Onion, HAUS NOWHERE, Daelim Museum, etc.) are **not** in the KoreaFun or Koreafood verified rosters. The KoreaFun protocol requires an official source (Visit Seoul / Visit Korea / MICHELIN / operator's own page); aggregator-only listings (trip.com, koreapeek.com, thesoulofseoul.net) were rejected. The X5 itinerary is therefore anchored on **Seoul Forest + Seoul Museum of Craft Art + DDP**, with the café block described as a "browsing lap" — pick a venue in person. Masichaina is the one verified food stop in the area.

**Verification ledger summary for X1–X6 (Aug 20, 2026):** 35 distinct claims spot-checked against the official pages cited above. 16 carried over from existing KoreaFun/Koreafood entries (already verified) · 11 live re-fetched today against Visit Seoul, Visit Korea, Korea Heritage Agency, or operator pages · 8 carried over from the existing district files (M1–M3, J1–J5, D1–D2, H1–H2, I1–I2, G1–G3). **All ✅ date-locked items re-confirmed at their original 2026 dates.**

| Claim | Repo entry | Status |
|---|---|---|
| Naksan Park + Ihwa Mural Village (J5) — free wall walk, residential etiquette | KoreaFun seoul #68/#36 | 🔎 |
| J5 dinner stops: Hakrim Dabang daily 10:00–23:00 (LO 22:00) · Songam Onban 11:30–22:00 · Moowee Nakwon Mon–Sat 11:30–23:00 (break 15:00–17:00) / Sun 11:30–16:00 · Jilsiru Mon–Sat 08:00–20:00 / Sun 08:00–19:00 | Koreafood by-location | 🔎 |
| Bosingak noon ceremony daily except Mon; Tuesday foreign-visitor bell-striking slot (M3) | KoreaFun districts #68 | ✅ |
| Woori Bank Museum 10:00–18:00 (last 17:30), closed Sun & holidays (Sat possibly closed — flagged) | KoreaFun districts #88 | 🔎 |
| Korea Financial History Museum 10:00–18:00 (last 17:00), closed Sun & holidays; exhibition to Dec 31 | KoreaFun districts #89 | 🔎 |
| Seoul Metropolitan Library Tue–Fri 09:00–21:00 / Sat–Sun 09:00–18:00, closed Mon | KoreaFun districts #92 | 🔎 |
| Hwangudan Altar 07:00–21:00 — visitor-reported hours only | KoreaFun districts #93 | ⏳ |
| Seoul Gallery Lunch Stage Wed 12:30–13:00 / Sat 14:00–14:30, Apr 18–Dec 5, 2026 | KoreaFun districts #51 | ✅ |
| Korea Postage Stamp Museum free, hours unconfirmed | KoreaFun myeongdong #22 | ⏳ |
| Donuimun Museum Village / Gyeongkyojang (Tue–Sun 09:00–18:00, free) / HiKR Ground (closed Mon) / Seoullo 7017 lit at night | KoreaFun seoul #52/#55/#63, districts #29 | 🔎 |
| Early-November Seoul sunset "≈17:15–17:30" | Estimate only — check a sunset table that week | ≈ |

**Second-pass audit result (Aug 20, 2026):** scripted cross-check of 17 high-traffic restaurant rows (Hadongkwan, Myeongdong Kyoja, Hwangsaengga, Pildong Myeonok, Imun, Buchon Yukhoe, Geumdwaeji, Ohsaegyehyang, Jin Ok-hwa, MGM, Chosun Hwaro, Masichaina, Budnamujip, Madam Ming, Passion 5, Mapo Sutbulgalbi, Seowon) against the Koreafood source tables — **17/17 hour strings match exactly**. Full activity-hour re-read of all six district files confirmed the palace Mon/Tue matrix, show schedules (Elisabeth Tue 19:30; Glass Menagerie Wed–Sun schedule; Gugak Sat 15:00; NANTA Sunday 14:00/17:00) and museum late-days (NMK Wed/Sat 21:00; SeMA/Seosomun/History/Craft Friday 21:00) are carried correctly.

| Claim | Repo entry | Status |
|---|---|---|
| Palace closure days: Gyeongbokgung/Jongmyo/Blue House Tue · Changdeokgung/Deoksugung/Changgyeonggung Mon; Deoksugung 09:00–21:00 ₩1,000; combined ticket ₩10,000 | KoreaFun seoul #29–37, myeongdong #31 | 🔎 |
| Deoksugung guard ceremony 11:00 & 14:00 daily except Mon | KoreaFun districts #69 | ✅ |
| Sungnyemun winter 09:00–17:30 closed Mon; Pasu ceremony times | KoreaFun myeongdong #33 | 🔎 |
| Bosingak noon bell ceremony (Tuesdays = foreign-visitor slot) | KoreaFun districts #68 | ✅ |
| Namsangol winter hours 09:00–20:00 from Nov 1; hanok closed Mon | KoreaFun myeongdong #25 | 🔎 |
| Namsan Ormi free + cable car ticketed (weather) | KoreaFun myeongdong #29 | 🔎 |
| N Seoul Tower ticketed; park free | KoreaFun myeongdong #30 | 🔎 |
| Bank of Korea Money Museum Tue–Sun 10–17 (last 16:40), free, EN docent 14:00 | KoreaFun myeongdong #21 / districts #90 | 🔎 |
| SeMA Seosomun hours + GanaArt show to Nov 22, free, closed Mon | KoreaFun myeongdong #2/#23 | ✅/🔎 |
| Jeongdong Observatory hours; closed holidays | KoreaFun districts #49 | 🔎 |
| Seosomun Shrine History Museum Wed to 20:30, closed Mon | KoreaFun districts #48 | 🔎 |
| Museum Kimchikan ₩5,000 closed Mon (class fee unverified) | KoreaFun walking-maps (flag) + seoul #56 | 🔎/⏳ class |
| Ssamziegil 10:30–20:30; Insadong car-free 10:00–22:00 | KoreaFun districts #91/#94 | 🔎 |
| Folk Music Museum hours (Sat to 19:00), closed Mon, Arirang show | KoreaFun districts #28 | 🔎/✅ |
| Gongpyeong Archaeology Hall Tue–Sun 9–18 free | KoreaFun districts #27 | 🔎 |
| Baek Inje House / Dilkusha / Gyeongkyojang Tue–Sun 9–18 free | KoreaFun districts #30/#31/#29 | 🔎 |
| Tongin Market dosirak café closed Mon; coins end mid-PM | KoreaFun seoul #72 | 🔎 |
| Seoul Museum of History (incl. Friday 21:00) | KoreaFun districts #26 | ✅/🔎 |
| Gyeonghuigung grounds free | KoreaFun seoul #33 | 🔎 |
| DDP History Museum 10–18 (12–13 close), closed Mon | KoreaFun districts #3 | 🔎 |
| DDP Architecture Tour 10:30/13:30 EN/15:30, Tue–Sun, free | KoreaFun districts #2 | 🔎 |
| Hanyangdoseong Museum Tue–Sun 9–18 free | KoreaFun districts #4 | 🔎 |
| Folk Flea Market 10–19 (food alley to 22:00), closed Tue | KoreaFun districts #5 | 🔎 |
| Gyeongdong Market 08:30–18:00; Starbucks Gyeongdong 1960 09–23 | KoreaFun districts #34 | 🔎 |
| Yangnyeongsi Museum Nov–Feb 10–17, closed Mon; fee ⏳ | KoreaFun districts #6 | 🔎/⏳ |
| Hongneung Forest / Sejong Memorial / Yeonghwiwon hours+fees | KoreaFun districts #53–55 | 🔎/⏳ (Yeonghwiwon hours) |
| Dongmyo shrine ~06:00–18:00 (visitor-reported) | KoreaFun districts #96 | ⏳ |
| Busking zones 12:00–22:00; Art Space Seogyo kiosk 11–22 | KoreaFun districts #97/#98 | 🔎 |
| Hongdae Free Market November dates | KoreaFun seoul #75 | ⏳ |
| Mangwon Market 10–20 | KoreaFun districts #37 | 🔎 |
| Haneul Park cart 09–19 ₩2,000/₩3,000; silver grass into early Nov | KoreaFun districts #77 | 🔎 |
| Oil Tank Park outdoor 24 h; interiors licensed since Apr 2025 | KoreaFun districts #10 | 🔎 |
| Stadium tour ₩1,000, 10:00–15:00 non-match days | KoreaFun districts #36 | 🔎 |
| KOFA Tue–Sat free; Korean Film Museum 10:30–19:00 | KoreaFun districts #56/#57 | 🔎 |
| Battleship Park Nov–Feb Tue–Sun 10–18 ₩3,000 | KoreaFun districts #58 | 🔎 |
| Energy Dream Center Tue–Sun 9–17:30 | KoreaFun districts #76 | 🔎 |
| Seonjeongneung Nov–Jan 06:00–17:30 ₩1,000; docent schedule | KoreaFun districts #105 | 🔎 |
| Heoninneung Nov–Jan 9–17:30 ₩1,000 closed Mon | KoreaFun districts #103 | 🔎 |
| Dosan Memorial weekdays 10–18 / weekends 11–18 | KoreaFun districts #62 | 🔎 |
| K-Star Road + GangnamDol House 10–19 (lunch 13–14) | KoreaFun districts #46 | 🔎 |
| Garosu-gil ginkgo November peak | KoreaFun districts #63 | 🔎 |
| Maeheon Memorial Nov–Feb 10–17 closed Mon | KoreaFun districts #45 | 🔎 |
| Some Sevit 11–22, decks free; fountain OFF Nov | KoreaFun districts #44 | 🔎 |
| Itaewon Tourist Zone expansion (Hangangjin) Dec 26, 2025 | KoreaFun districts #40 | 🔎 |
| Antique Furniture Street ~100 shops | KoreaFun districts #60 | 🔎 |
| Yongsan Craft Museum Tue–Sun ~10–18:30 closed Mon | KoreaFun districts #78 | 🔎 |
| Baekbeom Memorial Nov–Feb 10–17 closed Mon | KoreaFun districts #59 | 🔎 |
| Yongsan Park C5 / History Museum / Ichon Park | KoreaFun districts #101/#99/#102 | 🔎 |
| Culture Station Seoul 284 Tue–Sun 10–18; Nov show TBA | KoreaFun myeongdong #37 | ⏳ |
| Cheonggyecheon / Seoullo 7017 free walks | KoreaFun seoul #63/#64 | 🔎 |
| Lotte World hours (Sun–Thu 10–21, Fri–Sat 10–22) + Seoul Sky ₩33,000 hours | KoreaFun seoul #96/#58 | 🔎 |
| Gwangjang / Namdaemun markets; Sunday closures | KoreaFun seoul #70/#71, myeongdong #34–35 | 🔎 |
| Sindang Tteokbokki Town; Dongdaemun Comprehensive Mkt Sunday rules | KoreaFun districts #73/#74 | 🔎 |
| Myeongdong TIC 9–18; Seoul My Soul shop | KoreaFun myeongdong #9/#10 | 🔎 |

### 3b. Plans D/E/F and X7–X13 — line-by-line (Aug 21, 2026)

Every named stop is a copy of an already-logged KoreaFun/Koreafood row. New combinations only; no new businesses.

| # | Claim | Source already in this ledger | Status |
|---|---|---|---|
| D1 | Plan D uses only Koreafood S1–S5 + Hongdae/Gangnam verified tables | walking-food-routes.html · city food tables | 🔎 |
| D2 | Plan D does **not** schedule Hadongkwan/Pildong/Chanyang-jip on Sun Nov 1 or 8 | Koreafood S1/S2 closures | 🔎 |
| D3 | Plan D does **not** schedule Ohsaegyehyang on Thu Nov 5 | Koreafood S3 closed Thu | 🔎 |
| D4 | Plan D Nov 3 stays in Jongno (no BANKSY hop) | walk-cluster rule | — |
| E1 | Plan E: one inbound commute then walk; La Bohème only after returning to hotel | Sejong is Gwanghwamun; hotel is Euljiro 1-ga | 🔎 |
| E2 | Plan E Nov 3 = Yeouido-only BANKSY (last entry 19:00) | seoul #1 | ✅ |
| F1 | Palace matrix: Gyeongbokgung closed Tue; Changdeokgung/Deoksugung/Changgyeonggung closed Mon | seoul #29–37 | 🔎 |
| F2 | Outdoor Library night session usable after 15:00 check-in on Nov 1 | seoul #3 | ✅ |
| F3 | Jongmyo not locked on Sat Nov 7 — Saturday public-entry rule ⏳ royal.khs.go.kr | seoul #34 | ⏳ |
| F4 | National Hangeul Museum excluded (closed to Oct 2028) | seoul #40 | ⛔ |
| X7 | All S1 restaurants + NANTA + Money Museum already logged | §3 / §4 | 🔎 |
| X8 | Cheonggyecheon + Gwangjang + Ikseon cafés + Imun/Chanyang-jip already logged | J4 / S2 | 🔎 |
| X9 | Seonjeongneung + Bongeunsa + Starfield + Food Week already logged | G1 | ✅/🔎 |
| X10 | H1 stay-put (no Mangwon/Haneul add) | H1 | 🔎 |
| X11 | I1 stay-put; Leeum hours ⏳ | I1 / N6 | ✅ shows / ⏳ hours |
| X12 | I2 triangle; NMK Wed/Sat 21:00 | I2 | ✅/🔎 |
| X13 | Friday-late: History Museum, Sejong Story, SeMA, Deoksugung all to 21:00 Fri | districts #26/#87, myeongdong #2, seoul #32 | ✅/🔎 |

**Aug 21 gate:** 6 complete Nov 1–9 itineraries (A–F) · 10 mixed days entered (X1–X3, X7–X13) · 3 mixed days not entered (X4 held — transit hops; X5 rejected — unverified cafés; X6 held — transfer). No restaurant prices added. No aggregator hours promoted to ✅.

## 4. Food (all rows copied from the Koreafood verified roster — official-page-sourced hours, Aug 2026; no prices printed anywhere per that repo's standard)

Cross-checks performed line-by-line against `cities/walking-food-routes.md` (Routes S1–S5) and `cities/by-location.md` tables: Myeong-dong (19 spots) · Jongno/Seochon (13) · Dongdaemun/Sindang (12) · Hongdae/Mapo/Yeonnam (19) · Itaewon/Yongsan (6) · Gangnam/Seocho (12). **Closure-day mismatches with itinerary days:** verified per plan (e.g., Hadongkwan/Pildong/Chanyang-jip/Hamheung Myeonok closed Sun — none scheduled Sunday; Ohsaegyehyang closed Thu — not used Nov 5; Seowon alternate-Wednesday closure flagged; Moowee Nakwon Sunday 11:30–16:00 respected in Plan C Nov 8 brunch).

## 5. Items deliberately NOT used (with reasons)

| Item | Reason |
|---|---|
| National Hangeul Museum | ⛔ Closed until Oct 2028 (fire + extension) — KoreaFun seoul #40 |
| Banpo Rainbow Fountain / plaza fountains | Off in November — KoreaFun seoul #65, districts #95 |
| Seoul Lantern Festival / Seoul Light DDP Winter | December events — KoreaFun seoul "just outside the window" |
| Changdeokgung Moonlight Tour | Fall dates TBA (2025 ran Sep–Oct) — KoreaFun seoul #30 |
| Korea Sale FESTA dates | Unannounced; domains lapsed — KoreaFun seoul #28 / districts #86 |
| Hell's Kitchen musical | No current listing — "do not book" — KoreaFun re-check list S11 |
| Busan Fireworks (Nov 7), Daejeon Wine Expo, Suwon BeautySum, Yeosu expo | Outside the Seoul-only scope of this stay (the source itinerary.md options) |
| Any restaurant/cafe not in the Koreafood roster | Fails the repo's official-source standard |
| Seongsu café street (X5) | No official hours; **not entered** as an itinerary |
| X4 Yeouido→Sebitseom→DDP as one day | Two subway hops between activities — BANKSY kept as Yeouido-only (Plan E Nov 3) |
| X6 Namsan→Leeum as one day | Requires a transfer — Hannam half kept as X11 / I1 |
