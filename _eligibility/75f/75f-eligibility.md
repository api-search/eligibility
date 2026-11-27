---
api_specs:
- filename: 75f-openapi-generated.yml
  format: yaml
  label: 75F API
  slug: 75f-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/75f/openapi/_ae-authored/75f-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 75F makes no representation that the Services ... is appropriate to or available in locations outside of the United States.
  minimum_age:
    text: you (i) are over the age of 18; or (ii) otherwise have the power and authority to enter into and perform your obligations under this Agreement
    value: '18'
  restricted_uses:
  - summary: No emergency services reliance
    text: YOU UNDERSTAND AND ACKNOWLEDGE THAT YOU SHOULD NOT RELY ON THE HARDWARE OR THE SERVICES FOR EMERGENCY RESPONSE MANAGEMENT
  - summary: No unlawful use
    text: use the Services for unlawful purposes
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
name: 75F
provenance_date: '2026-11-09'
provider_name: 75F
provider_slug: 75f
slug: 75f-eligibility
source_date: '2026-11-09'
source_filename: 75f-eligibility.yml
source_heading: Eligibility
source_page: https://www.datocms-assets.com/55631/1648491708-75f-terms-of-service-pdf-2022.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 75F\naid: 75f\nurl: https://www.datocms-assets.com/55631/1648491708-75f-terms-of-service-pdf-2022.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 75F makes no representation that the Services ... is appropriate to or available in locations outside of\n    the United States.\nentity_types: []\nrestricted_uses:\n- summary: No emergency services reliance\n  text: YOU UNDERSTAND AND ACKNOWLEDGE THAT YOU SHOULD NOT RELY ON THE HARDWARE OR THE SERVICES FOR EMERGENCY RESPONSE\n    MANAGEMENT\n- summary: No unlawful use\n  text: use the Services for unlawful purposes\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you (i) are over the age of 18; or (ii) otherwise have the power and authority to enter into and perform\n    your obligations under this Agreement\n"
source_yaml_url: https://artifacts.apis.io/75f/eligibility/75f-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from 75F's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Building Automation
- Smart Buildings
- HVAC
- IoT
- Energy Management
- Project Haystack
- Facilities Management
- Sensors
- Building Management System
---
