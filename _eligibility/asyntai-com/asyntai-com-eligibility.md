---
api_specs:
- filename: asyntai-com-openapi-generated.yml
  format: yaml
  label: Asyntai API
  slug: asyntai-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asyntai-com/openapi/_ae-authored/asyntai-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are a person or entity barred from receiving the Services under the laws of the Czech Republic or other countries including the country in which you are resident or from which you use the Services.
  entity_types:
  - text: you are not of legal age to form a binding contract
    type: individual
  - text: when contracting on behalf of an entity, you are not authorized to legally bind your company or organization to such terms
    type: business
  minimum_age:
    text: you are not of legal age to form a binding contract
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: Use the Service for any illegal or unauthorized purpose;
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
name: Asyntai
provenance_date: '2026-11-09'
provider_name: Asyntai
provider_slug: asyntai-com
slug: asyntai-com-eligibility
source_date: '2026-11-09'
source_filename: asyntai-com-eligibility.yml
source_heading: Eligibility
source_page: https://asyntai.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Asyntai\naid: asyntai-com\nurl: https://asyntai.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are a person or entity barred from receiving the Services under the laws of the Czech Republic or other\n    countries including the country in which you are resident or from which you use the Services.\nentity_types:\n- type: individual\n  text: you are not of legal age to form a binding contract\n- type: business\n  text: when contracting on behalf of an entity, you are not authorized to legally bind your company or organization\n    to such terms\nrestricted_uses:\n\
  - summary: Illegal or unauthorized purpose\n  text: Use the Service for any illegal or unauthorized purpose;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/asyntai-com/eligibility/asyntai-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Asyntai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Chatbots
- Customer Service
- Software-as-a-Service
- Website Integration
- Multilingual
---
