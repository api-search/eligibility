---
api_specs:
- filename: brandnamemaker-com-hero-api-openapi.yml
  format: yaml
  label: True Frontier Hero API
  slug: brandnamemaker-com-hero-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandnamemaker-com/openapi/brandnamemaker-com-hero-api-openapi.yml
- filename: brandnamemaker-com-name-api-openapi.yml
  format: yaml
  label: True Frontier Name API
  slug: brandnamemaker-com-name-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandnamemaker-com/openapi/brandnamemaker-com-name-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use the Services, or older if the law where you live requires it.
    type: individual
  - text: If you use the Services on behalf of a company or other organization, you agree to these Terms for that organization and confirm that you have the authority to do so.
    type: business
  minimum_age:
    text: You must be at least 13 years old to use the Services, or older if the law where you live requires it.
    value: '13'
  restricted_uses:
  - summary: Sanctioned or legally prohibited use
    text: You may not use the Services if the law, including trade sanctions, prohibits you from doing so.
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
name: True Frontier
provenance_date: '2026-11-09'
provider_name: True Frontier
provider_slug: brandnamemaker-com
slug: brandnamemaker-com-eligibility
source_date: '2026-11-09'
source_filename: brandnamemaker-com-eligibility.yml
source_heading: Eligibility
source_page: https://brandnamemaker.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: True Frontier\naid: brandnamemaker-com\nurl: https://brandnamemaker.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Services, or older if the law where you live requires it.\n- type: business\n  text: If you use the Services on behalf of a company or other organization, you agree to these Terms for that\n    organization and confirm that you have the authority to do so.\nrestricted_uses:\n- summary: Sanctioned or legally prohibited use\n  text: You may not use the Services if the\
  \ law, including trade sanctions, prohibits you from doing so.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Services, or older if the law where you live requires it.\n"
source_yaml_url: https://artifacts.apis.io/brandnamemaker-com/eligibility/brandnamemaker-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from True Frontier's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Naming
- Branding
- Domain Check
---
