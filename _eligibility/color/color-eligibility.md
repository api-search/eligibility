---
api_specs:
- filename: color-eligibility-api-openapi.yml
  format: yaml
  label: Color Eligibility API
  slug: color-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/color/openapi/color-eligibility-api-openapi.yml
- filename: color-populations-api-openapi.yml
  format: yaml
  label: Color Populations API
  slug: color-populations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/color/openapi/color-populations-api-openapi.yml
- filename: color-samples-api-openapi.yml
  format: yaml
  label: Color Samples API
  slug: color-samples-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/color/openapi/color-samples-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Color controls and operates the Services from the United States, and makes no representation that the Service is appropriate or available for use beyond the United States.
  entity_types:
  - text: You must be at least thirteen (13) years old to use the Services, unless specific laws in your state of residence require otherwise.
    type: individual
  minimum_age:
    text: You must be at least thirteen (13) years old to use the Services, unless specific laws in your state of residence require otherwise.
    value: '13'
  restricted_uses:
  - summary: Not for emergencies
    text: USE OF THE SERVICES IS NOT FOR EMERGENCIES. CALL 911 OR GO TO THE NEAREST OPEN EMERGENCY DEPARTMENT FOR EMERGENCIES.
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
name: Color
provenance_date: '2026-11-09'
provider_name: Color
provider_slug: color
slug: color-eligibility
source_date: '2026-11-09'
source_filename: color-eligibility.yml
source_heading: Eligibility
source_page: https://color.com/policies/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Color\naid: color\nurl: https://color.com/policies/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Color controls and operates the Services from the United States, and makes no representation that the Service\n    is appropriate or available for use beyond the United States.\nentity_types:\n- type: individual\n  text: You must be at least thirteen (13) years old to use the Services, unless specific laws in your state of\n    residence require otherwise.\nrestricted_uses:\n- summary: Not for emergencies\n  text: USE OF THE SERVICES IS NOT FOR EMERGENCIES. CALL 911 OR GO TO THE\
  \ NEAREST OPEN EMERGENCY DEPARTMENT FOR\n    EMERGENCIES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least thirteen (13) years old to use the Services, unless specific laws in your state of\n    residence require otherwise.\n"
source_yaml_url: https://artifacts.apis.io/color/eligibility/color-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Color's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Genomics
- Oncology
- Cancer Care
- Preventive Health
- Eligibility
- Virtual Care
- Diagnostics
- Laboratory
- Employee Benefits
---
