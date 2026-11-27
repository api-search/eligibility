---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You will use the Products only from within the United States of America.
  entity_types:
  - text: These Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: you will not use the Products for any illegal or unauthorized purpose
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
name: Portex
provenance_date: '2026-11-10'
provider_name: Portex
provider_slug: portex
slug: portex-eligibility
source_date: '2026-11-10'
source_filename: portex-eligibility.yml
source_heading: Eligibility
source_page: https://www.portexpro.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Portex\naid: portex\nurl: https://www.portexpro.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You will use the Products only from within the United States of America.\nentity_types:\n- type: business\n  text: These Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: you will not use the Products for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/portex/eligibility/portex-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Portex's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Freight
- Supply Chain
- Freight Procurement
- Transportation Management
- Logistics Technology
---
