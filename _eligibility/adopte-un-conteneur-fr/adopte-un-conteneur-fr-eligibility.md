---
api_specs:
- filename: adopte-un-conteneur-fr-delivery-api-openapi.yml
  format: yaml
  label: Adopte Un Conteneur Delivery API
  slug: adopte-un-conteneur-fr-delivery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adopte-un-conteneur-fr/openapi/adopte-un-conteneur-fr-delivery-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    text: Livraison France entière
  entity_types:
  - text: Si vous êtes un particulier (consommateur)
    type: individual
  - text: les grandes entreprises et les collectivités publiques
    type: business
  - text: les collectivités publiques
    type: government
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
name: Adopte Un Conteneur
provenance_date: '2026-11-09'
provider_name: Adopte Un Conteneur
provider_slug: adopte-un-conteneur-fr
slug: adopte-un-conteneur-fr-eligibility
source_date: '2026-11-09'
source_filename: adopte-un-conteneur-fr-eligibility.yml
source_heading: Eligibility
source_page: https://adopte-un-conteneur.fr/cgv/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adopte Un Conteneur\naid: adopte-un-conteneur-fr\nurl: https://adopte-un-conteneur.fr/cgv/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - FR\n  excluded: []\n  text: Livraison France entière\nentity_types:\n- type: individual\n  text: Si vous êtes un particulier (consommateur)\n- type: business\n  text: les grandes entreprises et les collectivités publiques\n- type: government\n  text: les collectivités publiques\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adopte-un-conteneur-fr/eligibility/adopte-un-conteneur-fr-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 4 quoted statements, read from Adopte Un Conteneur's own page on 2026-11-09.
synthetic: false
tags:
- Containers
- Maritime
- Storage
- Modular
- France
---
