---
api_specs:
- filename: jetpackio-openapi-generated.yml
  format: yaml
  label: Jetpack.io API
  slug: jetpackio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jetpackio/openapi/_ae-authored/jetpackio-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and offered by Jetify from its facilities in the United States of America. Jetify makes no representations that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH JETIFY
    type: individual
  - text: THE LEGAL ENTITY IDENTIFIED DURING THE ACCOUNT REGISTRATION PROCESS, AND TO BIND THAT LEGAL ENTITY TO THE AGREEMENT
    type: business
  minimum_age:
    text: You represent that you are (i) at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Prohibited user conduct
    text: you agree not to use any of the Services for any purpose that is prohibited by this Agreement or by applicable law
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
name: Jetpack.io
provenance_date: '2026-11-09'
provider_name: Jetpack.io
provider_slug: jetpackio
slug: jetpackio-eligibility
source_date: '2026-11-09'
source_filename: jetpackio-eligibility.yml
source_heading: Eligibility
source_page: https://www.jetify.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jetpack.io\naid: jetpackio\nurl: https://www.jetify.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and offered by Jetify from its facilities in the United States of America. Jetify\n    makes no representations that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH JETIFY\n- type: business\n  text: THE LEGAL ENTITY IDENTIFIED DURING THE ACCOUNT REGISTRATION PROCESS, AND TO BIND THAT LEGAL ENTITY TO THE\n\
  \    AGREEMENT\nrestricted_uses:\n- summary: Prohibited user conduct\n  text: you agree not to use any of the Services for any purpose that is prohibited by this Agreement or by applicable\n    law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are (i) at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/jetpackio/eligibility/jetpackio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Jetpack.io's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Testing
- Automation
- DevOps
- Software-as-a-Service
---
