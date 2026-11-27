---
api_specs:
- filename: scrapingant-scraping-api-openapi.yml
  format: yaml
  label: ScrapingAnt Scraping API
  slug: scrapingant-scraping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrapingant/openapi/scrapingant-scraping-api-openapi.yml
- filename: scrapingant-usage-api-openapi.yml
  format: yaml
  label: ScrapingAnt Usage API
  slug: scrapingant-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrapingant/openapi/scrapingant-usage-api-openapi.yml
- filename: scrapingant-general-api-openapi.yml
  format: yaml
  label: ScrapingAnt General API
  slug: scrapingant-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrapingant/openapi/scrapingant-general-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To be eligible to use the Services, you must be at least 18 years old or have your parent’s permission.
    type: individual
  - text: If you register access to and/or use of the Services on behalf of a company or other entity, you represent and warrant that you have legal capacity and authority to accept these Terms
    type: business
  minimum_age:
    text: you must be at least 18 years old or have your parent’s permission.
    value: '18'
  restricted_uses:
  - summary: Illegal or unlawful use
    text: You shall not engage in any fraudulent business practices or any other activity that is illegal under applicable laws.
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
name: ScrapingAnt
provenance_date: '2026-11-10'
provider_name: ScrapingAnt
provider_slug: scrapingant
slug: scrapingant-eligibility
source_date: '2026-11-10'
source_filename: scrapingant-eligibility.yml
source_heading: Eligibility
source_page: https://scrapingant.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ScrapingAnt\naid: scrapingant\nurl: https://scrapingant.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To be eligible to use the Services, you must be at least 18 years old or have your parent’s permission.\n- type: business\n  text: If you register access to and/or use of the Services on behalf of a company or other entity, you represent\n    and warrant that you have legal capacity and authority to accept these Terms\nrestricted_uses:\n- summary: Illegal or unlawful use\n  text: You shall not engage in any\
  \ fraudulent business practices or any other activity that is illegal under applicable\n    laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old or have your parent’s permission.\n"
source_yaml_url: https://artifacts.apis.io/scrapingant/eligibility/scrapingant-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ScrapingAnt's own page on 2026-11-10.
synthetic: false
tags:
- Data Extraction
- Proxies
- Web Scraping
- Browser Automation
- AI Agents
- MCP
- LLM
- Data Collection
- Web Data
---
