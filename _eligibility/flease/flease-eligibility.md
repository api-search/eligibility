---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Site content restricted to private use
    text: Il s'engage à une utilisation des contenus du site dans un cadre strictement privé
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Pour accéder aux services, l’Utilisateur doit ensuite s'identifier à l'aide de son identifiant et de son mot de passe qui lui seront communiqués après son inscription.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Flease
provenance_date: '2026-11-09'
provider_name: Flease
provider_slug: flease
slug: flease-eligibility
source_date: '2026-11-09'
source_filename: flease-eligibility.yml
source_heading: Eligibility
source_page: https://www.flease.fr/legal/conditions-generales-dutilisation
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flease\naid: flease\nurl: https://www.flease.fr/legal/conditions-generales-dutilisation\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Site content restricted to private use\n  text: Il s'engage à une utilisation des contenus du site dans un cadre strictement privé\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Pour accéder aux services, l’Utilisateur doit ensuite s'identifier à l'aide de son identifiant et de son\n    mot de passe qui lui seront communiqués après son inscription.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flease/eligibility/flease-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Flease's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Automotive
- Vehicle Leasing
- Fleet Management
- Mobility
- France
---
