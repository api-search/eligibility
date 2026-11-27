---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: BY USING OR ACCESSING THE SERVICES, YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OF AGE
    value: '18'
  restricted_uses:
  - summary: No sensitive information submissions
    text: You agree to not use our Service to send us sensitive information where unauthorized disclosure could cause material, severe, or catastrophic harm or impact to the InnerTrends, any data subjects or relying parties.
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
name: Innertrends
provenance_date: '2026-11-09'
provider_name: Innertrends
provider_slug: innertrends
slug: innertrends-eligibility
source_date: '2026-11-09'
source_filename: innertrends-eligibility.yml
source_heading: Eligibility
source_page: https://www.innertrends.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Innertrends\naid: innertrends\nurl: https://www.innertrends.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No sensitive information submissions\n  text: You agree to not use our Service to send us sensitive information where unauthorized disclosure could cause\n    material, severe, or catastrophic harm or impact to the InnerTrends, any data subjects or relying parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: BY USING OR ACCESSING THE SERVICES,\
  \ YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/innertrends/eligibility/innertrends-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Innertrends's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Product Analytics
- Marketing
- Growth
- Data
- Software-as-a-Service
- Consulting
- Attribution
---
