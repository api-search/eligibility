---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: L'inscription sur le Site est gratuite et accessible à tout Utilisateur personne physique âgé d’au moins dix-huit (18) ans révolus
    type: individual
  - text: ainsi qu’à toute personne morale.
    type: business
  minimum_age:
    text: personne physique âgé d’au moins dix-huit (18) ans révolus
    value: '18'
  restricted_uses:
  - summary: Off-platform transactions barred
    text: L’Acheteur s’interdit expressément de conclure toute transaction directement avec un Vendeur rencontré par l’intermédiaire du Site, en dehors de la plateforme SELENCY
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: SELENCY se réserve le droit de demander à l’Acheteur des justificatifs d’identité
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Selency
provenance_date: '2026-11-10'
provider_name: Selency
provider_slug: selency
slug: selency-eligibility
source_date: '2026-11-10'
source_filename: selency-eligibility.yml
source_heading: Eligibility
source_page: https://share.selency.com/CGV/cgv.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Selency\naid: selency\nurl: https://share.selency.com/CGV/cgv.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: L'inscription sur le Site est gratuite et accessible à tout Utilisateur personne physique âgé d’au moins\n    dix-huit (18) ans révolus\n- type: business\n  text: ainsi qu’à toute personne morale.\nrestricted_uses:\n- summary: Off-platform transactions barred\n  text: L’Acheteur s’interdit expressément de conclure toute transaction directement avec un Vendeur rencontré par\n    l’intermédiaire du Site,\
  \ en dehors de la plateforme SELENCY\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: SELENCY se réserve le droit de demander à l’Acheteur des justificatifs d’identité\nminimum_age:\n  value: '18'\n  text: personne physique âgé d’au moins dix-huit (18) ans révolus\n"
source_yaml_url: https://artifacts.apis.io/selency/eligibility/selency-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Selency's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Marketplace
- Furniture
- Home Decor
- Secondhand
- Vintage
- E-Commerce
- France
---
