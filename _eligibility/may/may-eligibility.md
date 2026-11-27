---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Toute personne physique âgée de plus de 18 ans et jouissant de ses pleines capacités juridiques, ou toute personne morale de droit privé ou public navigant sur le Site et/ou souscrivant au Service.
    type: individual
  minimum_age:
    text: Pour créer son Compte, l’Utilisateur doit être une personne physique, âgée de dix-huit (18) ans ou ayant atteint l’âge légal dans son pays de résidence
    value: '18'
  restricted_uses:
  - summary: Medical consultations excluded
    text: Sont exclues de ce service les consultations médicales.
  - summary: Manual use only
    text: l’accès aux Services est limité à une utilisation manuelle.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: La création d’un Compte personnel est subordonnée à une validation. L’Utilisateur reçoit un code sur son téléphone portable, à reporter sur son profil d’inscription aux fins de validation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: May
provenance_date: '2026-11-10'
provider_name: May
provider_slug: may
slug: may-eligibility
source_date: '2026-11-10'
source_filename: may-eligibility.yml
source_heading: Eligibility
source_page: https://www.may.app/cgu/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: May\naid: may\nurl: https://www.may.app/cgu/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Toute personne physique âgée de plus de 18 ans et jouissant de ses pleines capacités juridiques, ou toute\n    personne morale de droit privé ou public navigant sur le Site et/ou souscrivant au Service.\nrestricted_uses:\n- summary: Medical consultations excluded\n  text: Sont exclues de ce service les consultations médicales.\n- summary: Manual use only\n  text: l’accès aux Services est limité à une utilisation manuelle.\nverification:\n \
  \ kyc: null\n  kyb: null\n  approval_required: null\n  text: La création d’un Compte personnel est subordonnée à une validation. L’Utilisateur reçoit un code sur son\n    téléphone portable, à reporter sur son profil d’inscription aux fins de validation.\nminimum_age:\n  value: '18'\n  text: Pour créer son Compte, l’Utilisateur doit être une personne physique, âgée de dix-huit (18) ans ou ayant\n    atteint l’âge légal dans son pays de résidence\n"
source_yaml_url: https://artifacts.apis.io/may/eligibility/may-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from May's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Digital Health
- Parenting
- Pregnancy
- Maternal Health
- Consumer Health
- Mobile App
- Employee Benefits
- France
---
