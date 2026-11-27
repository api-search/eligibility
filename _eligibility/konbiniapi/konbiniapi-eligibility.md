---
api_specs:
- filename: konbiniapi-instagram-api-openapi.yml
  format: yaml
  label: KonbiniAPI Instagram API
  slug: konbiniapi-instagram-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konbiniapi/openapi/konbiniapi-instagram-api-openapi.yml
- filename: konbiniapi-tiktok-api-openapi.yml
  format: yaml
  label: KonbiniAPI TikTok API
  slug: konbiniapi-tiktok-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konbiniapi/openapi/konbiniapi-tiktok-api-openapi.yml
- filename: konbiniapi-x-api-openapi.yml
  format: yaml
  label: KonbiniAPI X API
  slug: konbiniapi-x-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konbiniapi/openapi/konbiniapi-x-api-openapi.yml
- filename: konbiniapi-reddit-api-openapi.yml
  format: yaml
  label: KonbiniAPI Reddit API
  slug: konbiniapi-reddit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konbiniapi/openapi/konbiniapi-reddit-api-openapi.yml
- filename: konbiniapi-linked-in-api-openapi.yml
  format: yaml
  label: KonbiniAPI Linked In API
  slug: konbiniapi-linked-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konbiniapi/openapi/konbiniapi-linked-in-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  - text: Be at least 18 years old.
    type: individual
  minimum_age:
    text: Be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Illegal activity
    text: Engage in or facilitate any illegal activity under applicable law.
  - summary: Harassment or surveillance
    text: Harass, stalk, monitor, or surveil individuals without their knowledge or consent.
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
name: KonbiniAPI
provenance_date: '2026-11-09'
provider_name: KonbiniAPI
provider_slug: konbiniapi
slug: konbiniapi-eligibility
source_date: '2026-11-09'
source_filename: konbiniapi-eligibility.yml
source_heading: Eligibility
source_page: https://konbiniapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KonbiniAPI\naid: konbiniapi\nurl: https://konbiniapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have the authority to\n    bind that organization to these Terms.\n- type: individual\n  text: Be at least 18 years old.\nrestricted_uses:\n- summary: Illegal activity\n  text: Engage in or facilitate any illegal activity under applicable law.\n- summary: Harassment or surveillance\n  text: Harass, stalk, monitor, or surveil individuals without\
  \ their knowledge or consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/konbiniapi/eligibility/konbiniapi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from KonbiniAPI's own page on 2026-11-09.
synthetic: false
tags:
- Social Media
- Instagram
- TikTok
- X
- Reddit
- LinkedIn
- ActivityStreams 2.0
- Web Scraping
- Data Extraction
- Public Data
- Influencer Marketing
- Social Listening
- Creator Tools
- MCP
- Agent Skills
- Agents
- A2A
---
