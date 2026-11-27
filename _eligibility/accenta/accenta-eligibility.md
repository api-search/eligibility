---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '« Utilisateur(s) autorisé(s) » ou « Utilisateur(s) » : désigne toute personne physique qui est autorisée , sur demande du Client , par le Prestataire, à accéder et utiliser la Plateforme'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Private, non-commercial use only
    text: s’engage à n’en faire qu’un usage privé et non commercial , tout autre usage étant prohibé
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: toute personne physique qui est autorisée , sur demande du Client , par le Prestataire, à accéder et utiliser la Plateforme
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Accenta
provenance_date: '2026-11-09'
provider_name: Accenta
provider_slug: accenta
slug: accenta-eligibility
source_date: '2026-11-09'
source_filename: accenta-eligibility.yml
source_heading: Eligibility
source_page: https://storage.sbg.cloud.ovh.net/v1/AUTH_3d9cbc20c59c4c77a70475ce27cd4ecb/Images%20publiques%20effiPilot/Contrat_Licence_Utilisateur_Final_v200_20260602.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Accenta\naid: accenta\nurl: https://storage.sbg.cloud.ovh.net/v1/AUTH_3d9cbc20c59c4c77a70475ce27cd4ecb/Images%20publiques%20effiPilot/Contrat_Licence_Utilisateur_Final_v200_20260602.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '« Utilisateur(s) autorisé(s) » ou « Utilisateur(s) » : désigne toute personne physique qui est autorisée\n    , sur demande du Client , par le Prestataire, à accéder et utiliser la Plateforme'\nrestricted_uses:\n- summary: Private, non-commercial use only\n  text: s’engage à n’en faire qu’un usage privé\
  \ et non commercial , tout autre usage étant prohibé\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: toute personne physique qui est autorisée , sur demande du Client , par le Prestataire, à accéder et utiliser\n    la Plateforme\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/accenta/eligibility/accenta-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Accenta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ai Data
- Energy
- Buildings
- Smart Buildings
- Building Management
- Geothermal
- Decarbonization
- Sustainability
- Energy Management
- Artificial Intelligence
- Real Estate
- IoT
- France
---
