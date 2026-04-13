## 📊 QA & Testing Metrics

### Why We Need It

**Business:**
- Provides objective data to assess product quality before release decisions are made
- Makes the cost of quality visible — defect trends, rework effort, and escaped bugs
- Tracks testing progress against timelines to keep releases on schedule
- Builds stakeholder confidence with measurable, repeatable quality indicators

**Development Team:**
- Identifies where defects concentrate so testing and development effort can be focused
- Monitors test coverage to ensure critical areas are not under-tested
- Surfaces process inefficiencies — long defect resolution cycles, low automation ROI
- Gives teams a feedback loop to continuously improve testing effectiveness over time

---

### Aim
- Measure and communicate the quality of the product at every stage of the release cycle
- Track testing progress, coverage, and defect trends against defined thresholds
- Provide data-driven input for go/no-go release decisions
- Enable continuous improvement of the QA process through historical trend analysis

---

### The Distinction

> **Testing metrics** answer *"how is our testing going?"* — they measure the process.
> **QA metrics** answer *"how good is our product?"* — they measure the outcome.

---

### Testing Metrics — Process-Focused

| Metric | What It Measures | Example |
|---|---|---|
| **Test Execution Rate** | Percentage of planned test cases executed per cycle | 45/120 cases on day 2 → 37.5% — on track to finish on time |
| **Test Pass/Fail Rate** | Build stability at a glance | 218 passed, 8 failed, 4 blocked of 230 executed → 94.7% pass rate |
| **Test Case Productivity** | Cases written or executed per tester per period | Engineer A: 12/day vs Engineer B: 8/day — informs capacity planning |
| **Automation Rate** | Percentage of regression tests that are automated | 142/350 automated → 40.5%; target next quarter: 60% |
| **Test Execution Time** | How long the test suite takes to run | Full regression: 6.5 h manual → 45 min automated — 5.75 h saved per cycle |

---

### QA Metrics — Quality-Focused

| Metric | What It Measures | Example |
|---|---|---|
| **Defect Leakage Rate** | Bugs escaping to production | 7 of 85 defects reached production → 8.2% leakage, down from 12% |
| **Defect Density** | Defects per feature, module, or KLOC | Payment module: 14 defects / 3 features vs Profile: 2 / 5 — 7× higher density |
| **Mean Time to Detect (MTTD)** | Lag between a bug being introduced and found | Critical bug introduced Monday, found Wednesday → 2-day MTTD; target: <1 day |
| **Mean Time to Resolve (MTTR)** | Time from bug report to verified fix | Avg this quarter: Critical 4 h · High 1.5 d · Medium 4 d · Low 12 d |
| **Customer-Reported Defects** | Bugs found by real users, not QA | Q1: 23 → Q2: 11 after improving checkout regression — 52% reduction |

---

### Tools
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)
