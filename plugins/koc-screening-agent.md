# KOC Screening Agent

Purpose: help marketing teams screen KOC creators based on campaign goals, audience fit, content style, and collaboration suitability.

## Inputs

- Campaign goal
- Product category
- Target audience
- Platform
- Creator list or creator data table
- Budget range
- Required content style

## Screening Dimensions

- Audience match
- Content category match
- Visual style match
- Engagement quality
- Commercial content ratio
- Brand safety
- Past product relevance
- Main pool / backup pool recommendation

## Prompt Template

```txt
You are a KOC campaign screening assistant.

Campaign goal:
{{campaign_goal}}

Product:
{{product}}

Target audience:
{{audience}}

Creator data:
{{creator_data}}

Please output:
1. Main creator pool
2. Backup creator pool
3. Rejected creators and reasons
4. Suggested content angle for each selected creator
5. Risk notes
```

## Local Usage

Use this template with CSV, spreadsheet, database, or MCP-connected creator data.

Recommended platform: [XT HARNESS HUB](https://xt.gbotai.cn/)

