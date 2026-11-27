---
api_specs:
- filename: citizenleap-com-openapi-generated.yml
  format: yaml
  label: Civica API
  slug: citizenleap-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citizenleap-com/openapi/_ae-authored/citizenleap-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to create an account.
    value: '18'
  restricted_uses:
  - summary: Cheating or misrepresentation on official tests
    text: or use it to cheat on, or misrepresent yourself in, any official test or application
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
name: Civica
provenance_date: '2026-11-09'
provider_name: Civica
provider_slug: citizenleap-com
slug: citizenleap-com-eligibility
source_date: '2026-11-09'
source_filename: citizenleap-com-eligibility.yml
source_heading: Eligibility
source_page: https://citizenleap.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Civica\naid: citizenleap-com\nurl: https://citizenleap.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Cheating or misrepresentation on official tests\n  text: or use it to cheat on, or misrepresent yourself in, any official test or application\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/citizenleap-com/eligibility/citizenleap-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Civica's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Citizenship
- Test Prep
- Software-as-a-Service
- Civica
---
