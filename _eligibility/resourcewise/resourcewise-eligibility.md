---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any individual or entity who accesses or uses a website, mobile application, Analytical Platform and/or other online service
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful or infringing material
    text: use the Data Services to store or transmit infringing, libelous, or otherwise unlawful or tortious material
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
name: ResourceWise
provenance_date: '2026-11-10'
provider_name: ResourceWise
provider_slug: resourcewise
slug: resourcewise-eligibility
source_date: '2026-11-10'
source_filename: resourcewise-eligibility.yml
source_heading: Eligibility
source_page: https://www.resourcewise.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ResourceWise\naid: resourcewise\nurl: https://www.resourcewise.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: any individual or entity who accesses or uses a website, mobile application, Analytical Platform and/or\n    other online service\nrestricted_uses:\n- summary: No unlawful or infringing material\n  text: use the Data Services to store or transmit infringing, libelous, or otherwise unlawful or tortious material\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/resourcewise/eligibility/resourcewise-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from ResourceWise's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Market Intelligence
- Commodities
- Data & Analytics
- Forest Products
- Pulp And Paper
- Chemicals
- Biofuels
- Pricing Data
- Sustainability
---
