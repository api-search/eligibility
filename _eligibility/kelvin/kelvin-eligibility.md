---
api_specs:
- filename: kelvin-documents-api-openapi.yml
  format: yaml
  label: Kelvin Documents API
  slug: kelvin-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kelvin/openapi/kelvin-documents-api-openapi.yml
- filename: kelvin-qualification-api-openapi.yml
  format: yaml
  label: Kelvin Qualification API
  slug: kelvin-qualification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kelvin/openapi/kelvin-qualification-api-openapi.yml
- filename: kelvin-simulateur-api-openapi.yml
  format: yaml
  label: Kelvin Simulateur API
  slug: kelvin-simulateur-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kelvin/openapi/kelvin-simulateur-api-openapi.yml
- filename: kelvin-simulations-api-openapi.yml
  format: yaml
  label: Kelvin Simulations API
  slug: kelvin-simulations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kelvin/openapi/kelvin-simulations-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: la personne physique ou morale qui s’engage auprès de KELVIN pour ses propres besoins professionnels
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use contrary to applicable regulation
    text: l’utilisation du Logiciel à des fins non conforme à la réglementation en vigueur
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
name: Kelvin
provenance_date: '2026-11-09'
provider_name: Kelvin
provider_slug: kelvin
slug: kelvin-eligibility
source_date: '2026-11-09'
source_filename: kelvin-eligibility.yml
source_heading: Eligibility
source_page: https://www.go-kelvin.com/conditions-de-vente
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kelvin\naid: kelvin\nurl: https://www.go-kelvin.com/conditions-de-vente\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: la personne physique ou morale qui s’engage auprès de KELVIN pour ses propres besoins professionnels\nrestricted_uses:\n- summary: Use contrary to applicable regulation\n  text: l’utilisation du Logiciel à des fins non conforme à la réglementation en vigueur\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kelvin/eligibility/kelvin-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Kelvin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Energy Efficiency
- Home Renovation
- Construction
- Artificial Intelligence
- Lead Generation
- Sales Enablement
- France
- Sustainability
---
