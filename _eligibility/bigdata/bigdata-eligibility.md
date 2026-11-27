---
api_specs:
- filename: bigdata-analyst-estimates-api-openapi.yml
  format: yaml
  label: RavenPack Analyst Estimates API
  slug: bigdata-analyst-estimates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigdata/openapi/bigdata-analyst-estimates-api-openapi.yml
- filename: bigdata-company-events-api-openapi.yml
  format: yaml
  label: RavenPack Company & Events API
  slug: bigdata-company-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigdata/openapi/bigdata-company-events-api-openapi.yml
- filename: bigdata-financials-ratios-api-openapi.yml
  format: yaml
  label: RavenPack Financials & Ratios API
  slug: bigdata-financials-ratios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigdata/openapi/bigdata-financials-ratios-api-openapi.yml
- filename: bigdata-fixed-income-api-openapi.yml
  format: yaml
  label: RavenPack Fixed Income API
  slug: bigdata-fixed-income-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigdata/openapi/bigdata-fixed-income-api-openapi.yml
- filename: bigdata-fund-holdings-api-openapi.yml
  format: yaml
  label: RavenPack Fund Holdings API
  slug: bigdata-fund-holdings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigdata/openapi/bigdata-fund-holdings-api-openapi.yml
- filename: bigdata-market-data-api-openapi.yml
  format: yaml
  label: RavenPack Market Data API
  slug: bigdata-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigdata/openapi/bigdata-market-data-api-openapi.yml
- filename: bigdata-private-markets-api-openapi.yml
  format: yaml
  label: RavenPack Private Markets API
  slug: bigdata-private-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigdata/openapi/bigdata-private-markets-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are a consumer resident in the European Economic Area or the United Kingdom, you would ordinarily have a right to withdraw from a purchase within fourteen (14) days without giving any reason.
  entity_types:
  - text: If you are registering or using the platform as an individual user
    type: individual
  - text: If you are registering or using the platform on behalf of a legal entity or company
    type: business
  minimum_age:
    text: You must be at least 18 years old to create an account with Bigdata.com and/or use its Services.
    value: '18'
  restricted_uses:
  - summary: Single natural person plan use
    text: use any plan purchased through the Bigdata.com website other than for the individual use of one natural person
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
name: RavenPack
provenance_date: '2026-11-09'
provider_name: RavenPack
provider_slug: bigdata
slug: bigdata-eligibility
source_date: '2026-11-09'
source_filename: bigdata-eligibility.yml
source_heading: Eligibility
source_page: https://bigdata.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RavenPack\naid: bigdata\nurl: https://bigdata.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are a consumer resident in the European Economic Area or the United Kingdom, you would ordinarily\n    have a right to withdraw from a purchase within fourteen (14) days without giving any reason.\nentity_types:\n- type: individual\n  text: If you are registering or using the platform as an individual user\n- type: business\n  text: If you are registering or using the platform on behalf of a legal entity or company\nrestricted_uses:\n- summary: Single natural\
  \ person plan use\n  text: use any plan purchased through the Bigdata.com website other than for the individual use of one natural\n    person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account with Bigdata.com and/or use its Services.\n"
source_yaml_url: https://artifacts.apis.io/bigdata/eligibility/bigdata-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from RavenPack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Artificial Intelligence
- Data Analytics
- Market Insights
---
