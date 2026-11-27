---
api_specs:
- filename: githunt-ai-briefs-api-openapi.yml
  format: yaml
  label: githunt-ai Briefs API
  slug: githunt-ai-briefs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/githunt-ai/openapi/githunt-ai-briefs-api-openapi.yml
- filename: githunt-ai-lists-api-openapi.yml
  format: yaml
  label: githunt-ai Lists API
  slug: githunt-ai-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/githunt-ai/openapi/githunt-ai-lists-api-openapi.yml
- filename: githunt-ai-profile-api-openapi.yml
  format: yaml
  label: githunt-ai Profile API
  slug: githunt-ai-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/githunt-ai/openapi/githunt-ai-profile-api-openapi.yml
- filename: githunt-ai-search-api-openapi.yml
  format: yaml
  label: githunt-ai Search API
  slug: githunt-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/githunt-ai/openapi/githunt-ai-search-api-openapi.yml
- filename: githunt-ai-users-api-openapi.yml
  format: yaml
  label: githunt-ai Users API
  slug: githunt-ai-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/githunt-ai/openapi/githunt-ai-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use our Service.
    value: '18'
  restricted_uses:
  - summary: Discrimination in hiring
    text: 'Discrimination: Making hiring decisions based on protected characteristics'
  - summary: Privacy violations
    text: 'Privacy violations: Violating the privacy rights of individuals listed in reports'
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
name: githunt-ai
provenance_date: '2026-11-09'
provider_name: githunt-ai
provider_slug: githunt-ai
slug: githunt-ai-eligibility
source_date: '2026-11-09'
source_filename: githunt-ai-eligibility.yml
source_heading: Eligibility
source_page: https://githunt.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: githunt-ai\naid: githunt-ai\nurl: https://githunt.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority\n    to bind that organization to these Terms.\nrestricted_uses:\n- summary: Discrimination in hiring\n  text: 'Discrimination: Making hiring decisions based on protected characteristics'\n- summary: Privacy violations\n  text: 'Privacy violations: Violating the privacy rights of individuals listed in reports'\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our Service.\n"
source_yaml_url: https://artifacts.apis.io/githunt-ai/eligibility/githunt-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from githunt-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Talent
- Recruiting
- Developers
---
