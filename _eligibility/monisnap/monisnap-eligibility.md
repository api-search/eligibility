---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    text: La politique s’applique à vous, en tant qu’utilisateur de l’application MONI, en France Métropolitaine, dès lors que vous êtes âgé d'au moins 18 ans.
  entity_types:
  - text: L’accès aux Applications Monisnap et à ses fonctionnalités est réservé aux personnes physiques juridiquement capables.
    type: individual
  minimum_age:
    text: dès lors que vous êtes âgé d'au moins 18 ans
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: la réalisation de la vérification d’identité du Client telle que demandée par le Correspondant Bancaire
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MONI (Ex-Monisnap)
provenance_date: '2026-11-10'
provider_name: MONI (Ex-Monisnap)
provider_slug: monisnap
slug: monisnap-eligibility
source_date: '2026-11-10'
source_filename: monisnap-eligibility.yml
source_heading: Eligibility
source_page: https://assets.monisnap.com/monisnap/legal/monisnap-legal-notice.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MONI (Ex-Monisnap)\naid: monisnap\nurl: https://assets.monisnap.com/monisnap/legal/monisnap-legal-notice.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - FR\n  excluded: []\n  text: La politique s’applique à vous, en tant qu’utilisateur de l’application MONI, en France Métropolitaine,\n    dès lors que vous êtes âgé d'au moins 18 ans.\nentity_types:\n- type: individual\n  text: L’accès aux Applications Monisnap et à ses fonctionnalités est réservé aux personnes physiques juridiquement\n    capables.\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required:\
  \ null\n  text: la réalisation de la vérification d’identité du Client telle que demandée par le Correspondant Bancaire\nminimum_age:\n  value: '18'\n  text: dès lors que vous êtes âgé d'au moins 18 ans\n"
source_yaml_url: https://artifacts.apis.io/monisnap/eligibility/monisnap-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from MONI (Ex-Monisnap)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech Insurtech
- Money Transfer
- Remittances
- Payments
- Mobile Money
- Airtime Top-Up
- Prepaid Cards
- Embedded Finance
- France
---
