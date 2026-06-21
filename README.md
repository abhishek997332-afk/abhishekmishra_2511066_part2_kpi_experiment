# abhishekmishra_2511066_part2_kpi_experiment

# KPI Framework, Business Experiment Analysis & Decision Recommendation

## Business Context

A subscription-based digital product company launched a new onboarding and activation campaign. Users were divided into Control and Treatment groups to evaluate whether the new experience improves conversion and engagement.

## Dataset Description

The dataset contains user-level experiment data including onboarding activity, conversion outcomes, revenue, engagement metrics, support activity, and user segments.

## North Star Metric

Paid Conversion Rate

## KPI Tree Summary

The KPI tree includes Acquisition, Activation, and Engagement drivers supporting Paid Conversion Rate. Guardrail metrics include Refund Rate, Support Ticket Rate, and Revenue Per User.

## Experiment Analysis Approach

Data quality checks were performed for missing values, duplicate user IDs, invalid binary values, revenue outliers, and segment distribution.

Pivot tables were used to compare Control and Treatment performance.

Segment-level analysis was conducted across Region, Device Type, and Traffic Source.

## Hypothesis Test Summary

Null Hypothesis: The treatment does not improve paid conversion rate.

Alternative Hypothesis: The treatment improves paid conversion rate.

Significance Level: 0.05

The treatment group achieved a higher conversion rate than the control group.

## Guardrail Metrics Considered

* Refund Rate
* Support Ticket Rate
* Days To Convert

## Final Recommendation

Launch the new onboarding experience while continuing to monitor guardrail metrics.

## Assumptions and Limitations

Some fields contain missing values.

Duplicate user IDs were identified during data quality checks.

Revenue outliers were retained as valid observations.

## Screenshots Included

* summary_metrics.png
* hypothesis_test_output.png
* kpi_tree_preview.png
