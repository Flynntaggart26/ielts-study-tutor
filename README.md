# IELTS Study Tutor

> Advanced self-study system + curated best sources + human/AI tutor framework for IELTS Academic & General Training (Band 6.0 → 8.5).

[![IELTS](https://img.shields.io/badge/IELTS-Academic%20%7C%20General-blue)]()
[![Level](https://img.shields.io/badge/Level-B1--C2-green)]()
[![Target](https://img.shields.io/badge/Target-Band%206.0--8.5-orange)]()
[![License](https://img.shields.io/badge/License-MIT-lightgrey)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)]()

Stop hopping between random YouTube videos and PDFs. This repo gives you **what to use, how to study, and how to get feedback** — in one place.

## ✨ What You Get

**1. Best Sources for IELTS (curated, rated, no fluff)**
- Official Cambridge / IDP / British Council materials ranked by value
- Best books for each band level, best websites, apps, YouTube, podcasts
- Free vs paid, Academic vs General labels, direct links
- Machine-readable list in [`data/sources.json`](data/sources.json)

**2. How to Study + Tutor System**
- Diagnostic → plan → deliberate practice → mock → review loop
- Ready study plans: 7-day crash, 4-week, 8-week, 12-week
- Skill guides for Listening, Reading, Writing Task 1/2, Speaking, Vocab, Grammar
- AI tutor prompts + human tutor framework + feedback templates + band descriptors checklist

## 🚀 Start Here (5 minutes)

1. **Take a diagnostic:** Do 1 full Listening + Reading test + 1 Writing Task 2 + 2-min Speaking recording. Score with [`study-plans/self-assessment.md`](study-plans/self-assessment.md).
2. **Pick your plan:**
   - ≤ 1 week left → [`study-plans/crash-7-days.md`](study-plans/crash-7-days.md)
   - 1 month, Band 6 → 7 → [`study-plans/4-week-band-6-to-7.md`](study-plans/4-week-band-6-to-7.md)
   - 2 months, structured → [`study-plans/8-week-zero-to-hero.md`](study-plans/8-week-zero-to-hero.md)
   - 3 months, Band 7.5+ → [`study-plans/12-week-comprehensive.md`](study-plans/12-week-comprehensive.md)
3. **Get your sources:** Open [`sources/best-sources.md`](sources/best-sources.md) — install only Top 5, ignore the rest until Week 3.
4. **Study with tutor loop:** Follow [`tutor/how-to-study-guide.md`](tutor/how-to-study-guide.md) + copy prompts from [`tutor/ai-tutor-prompts.md`](tutor/ai-tutor-prompts.md).
5. **Track weekly:** Copy [`templates/weekly-planner.md`](templates/weekly-planner.md) + [`templates/study-tracker.csv`](templates/study-tracker.csv).

## 🗂️ Repository Structure

```text
ielts-study-tutor/
├── README.md                      # you are here
├── sources/
│   ├── best-sources.md            # master curated list (start here)
│   ├── books-by-level.md          # B1→C2 book roadmap
│   ├── websites-apps.md           # interactive practice + tools
│   ├── youtube-podcasts.md        # listening + strategy channels
│   └── practice-tests.md          # official mocks + where to take them
├── skills/
│   ├── listening.md
│   ├── reading.md
│   ├── writing-task-1.md
│   ├── writing-task-2.md
│   ├── speaking.md
│   ├── vocabulary.md
│   └── grammar.md
├── study-plans/
│   ├── self-assessment.md
│   ├── crash-7-days.md
│   ├── 4-week-band-6-to-7.md
│   ├── 8-week-zero-to-hero.md
│   └── 12-week-comprehensive.md
├── tutor/
│   ├── how-to-study-guide.md      # the core study method
│   ├── tutor-framework.md         # for human tutors / study partners
│   ├── ai-tutor-prompts.md        # copy-paste ChatGPT/Claude prompts
│   ├── feedback-templates.md      # Writing & Speaking correction sheets
│   └── common-mistakes.md
├── templates/
│   ├── weekly-planner.md
│   ├── study-tracker.csv
│   ├── writing-checklist.md
│   └── speaking-self-evaluation.md
├── data/
│   └── sources.json               # all sources in JSON
├── .github/
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── ISSUE_TEMPLATE/
├── CONTRIBUTING.md
└── LICENSE
```

## 🏆 Top 5 Sources (TL;DR)

| # | Source | Best For | Cost | Link |
|---|--------|----------|------|------|
| 1 | Cambridge IELTS 10–19 + Official Guide | Real mocks | Paid / library | [Cambridge](https://www.cambridgeenglish.org/) |
| 2 | IELTS Liz (ieltsliz.com) | Free strategy + Task 1/2 models | Free | [ieltsliz.com](https://ieltsliz.com) |
| 3 | E2 IELTS / IELTS Advantage YouTube | Speaking/Writing walkthroughs | Free | [E2](https://www.youtube.com/@E2IELTS) / [Advantage](https://www.youtube.com/@IELTSAdvantage) |
| 4 | IELTS Cambridge App / IELTS Prep App | Daily practice | Free | App Store / Play Store |
| 5 | Anki + Academic Word List | Vocab retention | Free | [Anki](https://apps.ankiweb.net/) |

Full rated list with 40+ sources: [`sources/best-sources.md`](sources/best-sources.md).

## 🧠 The Study Method (Summary)

```
Diagnose → Focused Input → Deliberate Practice → Feedback → Spaced Review → Mock
```

- **80/20 rule:** Writing Task 2 + Speaking Part 2/3 move your band most. 50% of time goes there.
- **No passive studying:** Every Listening/Reading session ends with error-log (why you missed it).
- **Writing:** 3 essays/week minimum, each corrected twice (self-checklist → AI/tutor).
- **Speaking:** 15 min/day recorded, 1 part fully transcribed weekly.
- **Vocab:** 10 collocations/day in Anki, only from your own corrections + past papers.

Details: [`tutor/how-to-study-guide.md`](tutor/how-to-study-guide.md).

## 📊 Band Score Quick Map

| Band | Listening (40) | Reading Academic (40) | Writing | Speaking |
|------|----------------|------------------------|---------|----------|
| 6.0 | 23-25 | 23-26 | addresses task, frequent errors, limited cohesion | fluent with pauses, simple linkers |
| 7.0 | 30-31 | 30-32 | clear position, less common vocab, some errors | flexible vocab, complex sentences with slips |
| 7.5+ | 33+ | 33+ | wide range, natural cohesion, rare errors | natural, precise, native-like collocations |

Use the official descriptors checklist before booking the test.

## 🤝 For Tutors

Use [`tutor/tutor-framework.md`](tutor/tutor-framework.md) for lesson structure (60/90-min templates), diagnostic script, homework policy, and progress tracking. Give students [`tutor/feedback-templates.md`](tutor/feedback-templates.md) so corrections are actionable.

## 🙋 FAQ

**Academic or General?** Listening/Speaking identical. Reading/Writing differ — see skill guides for Task 1 letter vs report split.

**How long to improve 0.5 band?** ~150-200 focused hours. 4-6 weeks at 2h/day with feedback.

**Free only — possible?** Yes to Band 7. Past papers + IELTS Liz + E2 + Anki is enough. Books help for 7.5+ Writing.

**When to book?** When 3 consecutive mocks hit target ±0.5 under timed conditions.

## 🤲 Contributing

Found a better source? Fixed a broken link? See [`CONTRIBUTING.md`](CONTRIBUTING.md). PR template in [`.github/PULL_REQUEST_TEMPLATE.md`](.github/PULL_REQUEST_TEMPLATE.md).

## 📄 License

MIT — see [LICENSE](LICENSE). Official IELTS materials belong to their owners; this repo curates links, it does not redistribute copyrighted tests.

---

If this helped you, ⭐ star the repo and share your band score in Discussions.
