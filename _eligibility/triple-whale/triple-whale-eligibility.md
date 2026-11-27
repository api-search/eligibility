---
api_specs:
- filename: triple-whale-api-keys-api-openapi.yml
  format: yaml
  label: Triple Whale API Keys API
  slug: triple-whale-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/triple-whale/openapi/triple-whale-api-keys-api-openapi.yml
- filename: triple-whale-compliance-api-openapi.yml
  format: yaml
  label: Triple Whale Compliance API
  slug: triple-whale-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/triple-whale/openapi/triple-whale-compliance-api-openapi.yml
- filename: triple-whale-data-in-api-openapi.yml
  format: yaml
  label: Triple Whale Data In API
  slug: triple-whale-data-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/triple-whale/openapi/triple-whale-data-in-api-openapi.yml
- filename: triple-whale-data-out-api-openapi.yml
  format: yaml
  label: Triple Whale Data Out API
  slug: triple-whale-data-out-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/triple-whale/openapi/triple-whale-data-out-api-openapi.yml
- filename: triple-whale-bi-api-openapi.yml
  format: yaml
  label: Triple Whale Bi API
  slug: triple-whale-bi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/triple-whale/openapi/triple-whale-bi-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise explicitly stated, all materials found on the Site are solely directed to individuals, companies, or other entities located in the United States.
  entity_types:
  - text: If you are using the Site for commercial purposes, each party will be responsible for paying any JAMS filing, administrative and arbitrator fees
    type: business
  - text: If you are an individual using the Site for non-commercial purposes
    type: individual
  minimum_age:
    text: Any use or access to the Site by anyone under 13 is strictly prohibited and in violation of this Agreement.
    value: '13'
  restricted_uses:
  - summary: Use by under-13s prohibited
    text: Any use or access to the Site by anyone under 13 is strictly prohibited and in violation of this Agreement.
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
name: Triple Whale
provenance_date: '2026-11-10'
provider_name: Triple Whale
provider_slug: triple-whale
slug: triple-whale-eligibility
source_date: '2026-11-10'
source_filename: triple-whale-eligibility.yml
source_heading: Eligibility
source_page: https://www.triplewhale.com/pages/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Triple Whale\naid: triple-whale\nurl: https://www.triplewhale.com/pages/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise explicitly stated, all materials found on the Site are solely directed to individuals,\n    companies, or other entities located in the United States.\nentity_types:\n- type: business\n  text: If you are using the Site for commercial purposes, each party will be responsible for paying any JAMS filing,\n    administrative and arbitrator fees\n- type: individual\n  text: If you are an individual using the Site for non-commercial\
  \ purposes\nrestricted_uses:\n- summary: Use by under-13s prohibited\n  text: Any use or access to the Site by anyone under 13 is strictly prohibited and in violation of this Agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any use or access to the Site by anyone under 13 is strictly prohibited and in violation of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/triple-whale/eligibility/triple-whale-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Triple Whale's own page on 2026-11-10.
synthetic: false
tags:
- E-Commerce
- Analytics
- Attribution
- Shopify
- Pixel Tracking
- ROAS
- Direct to Consumer
- Marketing
---
