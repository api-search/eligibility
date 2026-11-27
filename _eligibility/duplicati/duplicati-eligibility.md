---
api_specs:
- filename: duplicati-openapi-generated.yml
  format: yaml
  label: Duplicati API
  slug: duplicati-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duplicati/openapi/_ae-authored/duplicati-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and offered by Company from its facilities in the United States of America. Company makes no representations that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: THE AUTHORITY TO ENTER INTO THE AGREEMENT PERSONALLY OR ON BEHALF OF THE LEGAL ENTITY IDENTIFIED DURING THE ACCOUNT REGISTRATION PROCESS
    type: business
  minimum_age:
    text: You represent that you are (i) at least eighteen (18) years old; (ii) of legal age to form a binding contract
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
name: Duplicati
provenance_date: '2026-11-09'
provider_name: Duplicati
provider_slug: duplicati
slug: duplicati-eligibility
source_date: '2026-11-09'
source_filename: duplicati-eligibility.yml
source_heading: Eligibility
source_page: https://duplicati.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Duplicati\naid: duplicati\nurl: https://duplicati.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and offered by Company from its facilities in the United States of America.\n    Company makes no representations that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: THE AUTHORITY TO ENTER INTO THE AGREEMENT PERSONALLY OR ON BEHALF OF THE LEGAL ENTITY IDENTIFIED DURING\n    THE ACCOUNT REGISTRATION PROCESS\nrestricted_uses: []\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are (i) at least eighteen (18) years old; (ii) of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/duplicati/eligibility/duplicati-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Duplicati's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Backup
- Open Source
- Cloud
- Security
---
