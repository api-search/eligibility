---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of a company, you confirm that you are authorized to bind that company, and "you" includes the company.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live if that is higher, to use the Service.
    value: '18'
  restricted_uses:
  - summary: Prohibited content
    text: is illegal, or infringes copyright, trademark, privacy, personality or other rights
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
name: Aicut
provenance_date: '2026-11-09'
provider_name: Aicut
provider_slug: aicut-pro
slug: aicut-pro-eligibility
source_date: '2026-11-09'
source_filename: aicut-pro-eligibility.yml
source_heading: Eligibility
source_page: https://www.aicut.pro/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aicut\naid: aicut-pro\nurl: https://www.aicut.pro/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of a company, you confirm that you are authorized to bind that company,\n    and \"you\" includes the company.\nrestricted_uses:\n- summary: Prohibited content\n  text: is illegal, or infringes copyright, trademark, privacy, personality or other rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years\
  \ old, or the age of majority where you live if that is higher, to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/aicut-pro/eligibility/aicut-pro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Aicut's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Video Generation
- Marketing
- Content Creation
- Automation
- Company
---
