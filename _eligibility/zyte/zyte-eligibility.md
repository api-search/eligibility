---
api_specs:
- filename: zyte-extract-api-openapi.yml
  format: yaml
  label: Zyte Extract API
  slug: zyte-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zyte/openapi/zyte-extract-api-openapi.yml
- filename: zyte-stats-api-openapi.yml
  format: yaml
  label: Zyte Stats API
  slug: zyte-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zyte/openapi/zyte-stats-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - VE
    - RU
    served: []
    text: 'You represent and warrant that you are not from any of the following countries/regions: Cuba, Iran, North Korea, Syria, Venezuela, Russia, and the Crimea region of Ukraine.'
  entity_types:
  - text: If you are accessing or using the Services on behalf of a company, organization, or other entity, you are agreeing to these Terms on its behalf
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Publicly accessible websites only
    text: The Services shall be used solely to scrape data from publicly accessible websites.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
- VE
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zyte
provenance_date: '2026-11-10'
provider_name: Zyte
provider_slug: zyte
slug: zyte-eligibility
source_date: '2026-11-10'
source_filename: zyte-eligibility.yml
source_heading: Eligibility
source_page: https://www.zyte.com/terms-policies/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zyte\naid: zyte\nurl: https://www.zyte.com/terms-policies/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - VE\n  - RU\n  text: 'You represent and warrant that you are not from any of the following countries/regions: Cuba, Iran, North\n    Korea, Syria, Venezuela, Russia, and the Crimea region of Ukraine.'\nentity_types:\n- type: business\n  text: If you are accessing or using the Services on behalf of a company, organization, or other entity, you are\n    agreeing to these Terms on its behalf\nrestricted_uses:\n- summary: Publicly accessible\
  \ websites only\n  text: The Services shall be used solely to scrape data from publicly accessible websites.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zyte/eligibility/zyte-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Zyte's own page on 2026-11-10.
synthetic: false
tags:
- Crawling
- Data Extraction
- Web Scraping
- Proxies
- Browser Automation
- Anti-Ban
- SERP
- Agent Skills
- Developer Tools
---
