# Manual Testing Exercises | QA Portfolio

A collection of manual QA practice exercises focused on designing test cases, validating user inputs, and recording observations. Prepared as a learning portfolio for an entry-level QA/Software Tester role.

> **Practice portfolio — not a commercial QA engagement.** These files preserve historical training/exercise records. Reported execution statuses do not indicate that the scenarios were recently rerun or that any referenced application is currently available.

## Exercises

| Exercise | Focus | Test cases | Artifacts |
| --- | --- | ---: | --- |
| [01 — Login & CAPTCHA](01-login-captcha/) | Authentication input validation and CAPTCHA | 26 | Excel test cases, review notes |
| [02 — Reset Password](02-reset-password/) | Email/CAPTCHA validation and UI feedback | 27 | Excel test cases, bug list |
| [03 — Change Password](03-change-password/) | Password update and validation scenarios | 16 | Excel test cases, bug sheet |
| [04 — Password Validation](04-password-validation/) | Password test design and decision table | 37 | Excel test cases, decision table |

**Total:** 106 entries identified by test case IDs across the four workbooks. The count is not a measure of execution coverage or defect count.

## Skills demonstrated

- Writing test scenarios with preconditions, test steps, test data, and expected results
- Positive, negative, and input-validation testing
- Combining validation conditions and reviewing edge cases
- Using a decision table for systematic test design
- Documenting observed results and recording bugs in practice artifacts

## Repository structure

```text
manual-testing-exercises/
├── README.md
├── 01-login-captcha/
│   ├── README.md
│   └── Testcase_ITLearn_01_Reviewed.xlsx
├── 02-reset-password/
│   ├── README.md
│   └── Testcase_ITLearn_02_Reviewed.xlsx
├── 03-change-password/
│   ├── README.md
│   └── Testcase_ITLearn_03_Reviewed.xlsx
└── 04-password-validation/
    ├── README.md
    └── Testcase_ITLearn_04.xlsx
```

## How to explore

Select an exercise above, read its short scope statement, and open the corresponding `.xlsx` workbook. The Excel files are preserved from the supplied practice materials rather than rewritten for this README.

## Important limitations

- Results in exercises 01–03 are historical records and have **not** been independently rerun or verified for this portfolio. Some status and actual-result fields may require further consistency review.
- Exercise 04 contains design cases without recorded execution statuses.
- Some test cases depend on the original exercise specification and may not generalize to other apps.
- Before publishing, confirm all workbook data is safe to share and replace any credentials or personal data that are not explicitly dummy data.

## Background

Created as part of my hands-on manual testing practice, with a focus on becoming a QA/QC Tester and developing stronger test design and defect reporting skills.
