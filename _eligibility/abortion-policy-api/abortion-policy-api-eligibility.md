---
api_specs:
- filename: abortion-policy-api-gestational-limits-api-openapi.yml
  format: yaml
  label: Abortion Policy API Gestational Limits API
  slug: abortion-policy-api-gestational-limits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abortion-policy-api/openapi/abortion-policy-api-gestational-limits-api-openapi.yml
- filename: abortion-policy-api-insurance-coverage-api-openapi.yml
  format: yaml
  label: Abortion Policy API Insurance Coverage API
  slug: abortion-policy-api-insurance-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abortion-policy-api/openapi/abortion-policy-api-insurance-coverage-api-openapi.yml
- filename: abortion-policy-api-minors-api-openapi.yml
  format: yaml
  label: Abortion Policy API Minors API
  slug: abortion-policy-api-minors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abortion-policy-api/openapi/abortion-policy-api-minors-api-openapi.yml
- filename: abortion-policy-api-waiting-periods-api-openapi.yml
  format: yaml
  label: Abortion Policy API Waiting Periods API
  slug: abortion-policy-api-waiting-periods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abortion-policy-api/openapi/abortion-policy-api-waiting-periods-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you access or use the Abortion Policy API solely in your individual capacity and for your own, personal use
    type: individual
  - text: If you access or use the Abortion Policy API on behalf of, or within your capacity as, a representative, agent, or employee of any entity
    type: business
  minimum_age:
    text: ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH NEO (PATIENT FORWARD)
    value: legal age
  restricted_uses:
  - summary: No excessive or abusive usage
    text: exceeds reasonable request volume, constitutes excessive or abusive usage
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The term of this Agreement commences when Patient Forward approves your access to the Abortion Policy API
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Abortion Policy API
provenance_date: '2026-11-09'
provider_name: Abortion Policy API
provider_slug: abortion-policy-api
slug: abortion-policy-api-eligibility
source_date: '2026-11-09'
source_filename: abortion-policy-api-eligibility.yml
source_heading: Eligibility
source_page: https://www.abortionpolicyapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Abortion Policy API\naid: abortion-policy-api\nurl: https://www.abortionpolicyapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you access or use the Abortion Policy API solely in your individual capacity and for your own, personal\n    use\n- type: business\n  text: If you access or use the Abortion Policy API on behalf of, or within your capacity as, a representative,\n    agent, or employee of any entity\nrestricted_uses:\n- summary: No excessive or abusive usage\n  text: exceeds reasonable request volume, constitutes\
  \ excessive or abusive usage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The term of this Agreement commences when Patient Forward approves your access to the Abortion Policy API\nminimum_age:\n  value: legal age\n  text: ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH NEO (PATIENT FORWARD)\n"
source_yaml_url: https://artifacts.apis.io/abortion-policy-api/eligibility/abortion-policy-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Abortion Policy API's own page on 2026-11-09.
synthetic: false
tags:
- Abortion
- Policies
- Healthcare
- Government
---
