---
api_specs:
- filename: firetail-openapi-generated.yml
  format: yaml
  label: FireTail API
  slug: firetail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firetail/openapi/_ae-authored/firetail-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) You are not located in a country that is subject to the United States government embargo
  entity_types:
  - text: You means the individual accessing or using the Service
    type: individual
  - text: or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: business
  minimum_age:
    text: You represent that you are over the age of 18.
    value: '18'
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
name: FireTail
provenance_date: '2026-11-09'
provider_name: FireTail
provider_slug: firetail
slug: firetail-eligibility
source_date: '2026-11-09'
source_filename: firetail-eligibility.yml
source_heading: Eligibility
source_page: https://www.firetail.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FireTail\naid: firetail\nurl: https://www.firetail.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) You are not located in a country that is subject to the United States\n    government embargo\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service\n- type: business\n  text: or the company, or other legal entity on behalf of which such individual is accessing or using the Service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You represent that you are over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/firetail/eligibility/firetail-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from FireTail's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Security
- Governance
- Platform
- Cloud
---
