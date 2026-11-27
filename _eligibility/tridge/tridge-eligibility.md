---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Site on behalf of an entity, you represent and warrant that you have the authority to bind that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automated scraping or crawling
    text: use manual or automated software, devices, scripts, robots, backdoors or other means or processes to access, "scrape," "crawl" or "spider" any web pages or other services contained in the Site
  - summary: Competing business use of Site Content
    text: copy, reproduce, download, compile or otherwise use any Site Content for the purposes of operating a business that competes with Tridge
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
name: Tridge
provenance_date: '2026-11-10'
provider_name: Tridge
provider_slug: tridge
slug: tridge-eligibility
source_date: '2026-11-10'
source_filename: tridge-eligibility.yml
source_heading: Eligibility
source_page: https://www.tridge.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tridge\naid: tridge\nurl: https://www.tridge.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Site on behalf of an entity, you represent and warrant that you have the authority to bind\n    that entity\nrestricted_uses:\n- summary: Automated scraping or crawling\n  text: use manual or automated software, devices, scripts, robots, backdoors or other means or processes to access,\n    \"scrape,\" \"crawl\" or \"spider\" any web pages or other services contained in the Site\n- summary: Competing business use of Site\
  \ Content\n  text: copy, reproduce, download, compile or otherwise use any Site Content for the purposes of operating a business\n    that competes with Tridge\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tridge/eligibility/tridge-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Tridge's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Agriculture
- Food
- Trade
- Commodities
- Market Data
- Supply Chain
- Sourcing
- Analytics
- Price Data
- Artificial Intelligence
- Market Intelligence
---
