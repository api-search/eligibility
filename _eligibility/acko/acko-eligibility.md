---
api_specs:
- filename: acko-apis-api-openapi.yml
  format: yaml
  label: Acko APIs API
  slug: acko-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acko/openapi/acko-apis-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The User of this Platform unequivocally declares and agrees that the User is a natural / legal person who has attained the age of at least 18 years and is legally allowed to enter a contract in India.
    type: individual
  minimum_age:
    text: has attained the age of at least 18 years
    value: '18'
  restricted_uses:
  - summary: Fraudulent or illegal activity
    text: You shall not engage in fraudulent, abusive or illegal activity
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Prior to making this transfer, however, the Insurance Provider will ensure compliance with all applicable laws including KYC checks and bank account verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Acko
provenance_date: '2026-11-09'
provider_name: Acko
provider_slug: acko
slug: acko-eligibility
source_date: '2026-11-09'
source_filename: acko-eligibility.yml
source_heading: Eligibility
source_page: https://www.acko.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Acko\naid: acko\nurl: https://www.acko.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The User of this Platform unequivocally declares and agrees that the User is a natural / legal person who\n    has attained the age of at least 18 years and is legally allowed to enter a contract in India.\nrestricted_uses:\n- summary: Fraudulent or illegal activity\n  text: You shall not engage in fraudulent, abusive or illegal activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Prior to\
  \ making this transfer, however, the Insurance Provider will ensure compliance with all applicable\n    laws including KYC checks and bank account verification.\nminimum_age:\n  value: '18'\n  text: has attained the age of at least 18 years\n"
source_yaml_url: https://artifacts.apis.io/acko/eligibility/acko-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Acko's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Insurance
- Insurtech
- Financial Services
- Digital Insurance
- India
- Embedded Insurance
---
