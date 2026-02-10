# Marketing Performance Report

Analyze marketing performance data and generate actionable reports.

## Instructions

1. Read `context/CLAUDE.md` for business context and strategy.
2. Ask the user to provide or paste:
   - **Data source** (Google Analytics, social media metrics, email platform stats, ad platform data)
   - **Time period** for the report
   - **Comparison period** if applicable (e.g., month-over-month, year-over-year)
3. Analyze the data and generate a report covering:

### Report Sections

#### Executive Summary
- 3-5 bullet points on the most important takeaways
- Overall trend direction (improving, stable, declining)

#### Traffic & SEO
- Organic traffic trends
- Top-performing pages/posts
- Keyword ranking changes
- New vs returning visitors

#### Content Performance
- Top-performing blog posts (by traffic, engagement, conversions)
- Social media engagement rates by platform
- Email open rates, click rates, unsubscribe rates
- Content that underperformed and why

#### Conversion Metrics
- Free trial signups
- Trial-to-paid conversion rate
- Traffic-to-trial conversion rate by channel
- Top converting pages/content

#### Recommendations
- **Quick wins** — things to do this week
- **This month** — tactical improvements
- **Next quarter** — strategic changes

4. Save to `output/report/{YYYY-MM-DD}-performance-{period}.md`

## When No Data Is Provided

If the user doesn't have data to paste, offer to:
- Create a reporting template/dashboard structure they can fill in
- Suggest which metrics to track and where to find them
- Set up a KPI framework for their marketing efforts
