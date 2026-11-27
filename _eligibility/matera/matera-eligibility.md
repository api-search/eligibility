---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: à toute personne physique disposant de la pleine capacité juridique (+18 ans)
    type: individual
  - text: à toute personne morale agissant par l’intermédiaire d’une personne physique disposant de la capacité juridique pour contracter au nom et pour le compte de la personne morale.
    type: business
  minimum_age:
    text: à toute personne physique disposant de la pleine capacité juridique (+18 ans)
    value: '18'
  restricted_uses:
  - summary: No commercial content in shared spaces
    text: de monnayer, vendre ou concéder tout ou partie du Forum, ainsi que le Contenu qui y est hébergé et/ou partagé
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Matera ne vérifie pas les pouvoirs des représentants.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Matera
provenance_date: '2026-11-10'
provider_name: Matera
provider_slug: matera
slug: matera-eligibility
source_date: '2026-11-10'
source_filename: matera-eligibility.yml
source_heading: Eligibility
source_page: https://matera.eu/fr/documents-juridiques/cgu
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Matera\naid: matera\nurl: https://matera.eu/fr/documents-juridiques/cgu\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: à toute personne physique disposant de la pleine capacité juridique (+18 ans)\n- type: business\n  text: à toute personne morale agissant par l’intermédiaire d’une personne physique disposant de la capacité juridique\n    pour contracter au nom et pour le compte de la personne morale.\nrestricted_uses:\n- summary: No commercial content in shared spaces\n  text: de monnayer, vendre ou concéder tout ou partie du Forum,\
  \ ainsi que le Contenu qui y est hébergé et/ou partagé\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Matera ne vérifie pas les pouvoirs des représentants.\nminimum_age:\n  value: '18'\n  text: à toute personne physique disposant de la pleine capacité juridique (+18 ans)\n"
source_yaml_url: https://artifacts.apis.io/matera/eligibility/matera-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Matera's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Business Applications
- PropTech
- Property Management
- Real Estate
- Condominium Management
- Fintech
- France
- Software-as-a-Service
---
