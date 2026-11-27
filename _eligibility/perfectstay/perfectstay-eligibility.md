---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Les tarifs indiqués sur le Site sont applicables aux Clients résidents dans l’Union Européenne.
  entity_types:
  - text: '« Client » : désigne toute personne physique majeure et capable'
    type: individual
  - text: Sont exclues les personnes morales qui souhaitent commander des Prestations de manière régulière et/ou en grand nombre
    type: business
  minimum_age:
    text: '« Client » : désigne toute personne physique majeure et capable'
    value: majeure
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
name: PerfectStay
provenance_date: '2026-11-10'
provider_name: PerfectStay
provider_slug: perfectstay
slug: perfectstay-eligibility
source_date: '2026-11-10'
source_filename: perfectstay-eligibility.yml
source_heading: Eligibility
source_page: https://res.cloudinary.com/perfectstay/image/upload/v1751049126/cms/files/ox7azn9e/live/370239c6321b04f7fd3bd3e8cebc107ff94e98b3.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PerfectStay\naid: perfectstay\nurl: https://res.cloudinary.com/perfectstay/image/upload/v1751049126/cms/files/ox7azn9e/live/370239c6321b04f7fd3bd3e8cebc107ff94e98b3.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Les tarifs indiqués sur le Site sont applicables aux Clients résidents dans l’Union Européenne.\nentity_types:\n- type: individual\n  text: '« Client » : désigne toute personne physique majeure et capable'\n- type: business\n  text: Sont exclues les personnes morales qui souhaitent commander des Prestations de manière régulière et/ou en\n    grand nombre\nrestricted_uses:\
  \ []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: majeure\n  text: '« Client » : désigne toute personne physique majeure et capable'\n"
source_yaml_url: https://artifacts.apis.io/perfectstay/eligibility/perfectstay-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from PerfectStay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Applicative Saas
- Travel
- Tourism
- E-Commerce
- Booking
- Hospitality
- Flights
---
