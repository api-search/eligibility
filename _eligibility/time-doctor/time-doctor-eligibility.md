---
api_specs:
- filename: time-doctor-openapi-generated.yml
  format: yaml
  label: Time Doctor API
  slug: time-doctor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/time-doctor/openapi/_ae-authored/time-doctor-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer and Users shall not access or use the Software Subscription in a U.S. embargoed country.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and embargoed countries
    text: Customer may not use, or provide to any person or export or re-export or allow the export or re-export of the Software Subscription
  - summary: Competitive purposes
    text: Customer may not access the Software for any competitive purposes whatsoever.
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
name: Time Doctor
provenance_date: '2026-11-10'
provider_name: Time Doctor
provider_slug: time-doctor
slug: time-doctor-eligibility
source_date: '2026-11-10'
source_filename: time-doctor-eligibility.yml
source_heading: Eligibility
source_page: https://www.timedoctor.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Time Doctor\naid: time-doctor\nurl: https://www.timedoctor.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer and Users shall not access or use the Software Subscription in a U.S. embargoed country.\nentity_types: []\nrestricted_uses:\n- summary: Export and embargoed countries\n  text: Customer may not use, or provide to any person or export or re-export or allow the export or re-export of\n    the Software Subscription\n- summary: Competitive purposes\n  text: Customer may not access the Software for any competitive purposes whatsoever.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/time-doctor/eligibility/time-doctor-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Time Doctor's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Time Tracking
- Workforce Management
- Productivity
- Artificial Intelligence
---
