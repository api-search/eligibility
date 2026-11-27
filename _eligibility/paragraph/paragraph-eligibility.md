---
api_specs:
- filename: paragraph-analytics-api-openapi.yml
  format: yaml
  label: Paragraph Analytics API
  slug: paragraph-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-analytics-api-openapi.yml
- filename: paragraph-auth-api-openapi.yml
  format: yaml
  label: Paragraph Auth API
  slug: paragraph-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-auth-api-openapi.yml
- filename: paragraph-coins-api-openapi.yml
  format: yaml
  label: Paragraph Coins API
  slug: paragraph-coins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-coins-api-openapi.yml
- filename: paragraph-discover-api-openapi.yml
  format: yaml
  label: Paragraph Discover API
  slug: paragraph-discover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-discover-api-openapi.yml
- filename: paragraph-emails-api-openapi.yml
  format: yaml
  label: Paragraph Emails API
  slug: paragraph-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-emails-api-openapi.yml
- filename: paragraph-me-api-openapi.yml
  format: yaml
  label: Paragraph Me API
  slug: paragraph-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-me-api-openapi.yml
- filename: paragraph-posts-api-openapi.yml
  format: yaml
  label: Paragraph Posts API
  slug: paragraph-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-posts-api-openapi.yml
- filename: paragraph-publications-api-openapi.yml
  format: yaml
  label: Paragraph Publications API
  slug: paragraph-publications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-publications-api-openapi.yml
- filename: paragraph-subscribers-api-openapi.yml
  format: yaml
  label: Paragraph Subscribers API
  slug: paragraph-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-subscribers-api-openapi.yml
- filename: paragraph-users-api-openapi.yml
  format: yaml
  label: Paragraph Users API
  slug: paragraph-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old and legally able to enter into this agreement.
    type: individual
  - text: If you use the Services on behalf of a company or other organization, you represent that you have authority to bind it to these Terms.
    type: business
  minimum_age:
    text: You must be at least 16 years old and legally able to enter into this agreement.
    value: '16'
  restricted_uses:
  - summary: No reliance on AI output for consequential decisions
    text: Don't rely on an AI-generated result to make a decision that could materially affect a person's rights, health, safety, employment, housing, credit, insurance, or access to essential services.
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
name: Paragraph
provenance_date: '2026-11-10'
provider_name: Paragraph
provider_slug: paragraph
slug: paragraph-eligibility
source_date: '2026-11-10'
source_filename: paragraph-eligibility.yml
source_heading: Eligibility
source_page: https://paragraph.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paragraph\naid: paragraph\nurl: https://paragraph.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old and legally able to enter into this agreement.\n- type: business\n  text: If you use the Services on behalf of a company or other organization, you represent that you have authority\n    to bind it to these Terms.\nrestricted_uses:\n- summary: No reliance on AI output for consequential decisions\n  text: Don't rely on an AI-generated result to make a decision that could materially affect\
  \ a person's rights,\n    health, safety, employment, housing, credit, insurance, or access to essential services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old and legally able to enter into this agreement.\n"
source_yaml_url: https://artifacts.apis.io/paragraph/eligibility/paragraph-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Paragraph's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Publishing
- Newsletters
- Web3
- Content
- Blogging
- Creator Economy
---
