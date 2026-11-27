---
api_specs:
- filename: compsniper-com-account-api-openapi.yml
  format: yaml
  label: compsniper-com Account API
  slug: compsniper-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-account-api-openapi.yml
- filename: compsniper-com-best-offer-prices-api-openapi.yml
  format: yaml
  label: compsniper-com Best Offer Prices API
  slug: compsniper-com-best-offer-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-best-offer-prices-api-openapi.yml
- filename: compsniper-com-bulk-search-api-openapi.yml
  format: yaml
  label: compsniper-com Bulk Search API
  slug: compsniper-com-bulk-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-bulk-search-api-openapi.yml
- filename: compsniper-com-cards-api-openapi.yml
  format: yaml
  label: compsniper-com Cards API
  slug: compsniper-com-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-cards-api-openapi.yml
- filename: compsniper-com-depop-api-openapi.yml
  format: yaml
  label: compsniper-com Depop API
  slug: compsniper-com-depop-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-depop-api-openapi.yml
- filename: compsniper-com-grailed-api-openapi.yml
  format: yaml
  label: compsniper-com Grailed API
  slug: compsniper-com-grailed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-grailed-api-openapi.yml
- filename: compsniper-com-mercari-api-openapi.yml
  format: yaml
  label: compsniper-com Mercari API
  slug: compsniper-com-mercari-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-mercari-api-openapi.yml
- filename: compsniper-com-poshmark-api-openapi.yml
  format: yaml
  label: compsniper-com Poshmark API
  slug: compsniper-com-poshmark-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-poshmark-api-openapi.yml
- filename: compsniper-com-psa-api-openapi.yml
  format: yaml
  label: compsniper-com PSA API
  slug: compsniper-com-psa-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-psa-api-openapi.yml
- filename: compsniper-com-scrape-api-openapi.yml
  format: yaml
  label: compsniper-com Scrape API
  slug: compsniper-com-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-scrape-api-openapi.yml
- filename: compsniper-com-shipping-rates-api-openapi.yml
  format: yaml
  label: compsniper-com Shipping Rates API
  slug: compsniper-com-shipping-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-shipping-rates-api-openapi.yml
- filename: compsniper-com-sold-history-api-openapi.yml
  format: yaml
  label: compsniper-com Sold history API
  slug: compsniper-com-sold-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-sold-history-api-openapi.yml
- filename: compsniper-com-summary-api-openapi.yml
  format: yaml
  label: compsniper-com Summary API
  slug: compsniper-com-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-summary-api-openapi.yml
- filename: compsniper-com-tcgplayer-api-openapi.yml
  format: yaml
  label: compsniper-com TC Gplayer API
  slug: compsniper-com-tcgplayer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-tcgplayer-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using CompSniper on behalf of a company, you represent that you have the authority to bind that company to these terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal, deceptive, or harmful products
    text: Use the service to build a product that is illegal, deceptive, or harmful.
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
name: compsniper-com
provenance_date: '2026-11-09'
provider_name: compsniper-com
provider_slug: compsniper-com
slug: compsniper-com-eligibility
source_date: '2026-11-09'
source_filename: compsniper-com-eligibility.yml
source_heading: Eligibility
source_page: https://compsniper.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: compsniper-com\naid: compsniper-com\nurl: https://compsniper.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using CompSniper on behalf of a company, you represent that you have the authority to bind that\n    company to these terms.\nrestricted_uses:\n- summary: Illegal, deceptive, or harmful products\n  text: Use the service to build a product that is illegal, deceptive, or harmful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/compsniper-com/eligibility/compsniper-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from compsniper-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- E-Commerce
- Data
- Collectibles
---
