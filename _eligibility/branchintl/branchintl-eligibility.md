---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - KE
    text: The Services offered by the Bank can only be utilized by persons over the age of 18 and are legally resident in Kenya.
  entity_types:
  - text: The Services offered by the Bank can only be utilized by persons over the age of 18 and are legally resident in Kenya.
    type: individual
  - text: We only supply the App for domestic and private use.
    type: business
  minimum_age:
    text: The Services offered by the Bank can only be utilized by persons over the age of 18
    value: '18'
  restricted_uses:
  - summary: Domestic and private use only
    text: We only supply the App for domestic and private use.
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
name: Branchintl
provenance_date: '2026-11-09'
provider_name: Branchintl
provider_slug: branchintl
slug: branchintl-eligibility
source_date: '2026-11-09'
source_filename: branchintl-eligibility.yml
source_heading: Eligibility
source_page: https://branch.co/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Branchintl\naid: branchintl\nurl: https://branch.co/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - KE\n  excluded: []\n  text: The Services offered by the Bank can only be utilized by persons over the age of 18 and are legally resident\n    in Kenya.\nentity_types:\n- type: individual\n  text: The Services offered by the Bank can only be utilized by persons over the age of 18 and are legally resident\n    in Kenya.\n- type: business\n  text: We only supply the App for domestic and private use.\nrestricted_uses:\n- summary: Domestic and private use only\n  text: We\
  \ only supply the App for domestic and private use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services offered by the Bank can only be utilized by persons over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/branchintl/eligibility/branchintl-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Branchintl's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Mobile
- Credit
- Emerging Markets
- Africa
- India
---
