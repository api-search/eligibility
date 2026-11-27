---
api_specs:
- filename: epsilon-ads-api-openapi.yml
  format: yaml
  label: Epsilon Ads API
  slug: epsilon-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epsilon/openapi/epsilon-ads-api-openapi.yml
- filename: epsilon-catalog-products-api-openapi.yml
  format: yaml
  label: Epsilon Catalog Products API
  slug: epsilon-catalog-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epsilon/openapi/epsilon-catalog-products-api-openapi.yml
- filename: epsilon-catalogs-api-openapi.yml
  format: yaml
  label: Epsilon Catalogs API
  slug: epsilon-catalogs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epsilon/openapi/epsilon-catalogs-api-openapi.yml
- filename: epsilon-crosssellcategory-api-openapi.yml
  format: yaml
  label: Epsilon Cross Sell Category API
  slug: epsilon-crosssellcategory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epsilon/openapi/epsilon-crosssellcategory-api-openapi.yml
- filename: epsilon-customers-api-openapi.yml
  format: yaml
  label: Epsilon Customers API
  slug: epsilon-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epsilon/openapi/epsilon-customers-api-openapi.yml
- filename: epsilon-filtermapping-api-openapi.yml
  format: yaml
  label: Epsilon Filter Mapping API
  slug: epsilon-filtermapping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epsilon/openapi/epsilon-filtermapping-api-openapi.yml
- filename: epsilon-orders-api-openapi.yml
  format: yaml
  label: Epsilon Orders API
  slug: epsilon-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epsilon/openapi/epsilon-orders-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Epsilon provides this Site for use only by persons located in the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful content
    text: You are prohibited from posting or transmitting any unlawful, threatening, libelous, defamatory, obscene, indecent, inflammatory, pornographic or profane material
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
name: Epsilon
provenance_date: '2026-11-09'
provider_name: Epsilon
provider_slug: epsilon
slug: epsilon-eligibility
source_date: '2026-11-09'
source_filename: epsilon-eligibility.yml
source_heading: Eligibility
source_page: https://legal.epsilon.com/us/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Epsilon\naid: epsilon\nurl: https://legal.epsilon.com/us/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Epsilon provides this Site for use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: You are prohibited from posting or transmitting any unlawful, threatening, libelous, defamatory, obscene,\n    indecent, inflammatory, pornographic or profane material\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/epsilon/eligibility/epsilon-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Epsilon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketing
- Advertising
- Retail Media
- AdTech
- Identity Resolution
- Customer Data
- Loyalty
- Retail
- Publicis Groupe
---
