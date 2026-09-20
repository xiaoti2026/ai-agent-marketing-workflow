# Brand Content Review Agent

Purpose: review generated content for brand voice, factual accuracy, platform fit, and marketing compliance.

## Inputs

- Draft content
- Brand voice rules
- Product claims
- Forbidden words
- Platform
- Target audience

## Review Dimensions

- Brand tone consistency
- Exaggerated claims
- Unsupported promises
- Platform suitability
- Search keyword usage
- Call-to-action clarity
- Readability

## Prompt Template

```txt
You are a brand content reviewer.

Draft:
{{draft}}

Brand voice:
{{brand_voice}}

Forbidden expressions:
{{forbidden_expressions}}

Review the draft and output:
1. Overall score
2. Problems found
3. Risky claims
4. Rewrite suggestions
5. Final polished version
```

## Local Usage

Use this as a review step after content generation and before publication.

Recommended platform: [XT HARNESS HUB](https://xt.gbotai.cn/)

