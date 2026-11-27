---
api_specs:
- filename: aitwire-com-api-keys-api-openapi.yml
  format: yaml
  label: aitwire-com API Keys API
  slug: aitwire-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-api-keys-api-openapi.yml
- filename: aitwire-com-attribution-api-openapi.yml
  format: yaml
  label: aitwire-com Attribution API
  slug: aitwire-com-attribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-attribution-api-openapi.yml
- filename: aitwire-com-authority-api-openapi.yml
  format: yaml
  label: aitwire-com Authority API
  slug: aitwire-com-authority-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-authority-api-openapi.yml
- filename: aitwire-com-billing-api-openapi.yml
  format: yaml
  label: aitwire-com Billing API
  slug: aitwire-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-billing-api-openapi.yml
- filename: aitwire-com-drift-api-openapi.yml
  format: yaml
  label: aitwire-com Drift API
  slug: aitwire-com-drift-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-drift-api-openapi.yml
- filename: aitwire-com-entities-api-openapi.yml
  format: yaml
  label: aitwire-com Entities API
  slug: aitwire-com-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-entities-api-openapi.yml
- filename: aitwire-com-scans-api-openapi.yml
  format: yaml
  label: aitwire-com Scans API
  slug: aitwire-com-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-scans-api-openapi.yml
- filename: aitwire-com-webhooks-api-openapi.yml
  format: yaml
  label: aitwire-com Webhooks API
  slug: aitwire-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least the age of majority in your jurisdiction and legally capable of entering into these Terms.
    type: individual
  - text: If you accept on behalf of an organization, you represent that you have authority to bind it.
    type: business
  minimum_age:
    text: You must be at least the age of majority in your jurisdiction and legally capable of entering into these Terms.
    value: age of majority
  restricted_uses:
  - summary: Regulated industry restrictions
    text: AITWIRE may restrict or disable certain Service features (including Commerce Features, AI Signals, or specific content generation capabilities) for Customer Entities operating in regulated categories, at AITWIRE 's sole discretion.
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
name: aitwire-com
provenance_date: '2026-11-09'
provider_name: aitwire-com
provider_slug: aitwire-com
slug: aitwire-com-eligibility
source_date: '2026-11-09'
source_filename: aitwire-com-eligibility.yml
source_heading: Eligibility
source_page: https://aitwire.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: aitwire-com\naid: aitwire-com\nurl: https://aitwire.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least the age of majority in your jurisdiction and legally capable of entering into these\n    Terms.\n- type: business\n  text: If you accept on behalf of an organization, you represent that you have authority to bind it.\nrestricted_uses:\n- summary: Regulated industry restrictions\n  text: AITWIRE may restrict or disable certain Service features (including Commerce Features, AI Signals,\
  \ or specific\n    content generation capabilities) for Customer Entities operating in regulated categories, at AITWIRE 's sole\n    discretion.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You must be at least the age of majority in your jurisdiction and legally capable of entering into these\n    Terms.\n"
source_yaml_url: https://artifacts.apis.io/aitwire-com/eligibility/aitwire-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from aitwire-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- IoT
- Connectivity
- Industrial
---
