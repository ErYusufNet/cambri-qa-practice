# Test Plan

## Scope

Testing the study/survey creation and completion workflow on Prolific's Survey Builder, as a practice stand-in for a Cambri-style consumer research platform:

1. Researcher side - creating a study, naming it, writing an introduction, building survey questions
2. Participant side - previewing and completing the survey as a test participant
3. Validation and edge cases - required fields, draft-saving behavior, question type behavior

## Out of scope

- Cambri's actual production application (no access, and not appropriate to test without permission)
- Prolific's payment/wallet system beyond observing that it's involved
- Load/performance testing
- Cross-browser testing (tested in one browser session only, due to time)

## Approach

Risk-based and exploratory rather than exhaustive.

## Environment

- Browser: Chrome
- Tool: Jira (Kanban board QA Manual Testing, project key KAN)
- System under test: Prolific Survey Builder
