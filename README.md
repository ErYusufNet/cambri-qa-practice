# Cambri QA Practice

A hands-on QA case study built to prepare for a QA Engineer interview at Cambri (https://www.cambri.io/), an AI-powered consumer research platform used by brands like Coca-Cola and Danone to test product concepts with real consumers.

## Why this exists

Rather than only reading the job description, I wanted to actually practice the kind of work the role involves: designing test cases from requirements, running manual/exploratory testing on a real product, and tracking everything in Jira the way the posting describes ("Create practical test cases in Jira", "exploratory, risk-based, regression" testing).

I don't have access to Cambri's real production system, so I looked for a publicly usable platform with a similar mechanic - a researcher creates a study/survey, a participant completes it, results are collected. I chose Prolific (https://www.prolific.com), which lets you build a real survey (Survey Builder) and preview/complete it as a test participant. I don't know how closely it matches Cambri's actual internal tooling, but the researcher/participant/results shape is comparable enough to practice real QA thinking on.

Everything in this repo reflects actual testing performed on Prolific, not hypothetical scenarios - test cases were written first from the study-creation workflow, then genuinely executed, with real results (including one real bug found).

## What's inside

- test-plan.md - Scope and approach
- test-cases.md - All test cases, with real PASS/FAIL results and notes
- bug-reports/BUG-001.md - A real bug found during testing, in Jira-style format
- jira-board.md - Summary of how this was tracked in Jira (board structure, ticket IDs)

## Tools used

- Prolific (Survey Builder) - the system under test
- Jira - test case and bug tracking (Kanban board, ticket IDs referenced throughout)
- Manual + exploratory testing, no automation (matches the "mostly manual QA" nature of the target role)

## Background

I currently work as a Test Automation Engineer (Python, Robot Framework, REST API testing, CI/CD) with prior manual QA experience. This project was deliberately manual and exploratory to match what was described about the Cambri QA role specifically.
