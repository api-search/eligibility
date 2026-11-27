---
api_specs:
- filename: arctop-arctop-api-api-openapi.yml
  format: yaml
  label: Arctop Arctop API
  slug: arctop-arctop-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arctop/openapi/arctop-arctop-api-api-openapi.yml
- filename: arctop-dev-api-openapi.yml
  format: yaml
  label: Arctop Dev API
  slug: arctop-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arctop/openapi/arctop-dev-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Arctop makes no representations that the Service is appropriate or available for use in other locations.
  entity_types:
  - text: solely for your own personal purposes
    type: individual
  - text: ON BEHALF OF THE ENTITY IDENTIFIED IN THE ACCOUNT REGISTRATION PROCESS
    type: business
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH ARCTOP
    value: legal age
  restricted_uses:
  - summary: Medical advice or diagnosis
    text: ARCTOP DOES NOT OFFER MEDICAL ADVICE. ANY CONTENT ACCESSED THROUGH THE SERVICE IS FOR INFORMATIONAL AND EDUCATIONAL PURPOSES ONLY.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: provide true, accurate, current, and complete information about yourself as prompted by the registration form
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Arctop
provenance_date: '2026-11-09'
provider_name: Arctop
provider_slug: arctop
slug: arctop-eligibility
source_date: '2026-11-09'
source_filename: arctop-eligibility.yml
source_heading: Eligibility
source_page: https://arctop.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arctop\naid: arctop\nurl: https://arctop.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Arctop makes no representations that the Service is appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: solely for your own personal purposes\n- type: business\n  text: ON BEHALF OF THE ENTITY IDENTIFIED IN THE ACCOUNT REGISTRATION PROCESS\nrestricted_uses:\n- summary: Medical advice or diagnosis\n  text: ARCTOP DOES NOT OFFER MEDICAL ADVICE. ANY CONTENT ACCESSED THROUGH THE SERVICE IS FOR INFORMATIONAL AND\n    EDUCATIONAL\
  \ PURPOSES ONLY.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: provide true, accurate, current, and complete information about yourself as prompted by the registration\n    form\nminimum_age:\n  value: legal age\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH ARCTOP\n"
source_yaml_url: https://artifacts.apis.io/arctop/eligibility/arctop-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Arctop's own page on 2026-11-09.
synthetic: false
tags:
- Brain-Computer Interface
- Neural Data
- API Platform
- Healthcare
- Research
---
