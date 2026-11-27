---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Le fait pour une personne physique (ou morale), de commander des Services de CoachClub emporte adhésion et acceptation pleine et entière des présentes Conditions Générales de Vente
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal subscriptions non-transferable
    text: l’abonnement « à vie » est personnel et ne peut en aucun cas être rétrocédé, loué ou prêté à un tiers.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: CoachClub n’a pas pour obligation et ne dispose pas des moyens techniques pour s’assurer de l’identité des personnes s’inscrivant à ses Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CoachClub
provenance_date: '2026-11-09'
provider_name: CoachClub
provider_slug: coachclub
slug: coachclub-eligibility
source_date: '2026-11-09'
source_filename: coachclub-eligibility.yml
source_heading: Eligibility
source_page: https://coachclub.com/conditions-generales-de-vente-cgv/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CoachClub\naid: coachclub\nurl: https://coachclub.com/conditions-generales-de-vente-cgv/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Le fait pour une personne physique (ou morale), de commander des Services de CoachClub emporte adhésion\n    et acceptation pleine et entière des présentes Conditions Générales de Vente\nrestricted_uses:\n- summary: Personal subscriptions non-transferable\n  text: l’abonnement « à vie » est personnel et ne peut en aucun cas être rétrocédé, loué ou prêté à un tiers.\nverification:\n  kyc: false\n \
  \ kyb: null\n  approval_required: null\n  text: CoachClub n’a pas pour obligation et ne dispose pas des moyens techniques pour s’assurer de l’identité des\n    personnes s’inscrivant à ses Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coachclub/eligibility/coachclub-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from CoachClub's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Fitness
- Health and Wellness
- Online Coaching
- Video Streaming
- Subscription
- Nutrition
- France
---
