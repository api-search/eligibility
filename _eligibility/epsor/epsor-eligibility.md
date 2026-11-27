---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Une fois créé, le compte EPSOR vous est strictement personnel et ne peut faire l’objet d’un accès par le personnel de votre entreprise.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Access by invitation only
    text: Vous ne pouvez accéder à votre interface personnelle de gestion de votre épargne salariale et vous inscrire sur la plateforme Epsor que si vous y avez été invité par Epsor
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: pour certaines opérations le contrôle de votre identité ou la communication de données complémentaires tendant à vérifier que vous êtes le détenteur du compte EPSOR
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Epsor
provenance_date: '2026-11-09'
provider_name: Epsor
provider_slug: epsor
slug: epsor-eligibility
source_date: '2026-11-09'
source_filename: epsor-eligibility.yml
source_heading: Eligibility
source_page: https://www.epsor.fr/cgu---app
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Epsor\naid: epsor\nurl: https://www.epsor.fr/cgu---app\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Une fois créé, le compte EPSOR vous est strictement personnel et ne peut faire l’objet d’un accès par le\n    personnel de votre entreprise.\nrestricted_uses:\n- summary: Access by invitation only\n  text: Vous ne pouvez accéder à votre interface personnelle de gestion de votre épargne salariale et vous inscrire\n    sur la plateforme Epsor que si vous y avez été invité par Epsor\nverification:\n  kyc: true\n  kyb: null\n  approval_required:\
  \ null\n  text: pour certaines opérations le contrôle de votre identité ou la communication de données complémentaires tendant\n    à vérifier que vous êtes le détenteur du compte EPSOR\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/epsor/eligibility/epsor-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Epsor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Employee Savings
- Retirement
- Épargne Salariale
- Human Resources
- Compensation and Benefits
- ESG
- France
---
