---
api_specs:
- filename: crela-io-openapi-generated.yml
  format: yaml
  label: Crela API
  slug: crela-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crela-io/openapi/_ae-authored/crela-io-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: § 16 Additional Terms for Certain Countries (Australia, United Kingdom, Canada, California). § 17 excludes persons in countries or regions subject to comprehensive EU sanctions.
  entity_types:
  - text: Consumers within the meaning of § 13 BGB have a statutory right of withdrawal.
    type: individual
  - text: The right of withdrawal does not exist for contracts with entrepreneurs (B2B).
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: 'The Buyer shall not use the tools to: violate applicable law; infringe third-party rights; impair Crela''s platform infrastructure.'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Purchases require a Crela user account. The Buyer is obligated to provide truthful information and to keep credentials confidential.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Crela
provenance_date: '2026-11-09'
provider_name: Crela
provider_slug: crela-io
slug: crela-io-eligibility
source_date: '2026-11-09'
source_filename: crela-io-eligibility.yml
source_heading: Eligibility
source_page: https://crela.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crela\naid: crela-io\nurl: https://crela.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: § 16 Additional Terms for Certain Countries (Australia, United Kingdom, Canada, California). § 17 excludes\n    persons in countries or regions subject to comprehensive EU sanctions.\nentity_types:\n- type: individual\n  text: Consumers within the meaning of § 13 BGB have a statutory right of withdrawal.\n- type: business\n  text: The right of withdrawal does not exist for contracts with entrepreneurs (B2B).\nrestricted_uses:\n- summary: Lawful use only\n  text: 'The Buyer shall not\
  \ use the tools to: violate applicable law; infringe third-party rights; impair Crela''s\n    platform infrastructure.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Purchases require a Crela user account. The Buyer is obligated to provide truthful information and to keep\n    credentials confidential.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/crela-io/eligibility/crela-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Crela's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software Marketplace
- Desktop Software
- Independent Creators
- Software Distribution
- Security Review
- MCP
- REST API
---
