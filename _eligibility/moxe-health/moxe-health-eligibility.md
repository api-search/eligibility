---
api_specs:
- filename: moxe-health-claims-api-openapi.yml
  format: yaml
  label: Moxe Health Claims API
  slug: moxe-health-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moxe-health/openapi/moxe-health-claims-api-openapi.yml
- filename: moxe-health-patient-api-openapi.yml
  format: yaml
  label: Moxe Health Patient API
  slug: moxe-health-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moxe-health/openapi/moxe-health-patient-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unauthorized third-party access
    text: Client shall not permit unauthorized third parties to access or use The Moxe Technology.
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
name: Moxe Health
provenance_date: '2026-11-10'
provider_name: Moxe Health
provider_slug: moxe-health
slug: moxe-health-eligibility
source_date: '2026-11-10'
source_filename: moxe-health-eligibility.yml
source_heading: Eligibility
source_page: https://moxehealth.com/moxe-technology-governing-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moxe Health\naid: moxe-health\nurl: https://moxehealth.com/moxe-technology-governing-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized third-party access\n  text: Client shall not permit unauthorized third parties to access or use The Moxe Technology.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/moxe-health/eligibility/moxe-health-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Moxe Health's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- United States
- Interoperability
- Clinical Data
- Payers
- Providers
- Electronic Health Records
- Health Data Exchange
- Claims
- Risk Adjustment
---
