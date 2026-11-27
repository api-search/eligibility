---
api_specs:
- filename: adscrawl-browser-tasks-api-openapi.yml
  format: yaml
  label: AdsCrawl Browser tasks API
  slug: adscrawl-browser-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adscrawl/openapi/adscrawl-browser-tasks-api-openapi.yml
- filename: adscrawl-cloud-browsers-api-openapi.yml
  format: yaml
  label: AdsCrawl Cloud browsers API
  slug: adscrawl-cloud-browsers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adscrawl/openapi/adscrawl-cloud-browsers-api-openapi.yml
- filename: adscrawl-remote-cdp-api-openapi.yml
  format: yaml
  label: AdsCrawl Remote CDP API
  slug: adscrawl-remote-cdp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adscrawl/openapi/adscrawl-remote-cdp-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful, fraudulent or surveillance uses
    text: Do not use the service for unlawful surveillance, fraud, credential theft, spam, harassment, or discrimination.
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
name: AdsCrawl
provenance_date: '2026-11-09'
provider_name: AdsCrawl
provider_slug: adscrawl
slug: adscrawl-eligibility
source_date: '2026-11-09'
source_filename: adscrawl-eligibility.yml
source_heading: Eligibility
source_page: https://www.adscrawl.net/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdsCrawl\naid: adscrawl\nurl: https://www.adscrawl.net/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful, fraudulent or surveillance uses\n  text: Do not use the service for unlawful surveillance, fraud, credential theft, spam, harassment, or discrimination.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adscrawl/eligibility/adscrawl-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from AdsCrawl's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Browser Automation
- WebDataExtraction
- Playwright
- Puppeteer
- Chrome DevTools Protocol
---
