---
api_specs:
- filename: kodjin-openapi-generated.yml
  format: yaml
  label: Kodjin API
  slug: kodjin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kodjin/openapi/_ae-authored/kodjin-openapi-generated.yml
- filename: kodjin-auth-api-openapi.yml
  format: yaml
  label: Kodjin Auth API
  slug: kodjin-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kodjin/openapi/kodjin-auth-api-openapi.yml
- filename: kodjin-fhir-api-openapi.yml
  format: yaml
  label: Kodjin Fhir API
  slug: kodjin-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kodjin/openapi/kodjin-fhir-api-openapi.yml
- filename: kodjin-patient-api-openapi.yml
  format: yaml
  label: Kodjin Patient API
  slug: kodjin-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kodjin/openapi/kodjin-patient-api-openapi.yml
- filename: kodjin-terminology-api-openapi.yml
  format: yaml
  label: Kodjin Terminology API
  slug: kodjin-terminology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kodjin/openapi/kodjin-terminology-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: These Terms of Use constitute a legally binding agreement made between you personally (“you”) and Edenlab LLC
    type: individual
  minimum_age:
    text: By creating an account at the Site you confirm that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: You are granted a limited license to access and use the Software solely for your personal, non-commercial use worldwide
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Site. By creating an account at the Site you confirm that you are at least 18 years old.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kodjin
provenance_date: '2026-11-09'
provider_name: Kodjin
provider_slug: kodjin
slug: kodjin-eligibility
source_date: '2026-11-09'
source_filename: kodjin-eligibility.yml
source_heading: Eligibility
source_page: https://kodjin.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kodjin\naid: kodjin\nurl: https://kodjin.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: These Terms of Use constitute a legally binding agreement made between you personally (“you”) and Edenlab\n    LLC\nrestricted_uses:\n- summary: Non-commercial use only\n  text: You are granted a limited license to access and use the Software\
  \ solely for your personal, non-commercial\n    use worldwide\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with the Site. By creating an account at the Site you confirm that you are\n    at least 18 years old.\nminimum_age:\n  value: '18'\n  text: By creating an account at the Site you confirm that you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/kodjin/eligibility/kodjin-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Kodjin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Low-Code
- Platform
- Automation
- Integration
---
