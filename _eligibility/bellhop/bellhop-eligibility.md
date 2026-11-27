---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you reside in the United States or any of its territories
  entity_types:
  - text: your participation in using the Bellhop Platforms and/or requesting Services is for your own personal use
    type: individual
  minimum_age:
    text: In order to place an order for Services, you must be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: you will only use the Bellhop Platforms and/or request Services for lawful purposes
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: you will provide Bellhop and/or the Third Party Providers with whatever proof of identity they may reasonably request
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bellhop
provenance_date: '2026-11-09'
provider_name: Bellhop
provider_slug: bellhop
slug: bellhop-eligibility
source_date: '2026-11-09'
source_filename: bellhop-eligibility.yml
source_heading: Eligibility
source_page: https://www.getbellhops.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bellhop\naid: bellhop\nurl: https://www.getbellhops.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you reside in the United States or any of its territories\nentity_types:\n- type: individual\n  text: your participation in using the Bellhop Platforms and/or requesting Services is for your own personal use\nrestricted_uses:\n- summary: Lawful use only\n  text: you will only use the Bellhop Platforms and/or request Services for lawful purposes\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: you will provide\
  \ Bellhop and/or the Third Party Providers with whatever proof of identity they may reasonably\n    request\nminimum_age:\n  value: '18'\n  text: In order to place an order for Services, you must be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/bellhop/eligibility/bellhop-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Bellhop's own page on 2026-11-09.
synthetic: false
tags:
- Moving
- On-Demand
- Logistics
- Transportation
- Customer Experience
- Company
---
