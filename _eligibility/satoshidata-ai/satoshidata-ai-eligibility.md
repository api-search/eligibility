---
api_specs:
- filename: satoshidata-ai-batch-api-openapi.yml
  format: yaml
  label: satoshidata-ai Batch API
  slug: satoshidata-ai-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/satoshidata-ai/openapi/satoshidata-ai-batch-api-openapi.yml
- filename: satoshidata-ai-billing-api-openapi.yml
  format: yaml
  label: satoshidata-ai Billing API
  slug: satoshidata-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/satoshidata-ai/openapi/satoshidata-ai-billing-api-openapi.yml
- filename: satoshidata-ai-chain-api-openapi.yml
  format: yaml
  label: satoshidata-ai Chain API
  slug: satoshidata-ai-chain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/satoshidata-ai/openapi/satoshidata-ai-chain-api-openapi.yml
- filename: satoshidata-ai-community-api-openapi.yml
  format: yaml
  label: satoshidata-ai Community API
  slug: satoshidata-ai-community-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/satoshidata-ai/openapi/satoshidata-ai-community-api-openapi.yml
- filename: satoshidata-ai-discovery-api-openapi.yml
  format: yaml
  label: satoshidata-ai Discovery API
  slug: satoshidata-ai-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/satoshidata-ai/openapi/satoshidata-ai-discovery-api-openapi.yml
- filename: satoshidata-ai-entities-api-openapi.yml
  format: yaml
  label: satoshidata-ai Entities API
  slug: satoshidata-ai-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/satoshidata-ai/openapi/satoshidata-ai-entities-api-openapi.yml
- filename: satoshidata-ai-feedback-api-openapi.yml
  format: yaml
  label: satoshidata-ai Feedback API
  slug: satoshidata-ai-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/satoshidata-ai/openapi/satoshidata-ai-feedback-api-openapi.yml
- filename: satoshidata-ai-health-api-openapi.yml
  format: yaml
  label: satoshidata-ai Health API
  slug: satoshidata-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/satoshidata-ai/openapi/satoshidata-ai-health-api-openapi.yml
- filename: satoshidata-ai-labels-api-openapi.yml
  format: yaml
  label: satoshidata-ai Labels API
  slug: satoshidata-ai-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/satoshidata-ai/openapi/satoshidata-ai-labels-api-openapi.yml
- filename: satoshidata-ai-market-api-openapi.yml
  format: yaml
  label: satoshidata-ai Market API
  slug: satoshidata-ai-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/satoshidata-ai/openapi/satoshidata-ai-market-api-openapi.yml
- filename: satoshidata-ai-metrics-api-openapi.yml
  format: yaml
  label: satoshidata-ai Metrics API
  slug: satoshidata-ai-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/satoshidata-ai/openapi/satoshidata-ai-metrics-api-openapi.yml
- filename: satoshidata-ai-risk-api-openapi.yml
  format: yaml
  label: satoshidata-ai Risk API
  slug: satoshidata-ai-risk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/satoshidata-ai/openapi/satoshidata-ai-risk-api-openapi.yml
- filename: satoshidata-ai-sanctions-api-openapi.yml
  format: yaml
  label: satoshidata-ai Sanctions API
  slug: satoshidata-ai-sanctions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/satoshidata-ai/openapi/satoshidata-ai-sanctions-api-openapi.yml
- filename: satoshidata-ai-timestamping-api-openapi.yml
  format: yaml
  label: satoshidata-ai Timestamping API
  slug: satoshidata-ai-timestamping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/satoshidata-ai/openapi/satoshidata-ai-timestamping-api-openapi.yml
- filename: satoshidata-ai-wallets-api-openapi.yml
  format: yaml
  label: satoshidata-ai Wallets API
  slug: satoshidata-ai-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/satoshidata-ai/openapi/satoshidata-ai-wallets-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automated adverse decisions
    text: to make an automated adverse decision about a person without your own independent basis
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: manages a global, signup-less audience
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: satoshidata-ai
provenance_date: '2026-11-10'
provider_name: satoshidata-ai
provider_slug: satoshidata-ai
slug: satoshidata-ai-eligibility
source_date: '2026-11-10'
source_filename: satoshidata-ai-eligibility.yml
source_heading: Eligibility
source_page: https://satoshidata.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: satoshidata-ai\naid: satoshidata-ai\nurl: https://satoshidata.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Automated adverse decisions\n  text: to make an automated adverse decision about a person without your own independent basis\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: manages a global, signup-less audience\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/satoshidata-ai/eligibility/satoshidata-ai-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from satoshidata-ai's own page on 2026-11-10.
synthetic: false
tags:
- Bitcoin
- Artificial Intelligence
- Finance
- Chain-Intelligence
- Company
---
