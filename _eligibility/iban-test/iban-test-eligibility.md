---
api_specs:
- filename: iban-test-openapi-generated.yml
  format: yaml
  label: ToadTec API
  slug: iban-test-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iban-test/openapi/_ae-authored/iban-test-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Unless stated otherwise, prices for business customers are exclusive of statutory VAT.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only for API tokens
    text: API tokens may only be used for lawful purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Certain functions, especially API usage, require a user account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ToadTec
provenance_date: '2026-11-09'
provider_name: ToadTec
provider_slug: iban-test
slug: iban-test-eligibility
source_date: '2026-11-09'
source_filename: iban-test-eligibility.yml
source_heading: Eligibility
source_page: https://www.iban-test.eu/Terms-and-Conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ToadTec\naid: iban-test\nurl: https://www.iban-test.eu/Terms-and-Conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Unless stated otherwise, prices for business customers are exclusive of statutory VAT.\nrestricted_uses:\n- summary: Lawful purposes only for API tokens\n  text: API tokens may only be used for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Certain functions, especially API usage, require a user account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/iban-test/eligibility/iban-test-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from ToadTec's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Payments
- Validation
---
