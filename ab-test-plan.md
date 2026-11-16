# A/B Test Plan — Midwest Coaster Guide

**Website:** https://smeschoulam.github.io/Midwest-Coaster-Guide/

**Plan Date:** November 16, 2026

## 1. Page and Element Being Tested

The experiment will take place on the homepage of Midwest Coaster Guide (`index.html`).

The single element being tested is the text of the call-to-action (CTA) button linking to the trip planner.

- **Version A (Control):** "Trip Planner"
- **Version B (Treatment):** "Plan Your Coaster Trip"

All other elements of the webpage, including layout, colors, images, and content, will remain identical.

## 2. Hypothesis and Reasoning

I predict that Version B will produce a higher percentage of AI visitors who say they would click the trip planner button.

The reasoning is that "Plan Your Coaster Trip" is more descriptive and action-oriented than "Trip Planner." It clearly communicates what visitors can accomplish by clicking the button, potentially increasing their interest in using the trip planner.

## 3. AI Model, Persona, Prompt, and Random Assignment

**AI Model:** GPT-6 (same model and settings for every trial, with the exact model version recorded when testing begins).

**Visitor Persona:** A Midwest resident interested in visiting amusement parks and planning a roller coaster trip.

**Exact Prompt:**

"You are a Midwest resident who enjoys roller coasters and is considering planning a trip to an amusement park. Read the following homepage for Midwest Coaster Guide. Based only on the information provided, would you click the trip planner button to start planning a roller coaster trip? Answer YES or NO, followed by one sentence explaining your decision."

The complete page text for Version A or Version B will be supplied after this identical prompt in every trial.

Each AI visitor will participate in a fresh conversation without memory of previous trials. All trials will use the same AI model and settings.

Before testing, 100 assignments will be randomly generated, with exactly 50 assigned to Version A and 50 assigned to Version B. The assignment order will be saved before collecting responses.

## 4. Primary Outcome

The primary outcome is whether the AI visitor says they would click the trip planner button.

Responses will be recorded as:

- YES = 1 (would click)
- NO = 0 (would not click)

The conversion rate for each version will be calculated as the number of YES responses divided by the total number of trials for that version.

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
