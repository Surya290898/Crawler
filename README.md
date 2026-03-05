# Crawler (Streamlit)

A scope-bound, async crawler for authorized security assessments and discovery.  
**Does not bypass authentication or protections.** Supports authenticated crawling with provided credentials/cookies.

## Features
- Async crawl with concurrency & rate limits
- Scope control: max depth, max pages, allowed hosts
- Respects robots.txt (toggle)
- Sitemap discovery and seeding
- Auth: Basic, Cookie header, or form-based (with field names)
- Findings: status, title, headers, link counts, forms, basic security header checks
- Export CSV/JSON

## Quick Start
1. Clone repo and install deps:
   ```bash
   pip install -r requirements.txt
