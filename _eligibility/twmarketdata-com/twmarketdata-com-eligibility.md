---
api_specs:
- filename: twmarketdata-com-capital-flow-api-openapi.yml
  format: yaml
  label: twmarketdata-com Capital Flow API
  slug: twmarketdata-com-capital-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twmarketdata-com/openapi/twmarketdata-com-capital-flow-api-openapi.yml
- filename: twmarketdata-com-datasets-api-openapi.yml
  format: yaml
  label: twmarketdata-com Datasets API
  slug: twmarketdata-com-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twmarketdata-com/openapi/twmarketdata-com-datasets-api-openapi.yml
- filename: twmarketdata-com-fundamentals-api-openapi.yml
  format: yaml
  label: twmarketdata-com Fundamentals API
  slug: twmarketdata-com-fundamentals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twmarketdata-com/openapi/twmarketdata-com-fundamentals-api-openapi.yml
- filename: twmarketdata-com-market-prices-api-openapi.yml
  format: yaml
  label: twmarketdata-com Market Prices API
  slug: twmarketdata-com-market-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twmarketdata-com/openapi/twmarketdata-com-market-prices-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are contracting on behalf of an organisation, you represent that you have authority to bind that organisation to them
    type: business
  minimum_age:
    text: You must be of an age at which you can enter into a binding contract in your jurisdiction in order to use the Services.
    value: null
  restricted_uses:
  - summary: Acceptable Use Policy
    text: Your use of the Services is subject to the Acceptable Use Policy, which is incorporated into these Terms. A breach of that policy is a material breach of these Terms.
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
name: twmarketdata-com
provenance_date: '2026-11-10'
provider_name: twmarketdata-com
provider_slug: twmarketdata-com
slug: twmarketdata-com-eligibility
source_date: '2026-11-10'
source_filename: twmarketdata-com-eligibility.yml
source_heading: Eligibility
source_page: https://twmarketdata.com/en/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: twmarketdata-com\naid: twmarketdata-com\nurl: https://twmarketdata.com/en/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you are contracting on behalf of an organisation, you represent that you have authority to bind that\n    organisation to them\nrestricted_uses:\n- summary: Acceptable Use Policy\n  text: Your use of the Services is subject to the Acceptable Use Policy, which is incorporated into these Terms.\n    A breach of that policy is a material breach of these Terms.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be of an age at which you can enter into a binding contract in your jurisdiction in order to use\n    the Services.\n"
source_yaml_url: https://artifacts.apis.io/twmarketdata-com/eligibility/twmarketdata-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from twmarketdata-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Market Data
- Taiwan
---
