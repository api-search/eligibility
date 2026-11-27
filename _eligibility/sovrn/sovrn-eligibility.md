---
api_specs:
- filename: sovrn-account-api-openapi.yml
  format: yaml
  label: Sovrn Account API
  slug: sovrn-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-account-api-openapi.yml
- filename: sovrn-ai-orchestration-api-openapi.yml
  format: yaml
  label: Sovrn Ai Orchestration API
  slug: sovrn-ai-orchestration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-ai-orchestration-api-openapi.yml
- filename: sovrn-bid-api-openapi.yml
  format: yaml
  label: Sovrn Bid API
  slug: sovrn-bid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-bid-api-openapi.yml
- filename: sovrn-link-api-openapi.yml
  format: yaml
  label: Sovrn Link API
  slug: sovrn-link-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-link-api-openapi.yml
- filename: sovrn-merchant-group-summaries-api-openapi.yml
  format: yaml
  label: Sovrn Merchant Group Summaries API
  slug: sovrn-merchant-group-summaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-merchant-group-summaries-api-openapi.yml
- filename: sovrn-product-coupons-api-openapi.yml
  format: yaml
  label: Sovrn Product Coupons API
  slug: sovrn-product-coupons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-product-coupons-api-openapi.yml
- filename: sovrn-reporting-api-openapi.yml
  format: yaml
  label: Sovrn Reporting API
  slug: sovrn-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-reporting-api-openapi.yml
- filename: sovrn-reports-api-openapi.yml
  format: yaml
  label: Sovrn Reports API
  slug: sovrn-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-reports-api-openapi.yml
- filename: sovrn-sites-api-openapi.yml
  format: yaml
  label: Sovrn Sites API
  slug: sovrn-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-sites-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the business entity or person for whom you
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Child-directed sites excluded
    text: the Sites are not “directed to children” or “likely to be accessed by children”
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
name: Sovrn
provenance_date: '2026-11-10'
provider_name: Sovrn
provider_slug: sovrn
slug: sovrn-eligibility
source_date: '2026-11-10'
source_filename: sovrn-eligibility.yml
source_heading: Eligibility
source_page: https://www.sovrn.com/legal/msa/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sovrn\naid: sovrn\nurl: https://www.sovrn.com/legal/msa/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the business entity or person for whom you\nrestricted_uses:\n- summary: Child-directed sites excluded\n  text: the Sites are not “directed to children” or “likely to be accessed by children”\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sovrn/eligibility/sovrn-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Sovrn's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AdTech
- Advertising
- Monetization
- Affiliate Marketing
- Programmatic
- Publishers
- Commerce
- Data
- Reporting
- Product Data
- Agent-Native
---
