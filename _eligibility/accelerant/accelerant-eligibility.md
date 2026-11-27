---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The portions of the Platform and any Content and Offerings generally available to all Users are intended for use by individuals 13 years of age and older.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No political campaigning via Platform
    text: use the Platform for political campaigning
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All Accounts are issued at the sole discretion of Accelerant.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Accelerant
provenance_date: '2026-11-09'
provider_name: Accelerant
provider_slug: accelerant
slug: accelerant-eligibility
source_date: '2026-11-09'
source_filename: accelerant-eligibility.yml
source_heading: Eligibility
source_page: https://accelerant.ai/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Accelerant\naid: accelerant\nurl: https://accelerant.ai/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The portions of the Platform and any Content and Offerings generally available to all Users are intended\n    for use by individuals 13 years of age and older.\nrestricted_uses:\n- summary: No political campaigning via Platform\n  text: use the Platform for political campaigning\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All Accounts are issued at the sole discretion of Accelerant.\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/accelerant/eligibility/accelerant-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Accelerant's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Insurtech
- Specialty Insurance
- Underwriting
- Risk Management
- Reinsurance
- Marketplace
- Risk Scoring
- Financial Services
- Artificial Intelligence
---
