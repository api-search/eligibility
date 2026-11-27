---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are offered and provided solely for commercial and business purposes.
    type: business
  - text: To the extent you are a sole proprietor or individual business owner, you acknowledge that your use of the Services is in a commercial capacity.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal or household use
    text: you represent and warrant that you are using the Services for business purposes and not for personal, family, or household purposes.
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
name: Jaris
provenance_date: '2026-11-09'
provider_name: Jaris
provider_slug: jaris
slug: jaris-eligibility
source_date: '2026-11-09'
source_filename: jaris-eligibility.yml
source_heading: Eligibility
source_page: https://www.jaris.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jaris\naid: jaris\nurl: https://www.jaris.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are offered and provided solely for commercial and business purposes.\n- type: individual\n  text: To the extent you are a sole proprietor or individual business owner, you acknowledge that your use of the\n    Services is in a commercial capacity.\nrestricted_uses:\n- summary: No personal or household use\n  text: you represent and warrant that you are using the Services for business purposes and\
  \ not for personal, family,\n    or household purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jaris/eligibility/jaris-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Jaris's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Embedded Finance
- Fintech
- Payments
- Lending
- Banking as a Service
- Instant Payouts
- Merchant Onboarding
- KYB
- Settlement
---
