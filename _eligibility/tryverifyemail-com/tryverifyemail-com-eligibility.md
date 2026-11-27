---
api_specs:
- filename: tryverifyemail-com-openapi-generated.yml
  format: yaml
  label: tryverifyemail-com API
  slug: tryverifyemail-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tryverifyemail-com/openapi/_ae-authored/tryverifyemail-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for business and professional use.
    type: business
  - text: You must be at least 18 years old (or the age of majority where you live) and able to enter into a binding contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old (or the age of majority where you live)
    value: '18'
  restricted_uses:
  - summary: Unlawful or deceptive use
    text: use the Service for anything unlawful, harmful, deceptive, or that infringes others' rights, see our Abuse Policy
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
name: tryverifyemail-com
provenance_date: '2026-11-10'
provider_name: tryverifyemail-com
provider_slug: tryverifyemail-com
slug: tryverifyemail-com-eligibility
source_date: '2026-11-10'
source_filename: tryverifyemail-com-eligibility.yml
source_heading: Eligibility
source_page: https://tryverifyemail.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tryverifyemail-com\naid: tryverifyemail-com\nurl: https://tryverifyemail.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for business and professional use.\n- type: individual\n  text: You must be at least 18 years old (or the age of majority where you live) and able to enter into a binding\n    contract.\nrestricted_uses:\n- summary: Unlawful or deceptive use\n  text: use the Service for anything unlawful, harmful, deceptive, or that infringes others' rights, see our Abuse\n    Policy\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority where you live)\n"
source_yaml_url: https://artifacts.apis.io/tryverifyemail-com/eligibility/tryverifyemail-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from tryverifyemail-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email Verification
- Data Validation
- Deliverability
- Bulk
---
