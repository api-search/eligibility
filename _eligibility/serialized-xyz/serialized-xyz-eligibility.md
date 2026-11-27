---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The service is offered to businesses and professionals.
    type: business
  minimum_age:
    text: you confirm that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: use the service for anything unlawful, including sanctions evasion, fraud or market manipulation
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
name: Serialized
provenance_date: '2026-11-10'
provider_name: Serialized
provider_slug: serialized-xyz
slug: serialized-xyz-eligibility
source_date: '2026-11-10'
source_filename: serialized-xyz-eligibility.yml
source_heading: Eligibility
source_page: https://serialized.xyz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Serialized\naid: serialized-xyz\nurl: https://serialized.xyz/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The service is offered to businesses and professionals.\nrestricted_uses:\n- summary: Unlawful use\n  text: use the service for anything unlawful, including sanctions evasion, fraud or market manipulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you confirm that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/serialized-xyz/eligibility/serialized-xyz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Serialized's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Onchain
- Market Data
- TokenSecurity
- Data
---
