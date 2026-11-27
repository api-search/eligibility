---
api_specs:
- filename: telda-openapi-generated.yml
  format: yaml
  label: Telda API
  slug: telda-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telda/openapi/_ae-authored/telda-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - EG
    text: You'll need to be an Egyptian resident and at least 15 years old.
  entity_types:
  - text: Issuance of cards is limited to Egyptian natural persons “Egyptian individuals only” from the age of 15 years.
    type: individual
  - text: If you are using the Service on behalf of a business or entity, you acknowledge and agree that you have authority to bind such business or entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or abusive payment use
    text: You will use Telda legally and in accordance with debit and credit card network rules.
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
name: Telda
provenance_date: '2026-11-10'
provider_name: Telda
provider_slug: telda
slug: telda-eligibility
source_date: '2026-11-10'
source_filename: telda-eligibility.yml
source_heading: Eligibility
source_page: https://telda.app/legal/terms/index.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Telda\naid: telda\nurl: https://telda.app/legal/terms/index.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - EG\n  excluded: []\n  text: You'll need to be an Egyptian resident and at least 15 years old.\nentity_types:\n- type: individual\n  text: Issuance of cards is limited to Egyptian natural persons “Egyptian individuals only” from the age of 15\n    years.\n- type: business\n  text: If you are using the Service on behalf of a business or entity, you acknowledge and agree that you have\n    authority to bind such business or entity\nrestricted_uses:\n- summary: Illegal or abusive payment use\n \
  \ text: You will use Telda legally and in accordance with debit and credit card network rules.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/telda/eligibility/telda-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Telda's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Mobile App
- Digital Banking
---
