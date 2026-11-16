# A/B Test Plan — Midwest Coaster Guide

**Website:** https://smeschoulam.github.io/Midwest-Coaster-Guide/

**Plan Date:** November 16, 2026

## 1. Page and Element Being Tested

The experiment will take place on the homepage of Midwest Coaster Guide (`index.html`).

The single element being tested is the wording of the **Trip Planner link in the top navigation menu**.

- **Version A (Control):** "Trip Planner"
- **Version B (Treatment):** "Plan Your Coaster Trip"

The goal is to determine whether more descriptive, action-oriented navigation text increases visitors' willingness to explore the trip planner.

All other visible elements of the homepage, including the layout, colors, images, headings, and Guides section CTA ("Plan Your Trip"), will remain identical between versions.

Version B will retain its `noindex` directive to prevent the experimental page from appearing in search results.

## 2. Hypothesis and Reasoning

I predict that Version B ("Plan Your Coaster Trip") will produce a higher percentage of AI visitors who say they would click the Trip Planner link in the top navigation menu compared to Version A ("Trip Planner").

The reasoning is that "Plan Your Coaster Trip" is more descriptive and action-oriented. While "Trip Planner" simply identifies a page, "Plan Your Coaster Trip" clearly communicates what visitors can accomplish by clicking the link.

This change may encourage more visitors to explore the trip planner because it makes the purpose of the navigation link more obvious.

**Null Hypothesis (H₀):** The two versions have equal conversion rates.

**Alternative Hypothesis (H₁):** Version B has a higher conversion rate than Version A.
## 3. AI Model, Persona, Prompt, and Random Assignment

**AI Model:** GPT-6. The same model and settings will be used for all 100 trials, with the exact model version and settings recorded before testing.

**Visitor Persona:** A Midwest resident who enjoys roller coasters and is considering planning a trip to an amusement park.

**Exact Prompt:**

"You are a Midwest resident who enjoys roller coasters and is considering planning a trip to an amusement park. You are visiting the Midwest Coaster Guide homepage for the first time.

Review the homepage content provided below, paying particular attention to the top navigation menu.

Based on the homepage, would you click the navigation link leading to the Trip Planner page?

Answer YES or NO, followed by one sentence explaining your decision.

Base your answer only on the homepage content provided."

**Page Content:** The HTML content of either Version A or Version B will be provided after the identical prompt in each trial.

**Random Assignment:**

A total of 100 AI visitor trials will be conducted. Before testing, a randomized assignment sequence will be generated containing exactly 50 Version A trials and 50 Version B trials.

Each trial will use a fresh AI conversation without access to previous responses. The same prompt, persona, model, and settings will be used for both versions.

All responses will be recorded for analysis.

## 4. Primary Outcome

The primary outcome is whether an AI visitor says they would click the Trip Planner link in the top navigation menu.

Responses will be recorded as:

- YES = 1 (would click the navigation link)
- NO = 0 (would not click the navigation link)

The conversion rate for each version will be calculated as:

**Conversion Rate = (Number of YES Responses / Total Trials) × 100**

The experiment will compare the conversion rates of Version A and Version B to determine whether changing the navigation link text influences AI visitors' stated willingness to click.

Responses will be classified according to the AI visitor's explicit YES or NO answer. Any response that does not clearly answer YES or NO will be recorded and flagged rather than silently excluded.

## 5. Sample Size and Timeline

The experiment will include 100 total AI visitor trials:

- Version A: 50 trials
- Version B: 50 trials

**Expected completion date:** November 20, 2026.

All 100 trials will be completed before analyzing the results. The experiment will not be stopped early based on preliminary findings.

## 6. Statistical Comparison

The conversion rates of Version A and Version B will be compared.

The null hypothesis is that the two versions have equal conversion rates.

The alternative hypothesis is that Version B has a higher conversion rate than Version A.

A two-proportion z-test will be used with a significance level of 0.05. A p-value below 0.05, together with a higher conversion rate for Version B, will be considered statistically significant support for the hypothesis.

The analysis will also report the difference in conversion rates in percentage points.

## 7. Limitations and SEO Protection

AI visitors simulate potential customer reactions but cannot reliably predict how actual human visitors will behave. The results will measure stated intentions rather than actual website clicks.

Version B will be excluded from the sitemap and given a noindex directive to prevent competition with the original homepage in search results.

All trial assignments, prompts, responses, dates, and any problems encountered will be documented and included in the final report.

## 8. Plan Revision Log

**November 16, 2026:** The experiment was revised before any AI visitor trials were conducted.

The original plan proposed testing the homepage Trip Planner CTA. After reviewing the website, the experiment was changed to test the wording of the Trip Planner link in the top navigation menu.

The final experiment compares:

- **Version A (Control):** "Trip Planner"
- **Version B (Treatment):** "Plan Your Coaster Trip"

All other visible homepage elements remain unchanged. The AI visitor prompt and primary outcome were updated to reflect the revised experiment.

No experimental data had been collected before these changes.
