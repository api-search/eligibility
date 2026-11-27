---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: PM Company means a legal entity (whether an individual sole trader, a partnership or a body corporate) that is the owner or operator of a real estate business.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Ailo Platform.
    value: '18'
  restricted_uses:
  - summary: Lawful, non-abusive use only
    text: To use the Ailo Platform in a manner that complies with all applicable Laws and is courteous to other users at all times
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
name: Ailo
provenance_date: '2026-11-09'
provider_name: Ailo
provider_slug: ailo
slug: ailo-eligibility
source_date: '2026-11-09'
source_filename: ailo-eligibility.yml
source_heading: Eligibility
source_page: https://ailo.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ailo\naid: ailo\nurl: https://ailo.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: PM Company means a legal entity (whether an individual sole trader, a partnership or a body corporate) that\n    is the owner or operator of a real estate business.\nrestricted_uses:\n- summary: Lawful, non-abusive use only\n  text: To use the Ailo Platform in a manner that complies with all applicable Laws and is courteous to other users\n    at all times\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18 years of age to use the Ailo Platform.\n"
source_yaml_url: https://artifacts.apis.io/ailo/eligibility/ailo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ailo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Property Management
- Real Estate
- PropTech
- Rent Payments
- Payments
- Australia
---
