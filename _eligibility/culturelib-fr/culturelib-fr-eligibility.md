---
api_specs:
- filename: culturelib-fr-openapi-generated.yml
  format: yaml
  label: CultureLib Discover API
  slug: culturelib-discover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culturelib-fr/openapi/_ae-authored/culturelib-fr-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: un espace salariés réservé aux employés des entreprises clientes, qui permet d'utiliser des crédits culture financés par l'employeur
    type: individual
  minimum_age:
    text: null
    value: null
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
name: CultureLib
provenance_date: '2026-11-09'
provider_name: CultureLib
provider_slug: culturelib-fr
slug: culturelib-fr-eligibility
source_date: '2026-11-09'
source_filename: culturelib-fr-eligibility.yml
source_heading: Eligibility
source_page: https://www.culturelib.fr/cgu
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CultureLib\naid: culturelib-fr\nurl: https://www.culturelib.fr/cgu\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: un espace salariés réservé aux employés des entreprises clientes, qui permet d'utiliser des crédits culture\n    financés par l'employeur\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/culturelib-fr/eligibility/culturelib-fr-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from CultureLib's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Culture
- Event
- Ticketing
- Employee Benefits
- France
- MCP
- Entertainment
---
