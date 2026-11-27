---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    text: Utilisateur toute personne physique majeure utilisateur du Site ayant sa résidence fiscale en France métropolitaine
  entity_types:
  - text: Le Site et les Services s’adressent exclusivement aux particuliers et ne sont pas destinés à un usage professionnel
    type: individual
  minimum_age:
    text: toute personne physique majeure
    value: '18'
  restricted_uses:
  - summary: Non-professional use only
    text: ne sont pas destinés à un usage professionnel, entendu comme tout usage lié directement ou indirectement à une activité rémunérée exercée de façon non occasionnelle
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
name: Dalma
provenance_date: '2026-11-09'
provider_name: Dalma
provider_slug: dalma
slug: dalma-eligibility
source_date: '2026-11-09'
source_filename: dalma-eligibility.yml
source_heading: Eligibility
source_page: https://editique.dalma.co/formule_dalma/latest/CGU_dalma_fr.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dalma\naid: dalma\nurl: https://editique.dalma.co/formule_dalma/latest/CGU_dalma_fr.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - FR\n  excluded: []\n  text: Utilisateur toute personne physique majeure utilisateur du Site ayant sa résidence fiscale en France métropolitaine\nentity_types:\n- type: individual\n  text: Le Site et les Services s’adressent exclusivement aux particuliers et ne sont pas destinés à un usage professionnel\nrestricted_uses:\n- summary: Non-professional use only\n  text: ne sont pas destinés à un usage professionnel, entendu comme tout usage lié directement ou indirectement\n\
  \    à une activité rémunérée exercée de façon non occasionnelle\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: toute personne physique majeure\n"
source_yaml_url: https://artifacts.apis.io/dalma/eligibility/dalma-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Dalma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Insurance
- Insurtech
- Pet Insurance
- Pets
- Veterinary
- France
---
