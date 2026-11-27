---
api_specs:
- filename: bitcoinyield-offers-api-openapi.yml
  format: yaml
  label: BitcoinYield Offers API
  slug: bitcoinyield-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitcoinyield/openapi/bitcoinyield-offers-api-openapi.yml
- filename: bitcoinyield-prices-api-openapi.yml
  format: yaml
  label: BitcoinYield Prices API
  slug: bitcoinyield-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitcoinyield/openapi/bitcoinyield-prices-api-openapi.yml
- filename: bitcoinyield-yields-api-openapi.yml
  format: yaml
  label: BitcoinYield Yields API
  slug: bitcoinyield-yields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitcoinyield/openapi/bitcoinyield-yields-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Service only if you can form a legally binding contract with us
    type: individual
  - text: If you use the Service on behalf of a company or other organization, you represent that you have authority to bind that entity to these Terms, and in that case "you" refers to that entity.
    type: business
  minimum_age:
    text: You may use it only if you meet the minimum age required to consent to the processing of your personal data in your country, or the age of majority where that is higher.
    value: minimum consent age or age of majority
  restricted_uses:
  - summary: Investment advice presentation
    text: do not present our risk grades or rankings as your own, or as investment advice from us
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
name: BitcoinYield
provenance_date: '2026-11-09'
provider_name: BitcoinYield
provider_slug: bitcoinyield
slug: bitcoinyield-eligibility
source_date: '2026-11-09'
source_filename: bitcoinyield-eligibility.yml
source_heading: Eligibility
source_page: https://bitcoinyield.co/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BitcoinYield\naid: bitcoinyield\nurl: https://bitcoinyield.co/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Service only if you can form a legally binding contract with us\n- type: business\n  text: If you use the Service on behalf of a company or other organization, you represent that you have authority\n    to bind that entity to these Terms, and in that case \"you\" refers to that entity.\nrestricted_uses:\n- summary: Investment advice presentation\n  text: do not present our risk grades or rankings\
  \ as your own, or as investment advice from us\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: minimum consent age or age of majority\n  text: You may use it only if you meet the minimum age required to consent to the processing of your personal data\n    in your country, or the age of majority where that is higher.\n"
source_yaml_url: https://artifacts.apis.io/bitcoinyield/eligibility/bitcoinyield-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BitcoinYield's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Yield
- Finance
---
