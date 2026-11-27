---
api_specs:
- filename: paymate-businesses-api-openapi.yml
  format: yaml
  label: PayMate Businesses API
  slug: paymate-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymate/openapi/paymate-businesses-api-openapi.yml
- filename: paymate-cards-api-openapi.yml
  format: yaml
  label: PayMate Cards API
  slug: paymate-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymate/openapi/paymate-cards-api-openapi.yml
- filename: paymate-collections-api-openapi.yml
  format: yaml
  label: PayMate Collections API
  slug: paymate-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymate/openapi/paymate-collections-api-openapi.yml
- filename: paymate-contacts-api-openapi.yml
  format: yaml
  label: PayMate Contacts API
  slug: paymate-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymate/openapi/paymate-contacts-api-openapi.yml
- filename: paymate-payments-api-openapi.yml
  format: yaml
  label: PayMate Payments API
  slug: paymate-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymate/openapi/paymate-payments-api-openapi.yml
- filename: paymate-reference-api-openapi.yml
  format: yaml
  label: PayMate Reference API
  slug: paymate-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymate/openapi/paymate-reference-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: an entity eligible and registered to carry out business or operate in India; or (b) an individual who is at least 18 years old and a resident of India
  entity_types:
  - text: an entity eligible and registered to carry out business or operate in India
    type: business
  - text: an individual who is at least 18 years old and a resident of India
    type: individual
  minimum_age:
    text: an individual who is at least 18 years old and a resident of India
    value: '18'
  restricted_uses:
  - summary: Self-financing transactions
    text: User/Payer/Payee hereby expressly acknowledges, agrees and undertakes not to enter into/ facilitate /carry on or attempt to enter into/ facilitate/ carry on any self-financing transaction
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
name: PayMate
provenance_date: '2026-11-10'
provider_name: PayMate
provider_slug: paymate
slug: paymate-eligibility
source_date: '2026-11-10'
source_filename: paymate-eligibility.yml
source_heading: Eligibility
source_page: https://paymate.in/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PayMate\naid: paymate\nurl: https://paymate.in/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: an entity eligible and registered to carry out business or operate in India; or (b) an individual who is\n    at least 18 years old and a resident of India\nentity_types:\n- type: business\n  text: an entity eligible and registered to carry out business or operate in India\n- type: individual\n  text: an individual who is at least 18 years old and a resident of India\nrestricted_uses:\n- summary: Self-financing transactions\n  text: User/Payer/Payee hereby\
  \ expressly acknowledges, agrees and undertakes not to enter into/ facilitate /carry\n    on or attempt to enter into/ facilitate/ carry on any self-financing transaction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: an individual who is at least 18 years old and a resident of India\n"
source_yaml_url: https://artifacts.apis.io/paymate/eligibility/paymate-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from PayMate's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- B2B Payments
- Accounts Payable
- Accounts Receivable
- Supply Chain Finance
- Invoice Discounting
- Working Capital
- Commercial Cards
- Financial Services
- India
- Fintech
- Company
---
