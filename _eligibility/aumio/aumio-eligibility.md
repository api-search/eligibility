---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Eltern, Lehrer und andere Fachkräfte können die Aumio-App nutzen, um Kinder und Jugendliche beim Lernen zu begleiten.
    type: individual
  - text: Sofern der Nutzer Unternehmer (gem. § 14 BGB) ist, ist ausschließlicher Gerichtsstand
    type: business
  minimum_age:
    text: null
    value: null
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
name: Aumio
provenance_date: '2026-11-09'
provider_name: Aumio
provider_slug: aumio
slug: aumio-eligibility
source_date: '2026-11-09'
source_filename: aumio-eligibility.yml
source_heading: Eligibility
source_page: https://www.aumio.com/rechtliches/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aumio\naid: aumio\nurl: https://www.aumio.com/rechtliches/agb\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Eltern, Lehrer und andere Fachkräfte können die Aumio-App nutzen, um Kinder und Jugendliche beim Lernen\n    zu begleiten.\n- type: business\n  text: Sofern der Nutzer Unternehmer (gem. § 14 BGB) ist, ist ausschließlicher Gerichtsstand\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aumio/eligibility/aumio-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Aumio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Mental Health
- Sleep
- Meditation
- Mindfulness
- Children
- Wellness
- Mobile App
- Consumer
---
