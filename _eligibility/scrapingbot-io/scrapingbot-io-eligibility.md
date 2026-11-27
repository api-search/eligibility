---
api_specs:
- filename: scrapingbot-io-openapi-generated.yml
  format: yaml
  label: scrapingbot-io API
  slug: scrapingbot-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrapingbot-io/openapi/_ae-authored/scrapingbot-io-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use it for a company, you agree on its behalf and confirm you are allowed to.
    type: business
  minimum_age:
    text: You must be at least 16, and old enough to enter a contract where you live.
    value: '16'
  restricted_uses:
  - summary: Restricted acceptable use
    text: Track, monitor, profile or harass individuals, build dossiers on people, or make decisions about people’s eligibility for jobs, credit, housing or insurance.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: scrapingbot-io
provenance_date: '2026-11-10'
provider_name: scrapingbot-io
provider_slug: scrapingbot-io
slug: scrapingbot-io-eligibility
source_date: '2026-11-10'
source_filename: scrapingbot-io-eligibility.yml
source_heading: Eligibility
source_page: https://scrapingbot.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: scrapingbot-io\naid: scrapingbot-io\nurl: https://scrapingbot.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use it for a company, you agree on its behalf and confirm you are allowed to.\nrestricted_uses:\n- summary: Restricted acceptable use\n  text: Track, monitor, profile or harass individuals, build dossiers on people, or make decisions about people’s\n    eligibility for jobs, credit, housing or insurance.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n\
  \  text: You must be at least 16, and old enough to enter a contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/scrapingbot-io/eligibility/scrapingbot-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from scrapingbot-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Scraping
- Artificial Intelligence
- Data Extraction
- Automation
---
