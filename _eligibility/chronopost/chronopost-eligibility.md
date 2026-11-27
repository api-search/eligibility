---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Client : toute personne, physique ou morale, qui passe une commande sur notre Site.'
    type: business
  minimum_age:
    text: Pour créer un Compte Client, vous devez être majeur.
    value: majeur
  restricted_uses:
  - summary: No sharing of login with third-party services
    text: Il est formellement interdit de communiquer vos identifiants (login et mot de passe) à tout service tiers, notamment s'il s'agit d'un système automatisé.
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
name: Chronopost
provenance_date: '2026-11-09'
provider_name: Chronopost
provider_slug: chronopost
slug: chronopost-eligibility
source_date: '2026-11-09'
source_filename: chronopost-eligibility.yml
source_heading: Eligibility
source_page: https://www.chronopost.fr/fr/conditions-generales-utilisation
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chronopost\naid: chronopost\nurl: https://www.chronopost.fr/fr/conditions-generales-utilisation\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'Client : toute personne, physique ou morale, qui passe une commande sur notre Site.'\nrestricted_uses:\n- summary: No sharing of login with third-party services\n  text: Il est formellement interdit de communiquer vos identifiants (login et mot de passe) à tout service tiers,\n    notamment s'il s'agit d'un système automatisé.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: majeur\n  text: Pour créer un Compte Client, vous devez être majeur.\n"
source_yaml_url: https://artifacts.apis.io/chronopost/eligibility/chronopost-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Chronopost's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Shipping
- Logistics
- Parcel Delivery
- Express Courier
- SOAP
- Tracking
- France
---
