---
api_specs:
- filename: autoposting-ai-agents-api-openapi.yml
  format: yaml
  label: Autoposting.ai Agents API
  slug: autoposting-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-agents-api-openapi.yml
- filename: autoposting-ai-api-keys-api-openapi.yml
  format: yaml
  label: Autoposting.ai API Keys API
  slug: autoposting-ai-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-api-keys-api-openapi.yml
- filename: autoposting-ai-auth-api-openapi.yml
  format: yaml
  label: Autoposting.ai Auth API
  slug: autoposting-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-auth-api-openapi.yml
- filename: autoposting-ai-billing-api-openapi.yml
  format: yaml
  label: Autoposting.ai Billing API
  slug: autoposting-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-billing-api-openapi.yml
- filename: autoposting-ai-brands-api-openapi.yml
  format: yaml
  label: Autoposting.ai Brands API
  slug: autoposting-ai-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-brands-api-openapi.yml
- filename: autoposting-ai-carousels-api-openapi.yml
  format: yaml
  label: Autoposting.ai Carousels API
  slug: autoposting-ai-carousels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-carousels-api-openapi.yml
- filename: autoposting-ai-clips-api-openapi.yml
  format: yaml
  label: Autoposting.ai Clips API
  slug: autoposting-ai-clips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-clips-api-openapi.yml
- filename: autoposting-ai-knowledge-base-api-openapi.yml
  format: yaml
  label: Autoposting.ai Knowledge Base API
  slug: autoposting-ai-knowledge-base-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-knowledge-base-api-openapi.yml
- filename: autoposting-ai-notifications-api-openapi.yml
  format: yaml
  label: Autoposting.ai Notifications API
  slug: autoposting-ai-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-notifications-api-openapi.yml
- filename: autoposting-ai-organizations-api-openapi.yml
  format: yaml
  label: Autoposting.ai Organizations API
  slug: autoposting-ai-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-organizations-api-openapi.yml
- filename: autoposting-ai-platform-oauth-api-openapi.yml
  format: yaml
  label: Autoposting.ai Platform OAuth API
  slug: autoposting-ai-platform-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-platform-oauth-api-openapi.yml
- filename: autoposting-ai-posts-api-openapi.yml
  format: yaml
  label: Autoposting.ai Posts API
  slug: autoposting-ai-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-posts-api-openapi.yml
- filename: autoposting-ai-teams-api-openapi.yml
  format: yaml
  label: Autoposting.ai Teams API
  slug: autoposting-ai-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-teams-api-openapi.yml
- filename: autoposting-ai-usage-api-openapi.yml
  format: yaml
  label: Autoposting.ai Usage API
  slug: autoposting-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-usage-api-openapi.yml
- filename: autoposting-ai-webhooks-api-openapi.yml
  format: yaml
  label: Autoposting.ai Webhooks API
  slug: autoposting-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Have the authority to bind yourself or your organization to these Terms
    type: business
  minimum_age:
    text: Are at least 16 years of age
    value: '16'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: Post content that violates applicable law or the terms of connected social platforms
  - summary: Malware or phishing
    text: Use the Service to distribute malware, phishing content, or deceptive material
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
name: Autoposting.ai
provenance_date: '2026-11-09'
provider_name: Autoposting.ai
provider_slug: autoposting-ai
slug: autoposting-ai-eligibility
source_date: '2026-11-09'
source_filename: autoposting-ai-eligibility.yml
source_heading: Eligibility
source_page: https://autoposting.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Autoposting.ai\naid: autoposting-ai\nurl: https://autoposting.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Have the authority to bind yourself or your organization to these Terms\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: Post content that violates applicable law or the terms of connected social platforms\n- summary: Malware or phishing\n  text: Use the Service to distribute malware, phishing content, or deceptive material\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '16'\n  text: Are at least 16 years of age\n"
source_yaml_url: https://artifacts.apis.io/autoposting-ai/eligibility/autoposting-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Autoposting.ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Social Media
- Automation
- Marketing
- Developer Tools
- Company
---
