---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. government embargo
  entity_types:
  - text: you are the legal age of majority under applicable law (generally the age of 18 or older) to form a binding contract with Musaffa
    type: individual
  - text: If you establish an Account on behalf of a company, corporation, organization, entity, or brand
    type: business
  minimum_age:
    text: the legal age of majority under applicable law (generally the age of 18 or older)
    value: '18'
  restricted_uses:
  - summary: Revenue-generating or commercial use
    text: otherwise use the Service and/or the Content for any revenue-generating endeavor or commercial enterprise
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
name: Musaffa
provenance_date: '2026-11-10'
provider_name: Musaffa
provider_slug: musaffa
slug: musaffa-eligibility
source_date: '2026-11-10'
source_filename: musaffa-eligibility.yml
source_heading: Eligibility
source_page: https://musaffa.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Musaffa\naid: musaffa\nurl: https://musaffa.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. government embargo\nentity_types:\n- type: individual\n  text: you are the legal age of majority under applicable law (generally the age of 18 or older) to form a binding\n    contract with Musaffa\n- type: business\n  text: If you establish an Account on behalf of a company, corporation, organization, entity, or brand\nrestricted_uses:\n- summary: Revenue-generating or commercial use\n  text: otherwise\
  \ use the Service and/or the Content for any revenue-generating endeavor or commercial enterprise\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the legal age of majority under applicable law (generally the age of 18 or older)\n"
source_yaml_url: https://artifacts.apis.io/musaffa/eligibility/musaffa-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Musaffa's own page on 2026-11-10.
synthetic: false
tags:
- Islamic Finance
- Shariah Compliance
- Halal Investing
- Stock Screening
- Financial Data
- ETFs
- Market Data
- Fintech
- Investing
- Compliance
- Zakat
- Company
---
