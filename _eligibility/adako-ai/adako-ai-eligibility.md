---
api_specs:
- filename: adako-ai-adako-api-openapi.yml
  format: yaml
  label: Adako Adako API
  slug: adako-ai-adako-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adako-ai/openapi/adako-ai-adako-api-openapi.yml
- filename: adako-ai-chatgpt-ads-api-openapi.yml
  format: yaml
  label: Adako ChatGPT Ads API
  slug: adako-ai-chatgpt-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adako-ai/openapi/adako-ai-chatgpt-ads-api-openapi.yml
- filename: adako-ai-discovery-api-openapi.yml
  format: yaml
  label: Adako Discovery API
  slug: adako-ai-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adako-ai/openapi/adako-ai-discovery-api-openapi.yml
- filename: adako-ai-google-ads-api-openapi.yml
  format: yaml
  label: Adako Google Ads API
  slug: adako-ai-google-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adako-ai/openapi/adako-ai-google-ads-api-openapi.yml
- filename: adako-ai-linkedin-ads-api-openapi.yml
  format: yaml
  label: Adako LinkedIn Ads API
  slug: adako-ai-linkedin-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adako-ai/openapi/adako-ai-linkedin-ads-api-openapi.yml
- filename: adako-ai-meta-ads-api-openapi.yml
  format: yaml
  label: Adako Meta Ads API
  slug: adako-ai-meta-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adako-ai/openapi/adako-ai-meta-ads-api-openapi.yml
- filename: adako-ai-tiktok-ads-api-openapi.yml
  format: yaml
  label: Adako TikTok Ads API
  slug: adako-ai-tiktok-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adako-ai/openapi/adako-ai-tiktok-ads-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and use the Service for business or professional purposes.
    type: individual
  - text: If you use the Service for an organisation, you accept these Terms on its behalf
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Sanctions and export control
    text: you will not use the Service in breach of export control or sanctions laws
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
name: Adako
provenance_date: '2026-11-09'
provider_name: Adako
provider_slug: adako-ai
slug: adako-ai-eligibility
source_date: '2026-11-09'
source_filename: adako-ai-eligibility.yml
source_heading: Eligibility
source_page: https://adako.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adako\naid: adako-ai\nurl: https://adako.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and use the Service for business or professional purposes.\n- type: business\n  text: If you use the Service for an organisation, you accept these Terms on its behalf\nrestricted_uses:\n- summary: Sanctions and export control\n  text: you will not use the Service in breach of export control or sanctions laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/adako-ai/eligibility/adako-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Adako's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Artificial Intelligence
- Marketing
- MCP
- Automation
---
