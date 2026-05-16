# work-monitor

Work Monitor skill for daily planning, daily review, weekly review, and monthly review.

It turns a user's messy daily tasks into a structured workflow:

1. Collect today's todos
2. Summarize and confirm priorities
3. Ask for concrete time slots
4. Generate a visual daily tracking page: core task cards, timeline, status board, spare-time view
5. Sync confirmed plans to Feishu Daily Monitor docs when Feishu/lark-cli is available
6. Sync clear time-blocked core tasks, meetings, travel, meals, and fixed blocks to Feishu Calendar
7. Ask for actual completion status later in the day
8. Compare planned tasks with actual completion and append the review to the same Feishu doc
9. Produce weekly reviews
10. Produce monthly reviews

## Install

From this repository root:

```bash
npx skills add . --yes --global
```

## Usage

```text
/work-monitor
/daily-monitor
帮我安排今天
帮我做每日计划
帮我复盘今天
帮我做周复盘
帮我做月复盘
帮我做 work monitor
```

## Source

The skill definition is in `SKILL.md`.
