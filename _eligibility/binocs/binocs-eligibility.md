---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are accessing the Platform on behalf of Your employer or another entity, You represent that you are duly authorized to bind such entity to these Terms and Conditions.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: you warrant that You will not use the Service for any purpose that is unlawful or prohibited by these Terms and Conditions.
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
name: Binocs
provenance_date: '2026-11-09'
provider_name: Binocs
provider_slug: binocs
slug: binocs-eligibility
source_date: '2026-11-09'
source_filename: binocs-eligibility.yml
source_heading: Eligibility
source_page: https://binocs.co/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Binocs\naid: binocs\nurl: https://binocs.co/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are accessing the Platform on behalf of Your employer or another entity, You represent that you are\n    duly authorized to bind such entity to these Terms and Conditions.\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: you warrant that You will not use the Service for any purpose that is unlawful or prohibited by these Terms\n    and Conditions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/binocs/eligibility/binocs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Binocs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Due Diligence
- Private Equity
- Artificial Intelligence
- Financial Services
- Advisory
---
