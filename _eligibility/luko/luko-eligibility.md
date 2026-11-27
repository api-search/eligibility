---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    text: 'Pour ouvrir un compte Luko by Allianz Direct l’Utilisateur (personne physique) doit : Être résident fiscal en France.'
  entity_types:
  - text: Pour ouvrir un compte Luko by Allianz Direct l’Utilisateur (personne physique) doit
    type: individual
  minimum_age:
    text: Être majeur et être juridiquement capable.
    value: majeur
  restricted_uses:
  - summary: Multiple accounts or identity misuse
    text: Créer plusieurs comptes ou usurper l’identité d’un tiers
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
name: Luko
provenance_date: '2026-11-09'
provider_name: Luko
provider_slug: luko
slug: luko-eligibility
source_date: '2026-11-09'
source_filename: luko-eligibility.yml
source_heading: Eligibility
source_page: https://www.fr.luko.eu/cgu/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Luko\naid: luko\nurl: https://www.fr.luko.eu/cgu/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - FR\n  excluded: []\n  text: 'Pour ouvrir un compte Luko by Allianz Direct l’Utilisateur (personne physique) doit : Être résident fiscal\n    en France.'\nentity_types:\n- type: individual\n  text: Pour ouvrir un compte Luko by Allianz Direct l’Utilisateur (personne physique) doit\nrestricted_uses:\n- summary: Multiple accounts or identity misuse\n  text: Créer plusieurs comptes ou usurper l’identité d’un tiers\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: majeur\n  text: Être majeur et être juridiquement capable.\n"
source_yaml_url: https://artifacts.apis.io/luko/eligibility/luko-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Luko's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Insurance
- Insurtech
- Home Insurance
- Travel Insurance
- Auto Insurance
- France
- Allianz
---
