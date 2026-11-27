---
api_specs:
- filename: upspring-ai-ads-api-openapi.yml
  format: yaml
  label: upspring-ai Ads API
  slug: upspring-ai-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upspring-ai/openapi/upspring-ai-ads-api-openapi.yml
- filename: upspring-ai-advertisers-api-openapi.yml
  format: yaml
  label: upspring-ai Advertisers API
  slug: upspring-ai-advertisers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upspring-ai/openapi/upspring-ai-advertisers-api-openapi.yml
- filename: upspring-ai-docs-api-openapi.yml
  format: yaml
  label: upspring-ai Docs API
  slug: upspring-ai-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upspring-ai/openapi/upspring-ai-docs-api-openapi.yml
- filename: upspring-ai-taxonomy-api-openapi.yml
  format: yaml
  label: upspring-ai Taxonomy API
  slug: upspring-ai-taxonomy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upspring-ai/openapi/upspring-ai-taxonomy-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent that you are at least 18 years of age (or the age of majority in your jurisdiction)
    type: individual
  - text: If you are using the Service on behalf of a company or organization, you represent that you have authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Competitors barred without consent
    text: Competitors and individuals developing similar or competing services are prohibited from accessing the Service without our prior written consent.
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
name: upspring-ai
provenance_date: '2026-11-10'
provider_name: upspring-ai
provider_slug: upspring-ai
slug: upspring-ai-eligibility
source_date: '2026-11-10'
source_filename: upspring-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.upspring.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: upspring-ai\naid: upspring-ai\nurl: https://www.upspring.ai/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent that you are at least 18 years of age (or the age of majority in your jurisdiction)\n- type: business\n  text: If you are using the Service on behalf of a company or organization, you represent that you have authority\n    to bind that entity to these Terms\nrestricted_uses:\n- summary: Competitors barred without consent\n  text: Competitors and individuals developing similar or competing services are\
  \ prohibited from accessing the Service\n    without our prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/upspring-ai/eligibility/upspring-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from upspring-ai's own page on 2026-11-10.
synthetic: false
tags:
- Advertising
- Artificial Intelligence
- Data
- Marketing
- Platform
---
