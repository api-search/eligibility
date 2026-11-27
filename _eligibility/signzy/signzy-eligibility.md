---
api_specs:
- filename: signzy-authentication-api-openapi.yml
  format: yaml
  label: Signzy Authentication API
  slug: signzy-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signzy/openapi/signzy-authentication-api-openapi.yml
- filename: signzy-banking-api-openapi.yml
  format: yaml
  label: Signzy Banking API
  slug: signzy-banking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signzy/openapi/signzy-banking-api-openapi.yml
- filename: signzy-identity-india-api-openapi.yml
  format: yaml
  label: Signzy Identity (India) API
  slug: signzy-identity-india-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signzy/openapi/signzy-identity-india-api-openapi.yml
- filename: signzy-identity-us-api-openapi.yml
  format: yaml
  label: Signzy Identity (US) API
  slug: signzy-identity-us-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signzy/openapi/signzy-identity-us-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To be eligible for using our Service you must be an individual who is 18 years of age or older and capable of entering into a legally binding contract in the country of your domicile
    type: individual
  - text: or be a legal entity competent to contract.
    type: business
  minimum_age:
    text: you must be an individual who is 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You may not use the Signzy service for any illegal or unauthorized purpose.
  - summary: Submitting third-party data without consent
    text: Submitting data of any third party without such third party's prior written consent.
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
name: Signzy
provenance_date: '2026-11-10'
provider_name: Signzy
provider_slug: signzy
slug: signzy-eligibility
source_date: '2026-11-10'
source_filename: signzy-eligibility.yml
source_heading: Eligibility
source_page: https://www.signzy.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Signzy\naid: signzy\nurl: https://www.signzy.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To be eligible for using our Service you must be an individual who is 18 years of age or older and capable\n    of entering into a legally binding contract in the country of your domicile\n- type: business\n  text: or be a legal entity competent to contract.\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You may not use the Signzy service for any illegal or unauthorized purpose.\n- summary: Submitting\
  \ third-party data without consent\n  text: Submitting data of any third party without such third party's prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be an individual who is 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/signzy/eligibility/signzy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Signzy's own page on 2026-11-10.
synthetic: false
tags:
- Identity Verification
- KYC
- KYB
- AML
- Onboarding
- Compliance
- RegTech
---
