---
api_specs:
- filename: gitcoin-bounties-api-openapi.yml
  format: yaml
  label: Gitcoin Bounties API
  slug: gitcoin-bounties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitcoin/openapi/gitcoin-bounties-api-openapi.yml
- filename: gitcoin-contributors-api-openapi.yml
  format: yaml
  label: Gitcoin Contributors API
  slug: gitcoin-contributors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitcoin/openapi/gitcoin-contributors-api-openapi.yml
- filename: gitcoin-grants-api-openapi.yml
  format: yaml
  label: Gitcoin Grants API
  slug: gitcoin-grants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitcoin/openapi/gitcoin-grants-api-openapi.yml
- filename: gitcoin-model-analysis-api-openapi.yml
  format: yaml
  label: Gitcoin Model Analysis API
  slug: gitcoin-model-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitcoin/openapi/gitcoin-model-analysis-api-openapi.yml
- filename: gitcoin-stamp-api-api-openapi.yml
  format: yaml
  label: Gitcoin Stamp API
  slug: gitcoin-stamp-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitcoin/openapi/gitcoin-stamp-api-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not ... a citizen, resident, or organized in a jurisdiction or territory that is the subject of comprehensive country-wide, territory-wide, or regional economic sanctions by the United States.
  entity_types:
  - text: are of legal age to form a binding contract
    type: individual
  - text: If you are registering to use the Services on behalf of a legal entity
    type: business
  minimum_age:
    text: are of legal age to form a binding contract; (e.g., 18 years old in the United States)
    value: legal age
  restricted_uses:
  - summary: Illegal activity
    text: you will not access or use any of our Products to conduct, promote, or otherwise facilitate any illegal activity.
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
name: Gitcoin
provenance_date: '2026-11-09'
provider_name: Gitcoin
provider_slug: gitcoin
slug: gitcoin-eligibility
source_date: '2026-11-09'
source_filename: gitcoin-eligibility.yml
source_heading: Eligibility
source_page: https://gitcoin.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gitcoin\naid: gitcoin\nurl: https://gitcoin.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not ... a citizen, resident, or organized in a jurisdiction or territory that\n    is the subject of comprehensive country-wide, territory-wide, or regional economic sanctions by the United States.\nentity_types:\n- type: individual\n  text: are of legal age to form a binding contract\n- type: business\n  text: If you are registering to use the Services on behalf of a legal entity\nrestricted_uses:\n- summary: Illegal activity\n  text: you will not access\
  \ or use any of our Products to conduct, promote, or otherwise facilitate any illegal\n    activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: are of legal age to form a binding contract; (e.g., 18 years old in the United States)\n"
source_yaml_url: https://artifacts.apis.io/gitcoin/eligibility/gitcoin-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Gitcoin's own page on 2026-11-09.
synthetic: false
tags:
- Public Goods
- Grants
- Bounties
- Quadratic Funding
- Web3
- Verifiable Credentials
- Identity
- Open Source
---
