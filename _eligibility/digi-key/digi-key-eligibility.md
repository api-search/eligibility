---
api_specs:
- filename: digi-key-barcoding-api-openapi.yml
  format: yaml
  label: Digi-Key Barcoding API
  slug: digi-key-barcoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digi-key/openapi/digi-key-barcoding-api-openapi.yml
- filename: digi-key-bondedinventory-api-openapi.yml
  format: yaml
  label: Digi-Key Bonded Inventory API
  slug: digi-key-bondedinventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digi-key/openapi/digi-key-bondedinventory-api-openapi.yml
- filename: digi-key-customerresource-api-openapi.yml
  format: yaml
  label: Digi-Key Customer Resource API
  slug: digi-key-customerresource-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digi-key/openapi/digi-key-customerresource-api-openapi.yml
- filename: digi-key-lists-api-openapi.yml
  format: yaml
  label: Digi-Key Lists API
  slug: digi-key-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digi-key/openapi/digi-key-lists-api-openapi.yml
- filename: digi-key-orderhistory-api-openapi.yml
  format: yaml
  label: Digi-Key Order History API
  slug: digi-key-orderhistory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digi-key/openapi/digi-key-orderhistory-api-openapi.yml
- filename: digi-key-ordermanagement-api-openapi.yml
  format: yaml
  label: Digi-Key Order Management API
  slug: digi-key-ordermanagement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digi-key/openapi/digi-key-ordermanagement-api-openapi.yml
- filename: digi-key-orders-api-openapi.yml
  format: yaml
  label: Digi-Key Orders API
  slug: digi-key-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digi-key/openapi/digi-key-orders-api-openapi.yml
- filename: digi-key-packlist-api-openapi.yml
  format: yaml
  label: Digi-Key Pack List API
  slug: digi-key-packlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digi-key/openapi/digi-key-packlist-api-openapi.yml
- filename: digi-key-parts-api-openapi.yml
  format: yaml
  label: Digi-Key Parts API
  slug: digi-key-parts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digi-key/openapi/digi-key-parts-api-openapi.yml
- filename: digi-key-pcn-api-openapi.yml
  format: yaml
  label: Digi-Key Pcn API
  slug: digi-key-pcn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digi-key/openapi/digi-key-pcn-api-openapi.yml
- filename: digi-key-quotes-api-openapi.yml
  format: yaml
  label: Digi-Key Quotes API
  slug: digi-key-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digi-key/openapi/digi-key-quotes-api-openapi.yml
- filename: digi-key-product-search-api-openapi.yml
  format: yaml
  label: Digi-Key Product Search API
  slug: digi-key-product-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digi-key/openapi/digi-key-product-search-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you (a) agree on your own behalf personally
    type: individual
  - text: on behalf of any entity for which you work or you appear to represent
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use for DigiKey competitors
    text: (i) use the API for the benefit of any DigiKey competitors
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: To obtain access to an enhanced-access feed API, you must email api.contact@digikey.com to request such access.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Digi-Key
provenance_date: '2026-11-09'
provider_name: Digi-Key
provider_slug: digi-key
slug: digi-key-eligibility
source_date: '2026-11-09'
source_filename: digi-key-eligibility.yml
source_heading: Eligibility
source_page: https://developer.digikey.com/api-user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Digi-Key\naid: digi-key\nurl: https://developer.digikey.com/api-user-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you (a) agree on your own behalf personally\n- type: business\n  text: on behalf of any entity for which you work or you appear to represent\nrestricted_uses:\n- summary: Use for DigiKey competitors\n  text: (i) use the API for the benefit of any DigiKey competitors\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: To obtain access to an enhanced-access feed API, you must email api.contact@digikey.com\
  \ to request such\n    access.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/digi-key/eligibility/digi-key-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Digi-Key's own page on 2026-11-09.
synthetic: false
tags:
- Shopping
- Public APIs
- Electronic Components
- Distribution
- Ordering
- Product Search
- Pricing
- Inventory
- Supply Chain
---
