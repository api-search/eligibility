---
api_specs:
- filename: system-api-openapi.json
  format: json
  label: System REST API API
  slug: system-rest-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/system/openapi/_original/system-api-openapi.json
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company makes no representations that the Service is appropriate or available for use in other locations.
  entity_types:
  - text: You must be at least eighteen (18) years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least eighteen (18) years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Not for consumers or personal use
    text: THE SERVICE IS NOT INTENDED FOR PERSONAL OR DOMESTIC USE OR OTHERWISE FOR USE BY ANY PERSON ACTING AS A CONSUMER.
  - summary: No medical device use
    text: THE SERVICE IS NOT MEDICAL DEVICE SOFTWARE (AS DEFINED IN SECTION 1.8) AND IS NOT INTENDED FOR USE FOR ANY MEDICAL PURPOSES
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
name: System
provenance_date: '2026-11-10'
provider_name: System
provider_slug: system
slug: system-eligibility
source_date: '2026-11-10'
source_filename: system-eligibility.yml
source_heading: Eligibility
source_page: https://docs.system.com/system/legal/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: System\naid: system\nurl: https://docs.system.com/system/legal/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Company makes no representations that the Service is appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old to use the Service.\nrestricted_uses:\n- summary: Not for consumers or personal use\n  text: THE SERVICE IS NOT INTENDED FOR PERSONAL OR DOMESTIC USE OR OTHERWISE FOR USE BY ANY PERSON ACTING AS A\n    CONSUMER.\n- summary: No medical device use\n  text: THE SERVICE\
  \ IS NOT MEDICAL DEVICE SOFTWARE (AS DEFINED IN SECTION 1.8) AND IS NOT INTENDED FOR USE FOR ANY\n    MEDICAL PURPOSES\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/system/eligibility/system-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from System's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Population Health
- Knowledge Graph
- API Platform
- Public Benefit Corporation
---
