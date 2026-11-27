---
api_specs:
- filename: h1-cost-estimates-api-openapi.yml
  format: yaml
  label: H1 Cost Estimates API
  slug: h1-insights-cost-estimates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h1/openapi/h1-cost-estimates-api-openapi.yml
- filename: h1-filters-api-openapi.yml
  format: yaml
  label: H1 Filters API
  slug: h1-insights-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h1/openapi/h1-filters-api-openapi.yml
- filename: h1-focus-area-endpoints-api-openapi.yml
  format: yaml
  label: H1 Focus Area Endpoints API
  slug: h1-insights-focus-area-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h1/openapi/h1-focus-area-endpoints-api-openapi.yml
- filename: h1-locations-api-openapi.yml
  format: yaml
  label: H1 Locations API
  slug: h1-insights-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h1/openapi/h1-locations-api-openapi.yml
- filename: h1-networks-api-openapi.yml
  format: yaml
  label: H1 Networks API
  slug: h1-insights-networks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h1/openapi/h1-networks-api-openapi.yml
- filename: h1-organizations-api-openapi.yml
  format: yaml
  label: H1 Organizations API
  slug: h1-insights-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h1/openapi/h1-organizations-api-openapi.yml
- filename: h1-price-transparency-api-openapi.yml
  format: yaml
  label: H1 Price Transparency API
  slug: h1-insights-price-transparency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h1/openapi/h1-price-transparency-api-openapi.yml
- filename: h1-providers-api-openapi.yml
  format: yaml
  label: H1 Providers API
  slug: h1-insights-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h1/openapi/h1-providers-api-openapi.yml
- filename: h1-reference-endpoints-api-openapi.yml
  format: yaml
  label: H1 Reference Endpoints API
  slug: h1-insights-reference-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h1/openapi/h1-reference-endpoints-api-openapi.yml
- filename: h1-tins-api-openapi.yml
  format: yaml
  label: H1 TI Ns API
  slug: h1-insights-tins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h1/openapi/h1-tins-api-openapi.yml
- filename: h1-virtual-care-platforms-api-openapi.yml
  format: yaml
  label: H1 Virtual Care Platforms API
  slug: h1-insights-virtual-care-platforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h1/openapi/h1-virtual-care-platforms-api-openapi.yml
- filename: h1-price-transparency-v2-api-openapi.yml
  format: yaml
  label: H1 Price Transparency v2 API
  slug: h1-price-transparency-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h1/openapi/h1-price-transparency-v2-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: when H1 creates an account for you or your Company
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: You will not use any Site or its content for any unlawful purpose;
  - summary: Spam or harassing content
    text: You will not use any Site to disseminate spam or any harassing, abusive, threatening, vulgar, obscene, or other illegal information;
  - source: https://h1.com/terms-of-use/
    summary: Spam and harassment
    text: You will not use any Site to disseminate spam or any harassing, abusive, threatening, vulgar, obscene, or other illegal information;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    source: https://h1.com/terms-of-use/
    text: As a condition to using any Site, you must provide accurate personal information when H1 creates an account for you or your Company, and update any changes over time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: H1
provenance_date: '2026-11-09'
provider_name: H1
provider_slug: h1
slug: h1-eligibility
source_date: '2026-11-09'
source_filename: h1-eligibility.yml
source_heading: Eligibility
source_page: https://h1.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: H1\naid: h1\nurl: https://h1.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://h1.com/terms-of-use/\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: when H1 creates an account for you or your Company\nrestricted_uses:\n- summary: Unlawful use\n  text: You will not use any Site or its content for any unlawful purpose;\n- summary: Spam or harassing content\n  text: You will not use any Site to disseminate spam or any harassing, abusive, threatening, vulgar, obscene, or\n    other illegal information;\n- summary: Spam and harassment\n  text: You\
  \ will not use any Site to disseminate spam or any harassing, abusive, threatening, vulgar, obscene, or\n    other illegal information;\n  source: https://h1.com/terms-of-use/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As a condition to using any Site, you must provide accurate personal information when H1 creates an account\n    for you or your Company, and update any changes over time.\n  source: https://h1.com/terms-of-use/\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/h1/eligibility/h1-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from H1's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- United States
- Life Sciences
- Provider Data
- Healthcare API
- Price Transparency
- Eligibility
- Network Intelligence
- Digital Health
- Pharma
---
