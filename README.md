# Sprint-11

Project Summary – User Behavior and A/A/B Testing Analysis

In this project, I analyzed user behavior for a food product startup’s mobile app. The goal was twofold:

Sales Funnel Analysis
I examined the app’s user journey to identify drop-off points across key stages, such as:

-Tutorial
-MainScreenAppear
-OffersScreenAppear
-CartScreenAppear
-PaymentScreenSuccessful

I calculated how many users reached each stage and where the biggest user losses occurred, revealing the conversion efficiency from first interaction to purchase.

A/A/B Test Evaluation
The company tested a font redesign using an A/A/B experiment:

Groups 246 & 247: control (old fonts)

Group 248: test (new fonts)

I used a Z-test to compare user behavior (event participation rates) across groups. First, I verified if the control groups (246 vs. 247) were statistically similar. Then, I compared the test group (248) to each control group and their combined results for every key event.

Key Insights:

-No statistically significant differences were found between control groups.
-The test group (with new fonts) also showed no significant deviation from the controls.
-This suggests the font change did not negatively impact user engagement.

Additionally, I applied a Bonferroni correction to adjust for multiple hypothesis testing, lowering the significance threshold to avoid false positives.
