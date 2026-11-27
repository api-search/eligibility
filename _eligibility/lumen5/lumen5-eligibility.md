---
api_specs:
- filename: lumen5-video-creation-api-openapi.yml
  format: yaml
  label: Lumen5 Video Creation API
  slug: lumen5-video-creation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumen5/openapi/lumen5-video-creation-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    - US
    text: The Service is intended for visitors located within Canada and the United States. We make no representation that the Service is appropriate or available for use outside of Canada and the United States.
  entity_types:
  - text: You must be at least 16 years old to use the Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
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
name: Lumen5
provenance_date: '2026-11-09'
provider_name: Lumen5
provider_slug: lumen5
slug: lumen5-eligibility
source_date: '2026-11-09'
source_filename: lumen5-eligibility.yml
source_heading: Eligibility
source_page: https://lumen5.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lumen5\naid: lumen5\nurl: https://lumen5.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within Canada and the United States. We make no representation\n    that the Service is appropriate or available for use outside of Canada and the United States.\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to use the Service.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have\
  \ authority to bind you to these Terms\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/lumen5/eligibility/lumen5-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Lumen5's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
