---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Livraison à toute adresse partout dans le monde : « Les Produits commandés sont, au choix de l''Acheteur, livrés à toute adresse partout dans le monde. »'
  entity_types:
  - text: Le Client doit être âgé d’au moins 18 ans et avoir la capacité juridique ou être titulaire d’une autorisation parentale
    type: individual
  minimum_age:
    text: Le Client doit être âgé d’au moins 18 ans
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: Rouje rappelle que les Produits sont exclusivement dédiés à l’usage personnel de l'Acheteur
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
name: Rouje
provenance_date: '2026-11-10'
provider_name: Rouje
provider_slug: rouje
slug: rouje-eligibility
source_date: '2026-11-10'
source_filename: rouje-eligibility.yml
source_heading: Eligibility
source_page: https://www.rouje.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rouje\naid: rouje\nurl: https://www.rouje.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Livraison à toute adresse partout dans le monde : « Les Produits commandés sont, au choix de l''Acheteur,\n    livrés à toute adresse partout dans le monde. »'\nentity_types:\n- type: individual\n  text: Le Client doit être âgé d’au moins 18 ans et avoir la capacité juridique ou être titulaire d’une autorisation\n    parentale\nrestricted_uses:\n- summary: Personal use only\n  text: Rouje rappelle que les Produits sont exclusivement dédiés à l’usage personnel de\
  \ l'Acheteur\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Le Client doit être âgé d’au moins 18 ans\n"
source_yaml_url: https://artifacts.apis.io/rouje/eligibility/rouje-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Rouje's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Fashion
- Beauty
- Retail
- E-Commerce
- Shopify
- Agentic Commerce
- Paris
---
