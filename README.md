# alfido-tech-traffic-analysis# Alfido Tech — Smart-Link Traffic Analysis

Analysis of 226K+ landing-page events (pageviews, previews, clicks) across 743
smart links and 211 countries, built from a raw PDF export.

## What's inside
- `Alfido_Tech_Traffic_Analysis.ipynb` — full pipeline: PDF parsing/cleaning,
  metrics, funnel + geo + top-page visualizations
- `Alfido_Tech_Traffic_Report.md` — key insights and 5 conversion recommendations

## Key findings
- 39.2% overall pageview→click conversion
- Traffic volume and conversion quality don't correlate — biggest markets
  (Saudi Arabia, India) underperform vs. Pakistan/US on CTR
- Traffic is concentrated in a small number of pages — high-leverage fix targets
- Volume declines ~15% over the week while CTR holds steady (a reach issue, not
  a conversion issue)

## Recommendations
1. Fix worst-converting high-traffic pages first
2. Reallocate spend toward higher-converting markets
3. Instrument session ID / referrer / timestamp for true attribution
4. Test the underused preview step
5. Put top pages on a recurring re-promotion cadence

## Stack
Python, pandas, matplotlib, poppler (pdftotext) for extraction
