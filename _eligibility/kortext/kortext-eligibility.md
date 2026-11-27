---
api_specs:
- filename: kortext-chat-api-openapi.yml
  format: yaml
  label: Kortext Chat API
  slug: kortext-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kortext/openapi/kortext-chat-api-openapi.yml
- filename: kortext-content-api-openapi.yml
  format: yaml
  label: Kortext Content API
  slug: kortext-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kortext/openapi/kortext-content-api-openapi.yml
- filename: kortext-health-checks-api-openapi.yml
  format: yaml
  label: Kortext Health Checks API
  slug: kortext-health-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kortext/openapi/kortext-health-checks-api-openapi.yml
- filename: kortext-labs-api-openapi.yml
  format: yaml
  label: Kortext Labs API
  slug: kortext-labs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kortext/openapi/kortext-labs-api-openapi.yml
- filename: kortext-podcast-api-openapi.yml
  format: yaml
  label: Kortext Podcast API
  slug: kortext-podcast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kortext/openapi/kortext-podcast-api-openapi.yml
- filename: kortext-quiz-api-openapi.yml
  format: yaml
  label: Kortext Quiz API
  slug: kortext-quiz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kortext/openapi/kortext-quiz-api-openapi.yml
- filename: kortext-reading-list-api-openapi.yml
  format: yaml
  label: Kortext Reading List API
  slug: kortext-reading-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kortext/openapi/kortext-reading-list-api-openapi.yml
- filename: kortext-test-api-openapi.yml
  format: yaml
  label: Kortext Test API
  slug: kortext-test-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kortext/openapi/kortext-test-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: As a Kortext user, you are granted a personal, non-exclusive, non-transferable, limited licence
    type: individual
  minimum_age:
    text: You confirm that you are over 13 years of age. If you are under the age of 13, please do not access our Platform.
    value: '13'
  restricted_uses:
  - summary: Prohibited activities
    text: When using the Service, you agree to refrain from doing any of the following
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
name: Kortext
provenance_date: '2026-11-09'
provider_name: Kortext
provider_slug: kortext
slug: kortext-eligibility
source_date: '2026-11-09'
source_filename: kortext-eligibility.yml
source_heading: Eligibility
source_page: https://kortext.com/us/website-terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kortext\naid: kortext\nurl: https://kortext.com/us/website-terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: As a Kortext user, you are granted a personal, non-exclusive, non-transferable, limited licence\nrestricted_uses:\n- summary: Prohibited activities\n  text: When using the Service, you agree to refrain from doing any of the following\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You confirm that you are over 13 years of age. If you\
  \ are under the age of 13, please do not access our\n    Platform.\n"
source_yaml_url: https://artifacts.apis.io/kortext/eligibility/kortext-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Kortext's own page on 2026-11-09.
synthetic: false
tags:
- Education
- EdTech
- Higher Education
- Digital Textbooks
- Learning Analytics
- Artificial Intelligence
- Content Delivery
- LTI
- Library
- Student Engagement
- Publishing
---
