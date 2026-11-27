---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: where applicable, the organisation whose workspace you use
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Bulk scraping
    text: Bulk scraping is not supported or allowed
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
name: levirge-com
provenance_date: '2026-11-09'
provider_name: levirge-com
provider_slug: levirge-com
slug: levirge-com-eligibility
source_date: '2026-11-09'
source_filename: levirge-com-eligibility.yml
source_heading: Eligibility
source_page: https://levirge.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: levirge-com\naid: levirge-com\nurl: https://levirge.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: where applicable, the organisation whose workspace you use\nrestricted_uses:\n- summary: Bulk scraping\n  text: Bulk scraping is not supported or allowed\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/levirge-com/eligibility/levirge-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from levirge-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Search
- Knowledge
- MCP
- Platform
---
