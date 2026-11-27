---
api_specs:
- filename: bisque-cloud-api-openapi.json
  format: json
  label: Bisque API API
  slug: bisque-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bisque-cloud/openapi/_original/bisque-cloud-api-openapi.json
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old — or the age of digital consent in your country, if higher — to use the Service.
    type: individual
  - text: you agree to provide Bisque accurate and complete information about you and your business
    type: business
  minimum_age:
    text: You must be at least 13 years old — or the age of digital consent in your country, if higher — to use the Service.
    value: '13'
  restricted_uses:
  - summary: Prohibited AI content
    text: Use AI generation to create content that sexualizes minors, depicts real individuals without consent (including deceptive voice or likeness impersonation)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with your Google account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bisque
provenance_date: '2026-11-09'
provider_name: Bisque
provider_slug: bisque-cloud
slug: bisque-cloud-eligibility
source_date: '2026-11-09'
source_filename: bisque-cloud-eligibility.yml
source_heading: Eligibility
source_page: https://bisque.today/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bisque\naid: bisque-cloud\nurl: https://bisque.today/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old — or the age of digital consent in your country, if higher — to use the\n    Service.\n- type: business\n  text: you agree to provide Bisque accurate and complete information about you and your business\nrestricted_uses:\n- summary: Prohibited AI content\n  text: Use AI generation to create content that sexualizes minors, depicts real individuals without consent (including\n    deceptive voice\
  \ or likeness impersonation)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with your Google account.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old — or the age of digital consent in your country, if higher — to use the\n    Service.\n"
source_yaml_url: https://artifacts.apis.io/bisque-cloud/eligibility/bisque-cloud-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Bisque's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Code Presentation
---
