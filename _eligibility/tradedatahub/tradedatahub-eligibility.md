---
api_specs:
- filename: tradedatahub-commerce-api-openapi.yml
  format: yaml
  label: TradeDataHub Public API Commerce API
  slug: tradedatahub-commerce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradedatahub/openapi/tradedatahub-commerce-api-openapi.yml
- filename: tradedatahub-datasets-api-openapi.yml
  format: yaml
  label: TradeDataHub Public API Datasets API
  slug: tradedatahub-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradedatahub/openapi/tradedatahub-datasets-api-openapi.yml
- filename: tradedatahub-discovery-api-openapi.yml
  format: yaml
  label: TradeDataHub Public API Discovery API
  slug: tradedatahub-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradedatahub/openapi/tradedatahub-discovery-api-openapi.yml
claim_count: 1
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
  - summary: Outreach compliance
    text: Inclusion of a record does not constitute consent to contact that business or individual; obtaining required consents is solely the buyer's responsibility.
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
name: TradeDataHub Public API
provenance_date: '2026-11-10'
provider_name: TradeDataHub Public API
provider_slug: tradedatahub
slug: tradedatahub-eligibility
source_date: '2026-11-10'
source_filename: tradedatahub-eligibility.yml
source_heading: Eligibility
source_page: https://www.tradedatahub.net/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TradeDataHub Public API\naid: tradedatahub\nurl: https://www.tradedatahub.net/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Outreach compliance\n  text: Inclusion of a record does not constitute consent to contact that business or individual; obtaining required\n    consents is solely the buyer's responsibility.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tradedatahub/eligibility/tradedatahub-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from TradeDataHub Public API's own page on 2026-11-10.
synthetic: false
tags:
- contractor data
- B2B Data
- Business Listings
- Datasets
- CSV
- Lead Generation
- Sales Intelligence
- x402
- Agent-Native
- Llms.txt
- OpenAPI
---
