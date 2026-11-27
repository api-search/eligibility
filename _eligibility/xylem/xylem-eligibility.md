---
api_specs:
- filename: xylem-docview-api-openapi.yml
  format: yaml
  label: Xylem Doc View API
  slug: xylem-docview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xylem/openapi/xylem-docview-api-openapi.yml
- filename: xylem-infor-api-openapi.yml
  format: yaml
  label: Xylem Infor API
  slug: xylem-infor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xylem/openapi/xylem-infor-api-openapi.yml
- filename: xylem-mes-api-openapi.yml
  format: yaml
  label: Xylem MES API
  slug: xylem-mes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xylem/openapi/xylem-mes-api-openapi.yml
- filename: xylem-mes-v2-api-openapi.yml
  format: yaml
  label: Xylem MES V2 API
  slug: xylem-mes-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xylem/openapi/xylem-mes-v2-api-openapi.yml
- filename: xylem-nameplate-api-openapi.yml
  format: yaml
  label: Xylem Name Plate API
  slug: xylem-nameplate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xylem/openapi/xylem-nameplate-api-openapi.yml
- filename: xylem-serialcard-api-openapi.yml
  format: yaml
  label: Xylem Serial Card API
  slug: xylem-serialcard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xylem/openapi/xylem-serialcard-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to the Materials from territories where the Materials are illegal is prohibited.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Password-protected areas limited to registered users
    text: only registered users may access said pages
  - summary: Non-commercial use only
    text: any use of the Material is for informational and non-commercial or personal use only
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Xylem reserves the right to deny registration to any user.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Xylem
provenance_date: '2026-11-10'
provider_name: Xylem
provider_slug: xylem
slug: xylem-eligibility
source_date: '2026-11-10'
source_filename: xylem-eligibility.yml
source_heading: Eligibility
source_page: https://www.xylem.com/en-us/support/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Xylem\naid: xylem\nurl: https://www.xylem.com/en-us/support/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to the Materials from territories where the Materials are illegal is prohibited.\nentity_types: []\nrestricted_uses:\n- summary: Password-protected areas limited to registered users\n  text: only registered users may access said pages\n- summary: Non-commercial use only\n  text: any use of the Material is for informational and non-commercial or personal use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Xylem reserves\
  \ the right to deny registration to any user.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/xylem/eligibility/xylem-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Xylem's own page on 2026-11-10.
synthetic: false
tags:
- Fortune 1000
- Water
- Water Technology
- Utilities
- Smart Metering
- Industrial IoT
- Water Quality
- Wastewater
- Manufacturing
---
