---
api_specs:
- filename: mikmak-authentication-api-openapi.yml
  format: yaml
  label: MikMak Authentication API
  slug: mikmak-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mikmak/openapi/mikmak-authentication-api-openapi.yml
- filename: mikmak-availabilities-api-openapi.yml
  format: yaml
  label: MikMak Availabilities API
  slug: mikmak-availabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mikmak/openapi/mikmak-availabilities-api-openapi.yml
- filename: mikmak-cart-api-openapi.yml
  format: yaml
  label: MikMak Cart API
  slug: mikmak-cart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mikmak/openapi/mikmak-cart-api-openapi.yml
- filename: mikmak-custom-reports-api-openapi.yml
  format: yaml
  label: MikMak Custom Reports API
  slug: mikmak-custom-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mikmak/openapi/mikmak-custom-reports-api-openapi.yml
- filename: mikmak-experiences-api-openapi.yml
  format: yaml
  label: MikMak Experiences API
  slug: mikmak-experiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mikmak/openapi/mikmak-experiences-api-openapi.yml
- filename: mikmak-facet-api-openapi.yml
  format: yaml
  label: MikMak Facet API
  slug: mikmak-facet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mikmak/openapi/mikmak-facet-api-openapi.yml
- filename: mikmak-historical-pricing-reports-api-openapi.yml
  format: yaml
  label: MikMak Historical Pricing Reports API
  slug: mikmak-historical-pricing-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mikmak/openapi/mikmak-historical-pricing-reports-api-openapi.yml
- filename: mikmak-offers-api-openapi.yml
  format: yaml
  label: MikMak Offers API
  slug: mikmak-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mikmak/openapi/mikmak-offers-api-openapi.yml
- filename: mikmak-product-api-openapi.yml
  format: yaml
  label: MikMak Product API
  slug: mikmak-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mikmak/openapi/mikmak-product-api-openapi.yml
- filename: mikmak-product-search-api-openapi.yml
  format: yaml
  label: MikMak Product Search API
  slug: mikmak-product-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mikmak/openapi/mikmak-product-search-api-openapi.yml
- filename: mikmak-shoppable-recipe-reports-api-openapi.yml
  format: yaml
  label: MikMak Shoppable Recipe Reports API
  slug: mikmak-shoppable-recipe-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mikmak/openapi/mikmak-shoppable-recipe-reports-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: “Territory” means the United States unless otherwise set forth in an applicable Order Form.
  entity_types:
  - text: the individual, company, or other legal entity named as a customer in the Order Form (“Customer”)
    type: business
  minimum_age:
    text: null
    value: null
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
name: MikMak
provenance_date: '2026-11-10'
provider_name: MikMak
provider_slug: mikmak
slug: mikmak-eligibility
source_date: '2026-11-10'
source_filename: mikmak-eligibility.yml
source_heading: Eligibility
source_page: https://www.mikmak.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MikMak\naid: mikmak\nurl: https://www.mikmak.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: “Territory” means the United States unless otherwise set forth in an applicable Order Form.\nentity_types:\n- type: business\n  text: the individual, company, or other legal entity named as a customer in the Order Form (“Customer”)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mikmak/eligibility/mikmak-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from MikMak's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Commerce
- E-Commerce
- Multi-Channel
- Retail Media
- Where to Buy
- Shoppable Media
- Product Availability
- MCP
- Agent-Native
- Reporting
- Consumer Packaged Goods
---
