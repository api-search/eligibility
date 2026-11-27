---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you access and/or use the Service on behalf of a legal entity, then you represent that you have authority to bind that legal entity to this Agreement and that the legal entity accepts this Agreement.
    type: business
  minimum_age:
    text: You may not use the Service if you are under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Counterfeit sales
    text: infringe anyone’s intellectual property, such as by posting counterfeit products for sale through the Service
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
name: Poshmark
provenance_date: '2026-11-10'
provider_name: Poshmark
provider_slug: poshmark
slug: poshmark-eligibility
source_date: '2026-11-10'
source_filename: poshmark-eligibility.yml
source_heading: Eligibility
source_page: https://poshmark.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Poshmark\naid: poshmark\nurl: https://poshmark.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you access and/or use the Service on behalf of a legal entity, then you represent that you have authority\n    to bind that legal entity to this Agreement and that the legal entity accepts this Agreement.\nrestricted_uses:\n- summary: Counterfeit sales\n  text: infringe anyone’s intellectual property, such as by posting counterfeit products for sale through the Service\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You may not use the Service if you are under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/poshmark/eligibility/poshmark-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Poshmark's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Resale
- Fashion
- E-Commerce
- Social Commerce
- Secondhand
- Retail
---
