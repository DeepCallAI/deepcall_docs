---
layout: default
title: Pilot Calls Page Guide
nav_order: 4
description: Comprehensive guide to using the Calls page in the DeepCall pilot
---

# DeepCall Pilot Calls Page Guide

Welcome to the DeepCall Pilot Calls page! This guide will help you navigate the features of the Calls page, understand its components, and use it effectively during the pilot.

---

## Calls Table Overview

The main feature of this page is the calls table, which lists all AI-analyzed mystery shopping calls within the selected time frame and filters.

### Table Columns

- **Select Checkbox**  
  Select individual calls for batch actions like export or flagging. Use the top checkbox to select or deselect all filtered calls.

- **Call ID**  
  Unique identifier for each call.

- **Location**  
  Currently empty for the pilot.

- **Date**  
  Date and time when the call was analyzed.

- **Duration**  
  Length of the call displayed as minutes and seconds.

- **Compliance Status**  
  Shows ✅ Pass or ❌ Fail based on compliance scores.

- **Overall Score**  
  The overall quality score assigned to the call.

- **Call Summary**  
  A brief truncated snippet of the AI-generated summary. Hover to see the full text.

- **Actions**  
  Two buttons:
  - **View Call**: Opens a detailed side panel for the selected call.
  - **Download Report**: (Not available in the pilot yet.)

---

## Filters

Located above the calls table, filters allow you to narrow down calls based on:

- **Compliance Status**  
  Filter calls by Pass, Fail, or show All.

- **Score Range**  
  Select calls within specific overall score ranges.

- **Call Duration**  
  Filter calls by duration buckets: less than 1 minute, 1 to 5 minutes, or more than 5 minutes.

- **Reset Filters**  
  Quickly reset all filters back to default (All).

Filters update the table dynamically.

---

## Pagination

The table shows 10 calls per page. Use the pagination bar below the table to navigate through pages. The current page is highlighted for clarity.

---

## Call Details Side Panel

Clicking **View Call** opens a sliding side panel from the right showing detailed information for that call, including:

- Call ID and analyzed date/time
- Summary card with duration, brand voice match score, compliance status, overall score, and tone
- Full call summary text
- Detailed scores and justifications for categories such as Greeting, Product Knowledge, Confidence, Politeness, and Resolution
- Overall justification
- AI observations, staff tags, flagged issues, and recommended actions related to the call

The panel is scrollable with a close button at the top.

---

## Known Pilot Limitations

- **Download Report** button is visible but non-functional in the pilot.
- **Export Selected** and **Flag Selected** buttons do not currently trigger backend actions.
- Location data for calls is not yet available.

---

## Tips for Effective Use

- Use filters to focus on calls most relevant to your analysis.
- Select calls to prepare for batch actions when those features are enabled.
- Review flagged issues carefully in the side panel to identify training needs.
- Use the AI insights and detailed scores to guide quality improvements.

---

## Support

If you encounter issues or have questions, please contact your DeepCall pilot support representative. Your feedback is invaluable.

---

Return to the [Settings Page Guide](pilot-settings.md) or [Dashboard Overview](pilot-dashboard.md).
