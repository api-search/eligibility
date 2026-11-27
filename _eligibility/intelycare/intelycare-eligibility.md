---
api_specs:
- filename: intelycare-check-in-check-out-api-openapi.yml
  format: yaml
  label: IntelyCare Check In / Check Out API
  slug: intelycare-check-in-check-out-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelycare/openapi/intelycare-check-in-check-out-api-openapi.yml
- filename: intelycare-shift-api-openapi.yml
  format: yaml
  label: IntelyCare Shift API
  slug: intelycare-shift-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelycare/openapi/intelycare-shift-api-openapi.yml
- filename: intelycare-webhook-events-api-openapi.yml
  format: yaml
  label: IntelyCare Webhook Events API
  slug: intelycare-webhook-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelycare/openapi/intelycare-webhook-events-api-openapi.yml
- filename: intelycare-time-card-api-openapi.yml
  format: yaml
  label: IntelyCare Time Card API
  slug: intelycare-time-card-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelycare/openapi/intelycare-time-card-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to use the Sites.
    value: '18'
  restricted_uses:
  - summary: Communication services conduct
    text: You agree to use the Communication Services only to post, send and receive messages and material that are proper and, when applicable, related to the particular Communication Service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If any of the Services requires you to open an account, you must complete the registration process by providing us with current, complete and accurate information as prompted by the applicable registration form.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: IntelyCare
provenance_date: '2026-11-09'
provider_name: IntelyCare
provider_slug: intelycare
slug: intelycare-eligibility
source_date: '2026-11-09'
source_filename: intelycare-eligibility.yml
source_heading: Eligibility
source_page: https://www.intelycare.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: IntelyCare\naid: intelycare\nurl: https://www.intelycare.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Communication services conduct\n  text: You agree to use the Communication Services only to post, send and receive messages and material that are\n    proper and, when applicable, related to the particular Communication Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If any of the Services requires you to open an account, you must complete the registration process by providing\n\
  \    us with current, complete and accurate information as prompted by the applicable registration form.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Sites.\n"
source_yaml_url: https://artifacts.apis.io/intelycare/eligibility/intelycare-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from IntelyCare's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Healthcare Staffing
- Nursing
- Workforce Management
- Scheduling
- Shift Management
- Timekeeping
- Marketplace
- Webhook
- Per Diem
- Credentialing
- Post-Acute Care
---
