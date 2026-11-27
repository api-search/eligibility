---
api_specs:
- filename: soldgraph-com-account-api-openapi.yml
  format: yaml
  label: soldgraph-com Account API
  slug: soldgraph-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldgraph-com/openapi/soldgraph-com-account-api-openapi.yml
- filename: soldgraph-com-batches-api-openapi.yml
  format: yaml
  label: soldgraph-com Batches API
  slug: soldgraph-com-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldgraph-com/openapi/soldgraph-com-batches-api-openapi.yml
- filename: soldgraph-com-depop-api-openapi.yml
  format: yaml
  label: soldgraph-com Depop API
  slug: soldgraph-com-depop-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldgraph-com/openapi/soldgraph-com-depop-api-openapi.yml
- filename: soldgraph-com-ebay-api-openapi.yml
  format: yaml
  label: soldgraph-com eBay API
  slug: soldgraph-com-ebay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldgraph-com/openapi/soldgraph-com-ebay-api-openapi.yml
- filename: soldgraph-com-facebook-marketplace-api-openapi.yml
  format: yaml
  label: soldgraph-com Facebook Marketplace API
  slug: soldgraph-com-facebook-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldgraph-com/openapi/soldgraph-com-facebook-marketplace-api-openapi.yml
- filename: soldgraph-com-jobs-api-openapi.yml
  format: yaml
  label: soldgraph-com Jobs API
  slug: soldgraph-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldgraph-com/openapi/soldgraph-com-jobs-api-openapi.yml
- filename: soldgraph-com-mercari-api-openapi.yml
  format: yaml
  label: soldgraph-com Mercari API
  slug: soldgraph-com-mercari-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldgraph-com/openapi/soldgraph-com-mercari-api-openapi.yml
- filename: soldgraph-com-offerup-api-openapi.yml
  format: yaml
  label: soldgraph-com Offer Up API
  slug: soldgraph-com-offerup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldgraph-com/openapi/soldgraph-com-offerup-api-openapi.yml
- filename: soldgraph-com-poshmark-api-openapi.yml
  format: yaml
  label: soldgraph-com Poshmark API
  slug: soldgraph-com-poshmark-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldgraph-com/openapi/soldgraph-com-poshmark-api-openapi.yml
- filename: soldgraph-com-tcgplayer-api-openapi.yml
  format: yaml
  label: soldgraph-com TC Gplayer API
  slug: soldgraph-com-tcgplayer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldgraph-com/openapi/soldgraph-com-tcgplayer-api-openapi.yml
- filename: soldgraph-com-vinted-api-openapi.yml
  format: yaml
  label: soldgraph-com Vinted API
  slug: soldgraph-com-vinted-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldgraph-com/openapi/soldgraph-com-vinted-api-openapi.yml
- filename: soldgraph-com-whatnot-api-openapi.yml
  format: yaml
  label: soldgraph-com Whatnot API
  slug: soldgraph-com-whatnot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldgraph-com/openapi/soldgraph-com-whatnot-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18.
    type: individual
  - text: If you use Soldgraph for a company, you agree on its behalf.
    type: business
  minimum_age:
    text: You must be at least 18.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: Use the service or its data to break the law, to harass or harm anyone, or to violate anyone's rights.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Give us a real, permanent email address and keep it current.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: soldgraph-com
provenance_date: '2026-11-10'
provider_name: soldgraph-com
provider_slug: soldgraph-com
slug: soldgraph-com-eligibility
source_date: '2026-11-10'
source_filename: soldgraph-com-eligibility.yml
source_heading: Eligibility
source_page: https://soldgraph.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: soldgraph-com\naid: soldgraph-com\nurl: https://soldgraph.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18.\n- type: business\n  text: If you use Soldgraph for a company, you agree on its behalf.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: Use the service or its data to break the law, to harass or harm anyone, or to violate anyone's rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Give us a real, permanent email address and keep it current.\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18.\n"
source_yaml_url: https://artifacts.apis.io/soldgraph-com/eligibility/soldgraph-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from soldgraph-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Resale
- Marketplace
- Pricing
- Data
---
