---
api_specs:
- filename: crawlerdata-com-custom-search-compatible-api-openapi.yml
  format: yaml
  label: crawlerdata-com Custom Search-compatible API
  slug: crawlerdata-com-custom-search-compatible-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawlerdata-com/openapi/crawlerdata-com-custom-search-compatible-api-openapi.yml
- filename: crawlerdata-com-jobs-api-openapi.yml
  format: yaml
  label: crawlerdata-com Jobs API
  slug: crawlerdata-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawlerdata-com/openapi/crawlerdata-com-jobs-api-openapi.yml
- filename: crawlerdata-com-open-webui-api-openapi.yml
  format: yaml
  label: crawlerdata-com Open WebUI API
  slug: crawlerdata-com-open-webui-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawlerdata-com/openapi/crawlerdata-com-open-webui-api-openapi.yml
- filename: crawlerdata-com-serpapi-compatible-api-openapi.yml
  format: yaml
  label: crawlerdata-com Serp API Compatible API
  slug: crawlerdata-com-serpapi-compatible-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawlerdata-com/openapi/crawlerdata-com-serpapi-compatible-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You confirm that you are not located, organized or ordinarily resident in a country or region subject to comprehensive sanctions
  entity_types:
  - text: The Service is for businesses only.
    type: business
  - text: You must be at least 18 years old and able to enter into a binding contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No automated account creation
    text: You may not create Accounts by automated means
  - summary: No targeting of sensitive or children's data
    text: You confirm that you will not use the Service to target special categories of personal data (such as health, religion, sexual orientation or political opinions) or data about children
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: At any time we may ask you to verify your identity, your company and your intended use of the Service
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: crawlerdata-com
provenance_date: '2026-11-09'
provider_name: crawlerdata-com
provider_slug: crawlerdata-com
slug: crawlerdata-com-eligibility
source_date: '2026-11-09'
source_filename: crawlerdata-com-eligibility.yml
source_heading: Eligibility
source_page: https://crawlerdata.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: crawlerdata-com\naid: crawlerdata-com\nurl: https://crawlerdata.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You confirm that you are not located, organized or ordinarily resident in a country or region subject to\n    comprehensive sanctions\nentity_types:\n- type: business\n  text: The Service is for businesses only.\n- type: individual\n  text: You must be at least 18 years old and able to enter into a binding contract.\nrestricted_uses:\n- summary: No automated account creation\n  text: You may not create Accounts by automated means\n- summary: No targeting\
  \ of sensitive or children's data\n  text: You confirm that you will not use the Service to target special categories of personal data (such as health,\n    religion, sexual orientation or political opinions) or data about children\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: At any time we may ask you to verify your identity, your company and your intended use of the Service\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/crawlerdata-com/eligibility/crawlerdata-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from crawlerdata-com's own page on 2026-11-09.
synthetic: false
tags:
- Search
- Google
- SERP
- Data
- E-Commerce
- SEO
---
