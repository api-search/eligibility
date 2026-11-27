---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: toda persona natural o persona jurídica que, tras haber suscrito y aceptado los Términos y Condiciones, se le ha otorgado el uso del Sistema
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Single contracted establishment
    text: el uso del plan adquirido es única y exclusivamente para los establecimientos comerciales contratados al momento de elegir el plan.
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
name: FITCO
provenance_date: '2026-11-09'
provider_name: FITCO
provider_slug: fitco
slug: fitco-eligibility
source_date: '2026-11-09'
source_filename: fitco-eligibility.yml
source_heading: Eligibility
source_page: https://www.fitcolatam.com/terminos-condiciones/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FITCO\naid: fitco\nurl: https://www.fitcolatam.com/terminos-condiciones/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: toda persona natural o persona jurídica que, tras haber suscrito y aceptado los Términos y Condiciones,\n    se le ha otorgado el uso del Sistema\nrestricted_uses:\n- summary: Single contracted establishment\n  text: el uso del plan adquirido es única y exclusivamente para los establecimientos comerciales contratados al\n    momento de elegir el plan.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fitco/eligibility/fitco-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from FITCO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fitness
- Gym Management
- Software-as-a-Service
- Latin America
- Booking
- Membership
- Payments
- Wellness
- Boutique Fitness
---
