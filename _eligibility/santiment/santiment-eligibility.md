---
api_specs:
- filename: graphiql
  format: yaml
  label: SanAPI
  slug: sanapi
  spec_type: OpenAPI
  url: https://api.santiment.net/graphiql
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if You represent a corporation, governmental organization or other legal entity, You have the right, power and authority to enter into these T&C on behalf of such corporation
    type: business
  minimum_age:
    text: You are of legal age to enter into a binding agreement
    value: legal age
  restricted_uses:
  - summary: Jurisdictional legal restrictions
    text: You shall not use the Services if applicable laws, based on Your country of location, residency and/or citizenship, prohibit You from doing so
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
name: Santiment
provenance_date: '2026-11-10'
provider_name: Santiment
provider_slug: santiment
slug: santiment-eligibility
source_date: '2026-11-10'
source_filename: santiment-eligibility.yml
source_heading: Eligibility
source_page: https://santiment.net/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Santiment\naid: santiment\nurl: https://santiment.net/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if You represent a corporation, governmental organization or other legal entity, You have the right, power\n    and authority to enter into these T&C on behalf of such corporation\nrestricted_uses:\n- summary: Jurisdictional legal restrictions\n  text: You shall not use the Services if applicable laws, based on Your country of location, residency and/or citizenship,\n    prohibit You from doing so\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: You are of legal age to enter into a binding agreement\n"
source_yaml_url: https://artifacts.apis.io/santiment/eligibility/santiment-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Santiment's own page on 2026-11-10.
synthetic: false
tags:
- Cryptocurrency
- Blockchain
- Market Intelligence
- On-Chain Metrics
- Social Sentiment
- Developer Activity
- Analytics
- GraphQL
---
