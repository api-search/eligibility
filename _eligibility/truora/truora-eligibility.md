---
api_specs:
- filename: truora-account-api-openapi.yml
  format: yaml
  label: Truora Account API
  slug: truora-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truora/openapi/truora-account-api-openapi.yml
- filename: truora-checks-api-openapi.yml
  format: yaml
  label: Truora Checks API
  slug: truora-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truora/openapi/truora-checks-api-openapi.yml
- filename: truora-continuous-monitoring-api-openapi.yml
  format: yaml
  label: Truora Continuous Monitoring API
  slug: truora-continuous-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truora/openapi/truora-continuous-monitoring-api-openapi.yml
- filename: truora-digital-identity-api-openapi.yml
  format: yaml
  label: Truora Digital Identity API
  slug: truora-digital-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truora/openapi/truora-digital-identity-api-openapi.yml
- filename: truora-validators-api-openapi.yml
  format: yaml
  label: Truora Validators API
  slug: truora-validators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truora/openapi/truora-validators-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Truora provides its Services exclusively to businesses (B2B) by entering into a master services agreement with each client
    type: business
  - text: In cases where the User is an individual, they must have the legal age of majority required under applicable law to use the Platform.
    type: individual
  minimum_age:
    text: they must have the legal age of majority required under applicable law to use the Platform.
    value: age of majority
  restricted_uses:
  - summary: Illegal activity
    text: Use the Services for any illegal activity or products, both nationally and internationally;
  - summary: Impersonation of data subjects
    text: Use the Platform for the purpose of impersonating the Data Subject.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Truora reserves the right to reject any registration request or to cancel a previously accepted registration, without being obliged to communicate or explain the reasons for its decision
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Truora
provenance_date: '2026-11-10'
provider_name: Truora
provider_slug: truora
slug: truora-eligibility
source_date: '2026-11-10'
source_filename: truora-eligibility.yml
source_heading: Eligibility
source_page: https://www.truora.com/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Truora\naid: truora\nurl: https://www.truora.com/en/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Truora provides its Services exclusively to businesses (B2B) by entering into a master services agreement\n    with each client\n- type: individual\n  text: In cases where the User is an individual, they must have the legal age of majority required under applicable\n    law to use the Platform.\nrestricted_uses:\n- summary: Illegal activity\n  text: Use the Services for any illegal activity or products, both nationally\
  \ and internationally;\n- summary: Impersonation of data subjects\n  text: Use the Platform for the purpose of impersonating the Data Subject.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Truora reserves the right to reject any registration request or to cancel a previously accepted registration,\n    without being obliged to communicate or explain the reasons for its decision\nminimum_age:\n  value: age of majority\n  text: they must have the legal age of majority required under applicable law to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/truora/eligibility/truora-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Truora's own page on 2026-11-10.
synthetic: false
tags:
- Identity Verification
- KYC
- Background Checks
- Fraud Prevention
- Latin America
- WhatsApp
---
