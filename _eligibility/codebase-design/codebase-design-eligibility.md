---
api_specs:
- filename: codebase-design-account-api-openapi.yml
  format: yaml
  label: Codebase Account API
  slug: codebase-design-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-account-api-openapi.yml
- filename: codebase-design-admin-api-openapi.yml
  format: yaml
  label: Codebase Admin API
  slug: codebase-design-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-admin-api-openapi.yml
- filename: codebase-design-api-keys-api-openapi.yml
  format: yaml
  label: Codebase API Keys API
  slug: codebase-design-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-api-keys-api-openapi.yml
- filename: codebase-design-billing-api-openapi.yml
  format: yaml
  label: Codebase Billing API
  slug: codebase-design-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-billing-api-openapi.yml
- filename: codebase-design-builds-api-openapi.yml
  format: yaml
  label: Codebase Builds API
  slug: codebase-design-builds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-builds-api-openapi.yml
- filename: codebase-design-community-api-openapi.yml
  format: yaml
  label: Codebase Community API
  slug: codebase-design-community-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-community-api-openapi.yml
- filename: codebase-design-credits-api-openapi.yml
  format: yaml
  label: Codebase Credits API
  slug: codebase-design-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-credits-api-openapi.yml
- filename: codebase-design-deploys-api-openapi.yml
  format: yaml
  label: Codebase Deploys API
  slug: codebase-design-deploys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-deploys-api-openapi.yml
- filename: codebase-design-gallery-api-openapi.yml
  format: yaml
  label: Codebase Gallery API
  slug: codebase-design-gallery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-gallery-api-openapi.yml
- filename: codebase-design-health-api-openapi.yml
  format: yaml
  label: Codebase Health API
  slug: codebase-design-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-health-api-openapi.yml
- filename: codebase-design-inference-api-openapi.yml
  format: yaml
  label: Codebase Inference API
  slug: codebase-design-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-inference-api-openapi.yml
- filename: codebase-design-platform-api-openapi.yml
  format: yaml
  label: Codebase Platform API
  slug: codebase-design-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-platform-api-openapi.yml
- filename: codebase-design-projects-api-openapi.yml
  format: yaml
  label: Codebase Projects API
  slug: codebase-design-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-projects-api-openapi.yml
- filename: codebase-design-prompts-api-openapi.yml
  format: yaml
  label: Codebase Prompts API
  slug: codebase-design-prompts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-prompts-api-openapi.yml
- filename: codebase-design-sessions-api-openapi.yml
  format: yaml
  label: Codebase Sessions API
  slug: codebase-design-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebase-design/openapi/codebase-design-sessions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into this agreement.
    type: individual
  - text: If you use Codebase for a company or other organization, you represent that you have authority to bind it to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into this agreement.
    value: '18'
  restricted_uses:
  - summary: Regulated data
    text: store or process payment-card data, protected health information, or other specially regulated data without a separate written agreement with us
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
name: Codebase
provenance_date: '2026-11-09'
provider_name: Codebase
provider_slug: codebase-design
slug: codebase-design-eligibility
source_date: '2026-11-09'
source_filename: codebase-design-eligibility.yml
source_heading: Eligibility
source_page: https://codebase.design/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Codebase\naid: codebase-design\nurl: https://codebase.design/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into this agreement.\n- type: business\n  text: If you use Codebase for a company or other organization, you represent that you have authority to bind it\n    to these Terms.\nrestricted_uses:\n- summary: Regulated data\n  text: store or process payment-card data, protected health information, or other specially regulated data without\n    a separate written agreement\
  \ with us\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into this agreement.\n"
source_yaml_url: https://artifacts.apis.io/codebase-design/eligibility/codebase-design-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Codebase's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI App Builder
- Code Generation
- Developer Tools
- Open-Weight Models
- CLI
- MCP
- Web3
---
