---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    text: DIKOO étant principalement destiné au marché français
  entity_types:
  - text: 'Utilisateur / Client : toute personne physique majeure qui crée un compte client sur la Plateforme'
    type: individual
  - text: 'Avocat : tout professionnel régulièrement inscrit à un barreau français qui crée un compte avocat sur la Plateforme.'
    type: other
  minimum_age:
    text: toute personne physique majeure qui crée un compte client
    value: majeur
  restricted_uses:
  - summary: Off-platform payment for consultations
    text: 'En mode Paiement en ligne : toute tentative d''organiser le règlement de la Consultation en dehors de la Plateforme'
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: création d'un compte avec vérification d'identité et d'inscription au barreau (procédure KYC). Le compte est activé après contrôle par l'équipe DIKOO.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DIKOO
provenance_date: '2026-11-09'
provider_name: DIKOO
provider_slug: dikoo-fr
slug: dikoo-fr-eligibility
source_date: '2026-11-09'
source_filename: dikoo-fr-eligibility.yml
source_heading: Eligibility
source_page: https://www.dikoo.fr/cgu
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DIKOO\naid: dikoo-fr\nurl: https://www.dikoo.fr/cgu\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - FR\n  excluded: []\n  text: DIKOO étant principalement destiné au marché français\nentity_types:\n- type: individual\n  text: 'Utilisateur / Client : toute personne physique majeure qui crée un compte client sur la Plateforme'\n- type: other\n  text: 'Avocat : tout professionnel régulièrement inscrit à un barreau français qui crée un compte avocat sur la\n    Plateforme.'\nrestricted_uses:\n- summary: Off-platform payment for consultations\n  text: 'En mode Paiement en ligne : toute tentative d''organiser\
  \ le règlement de la Consultation en dehors de la\n    Plateforme'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: création d'un compte avec vérification d'identité et d'inscription au barreau (procédure KYC). Le compte\n    est activé après contrôle par l'équipe DIKOO.\nminimum_age:\n  value: majeur\n  text: toute personne physique majeure qui crée un compte client\n"
source_yaml_url: https://artifacts.apis.io/dikoo-fr/eligibility/dikoo-fr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from DIKOO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Lawyers
- Legal Directory
- Appointment Booking
- Legal Tech
- MCP
- Artificial Intelligence
- France
---
