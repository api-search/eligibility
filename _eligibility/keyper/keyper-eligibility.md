---
api_specs:
- filename: keyper-permissions-api-openapi.yml
  format: yaml
  label: Keyper Permissions API
  slug: keyper-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keyper/openapi/keyper-permissions-api-openapi.yml
- filename: keyper-transactions-api-openapi.yml
  format: yaml
  label: Keyper Transactions API
  slug: keyper-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keyper/openapi/keyper-transactions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Veranstalter oder autorisierten Ticketing-Dienstleister (Anbieter)
    type: other
  minimum_age:
    text: keyper stellt seine Services nur volljährigen Personen zur Verfügung, die das 18. Lebensjahr vollendet haben.
    value: '18'
  restricted_uses:
  - summary: Lotteries, games and prize contests
    text: Glücksspiele, Spiele, Lotterien, Verlosungen, Wettbewerbe, Gewinnspiele und/oder andere Aktivitäten, für die Preise vergeben werden, zu ermöglichen
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: keyper behält sich vor, das Angebot des Anbieters ohne Angaben von Gründen nicht anzunehmen.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Keyper
provenance_date: '2026-11-09'
provider_name: Keyper
provider_slug: keyper
slug: keyper-eligibility
source_date: '2026-11-09'
source_filename: keyper-eligibility.yml
source_heading: Eligibility
source_page: https://www.keyper.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Keyper\naid: keyper\nurl: https://www.keyper.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: Veranstalter oder autorisierten Ticketing-Dienstleister (Anbieter)\nrestricted_uses:\n- summary: Lotteries, games and prize contests\n  text: Glücksspiele, Spiele, Lotterien, Verlosungen, Wettbewerbe, Gewinnspiele und/oder andere Aktivitäten, für\n    die Preise vergeben werden, zu ermöglichen\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: keyper behält sich vor, das Angebot des Anbieters ohne\
  \ Angaben von Gründen nicht anzunehmen.\nminimum_age:\n  value: '18'\n  text: keyper stellt seine Services nur volljährigen Personen zur Verfügung, die das 18. Lebensjahr vollendet haben.\n"
source_yaml_url: https://artifacts.apis.io/keyper/eligibility/keyper-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Keyper's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ticketing
- Access Control
- Event
- Developer Platform
- SDK
- Sports
- Arts and Culture
- Austria
---
