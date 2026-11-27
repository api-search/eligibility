---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: toute personne physique (ci-après, le « Membre ») bénéficiant du service proposé par la Société
    type: individual
  minimum_age:
    text: Le Membre doit être une personne physique âgée de 16 ans ou plus
    value: '16'
  restricted_uses:
  - summary: No use for competing business
    text: le Membre s’interdit d’utiliser la Solution dans l’exercice ou dans l’intérêt d’une activité commerciale concurrente de la Société
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
name: Joko
provenance_date: '2026-11-09'
provider_name: Joko
provider_slug: joko
slug: joko-eligibility
source_date: '2026-11-09'
source_filename: joko-eligibility.yml
source_heading: Eligibility
source_page: https://home.joko.com/fr/legal/conditions-generales
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Joko\naid: joko\nurl: https://home.joko.com/fr/legal/conditions-generales\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: toute personne physique (ci-après, le « Membre ») bénéficiant du service proposé par la Société\nrestricted_uses:\n- summary: No use for competing business\n  text: le Membre s’interdit d’utiliser la Solution dans l’exercice ou dans l’intérêt d’une activité commerciale\n    concurrente de la Société\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '16'\n  text: Le Membre doit être une personne physique âgée de 16 ans ou plus\n"
source_yaml_url: https://artifacts.apis.io/joko/eligibility/joko-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Joko's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Cashback
- Rewards
- Loyalty
- Consumer
- Payments
- Retail
- France
---
