---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: ofreciendo los Servicios de aceptación de pagos con tarjetas de débito, crédito, y Servicios a través de dispositivos móviles, en México.
  entity_types:
  - text: una persona física, mayor de edad, con capacidad para celebrar los presentes T&C
    type: individual
  - text: persona moral debidamente constituida conforme las Leyes de los Estados Unidos Mexicanos
    type: business
  minimum_age:
    text: una persona física, mayor de edad
    value: null
  restricted_uses:
  - summary: Illegal transactions
    text: Cualquier tipo de transacción que infrinja leyes locales, nacionales o internacionales
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
name: Clip
provenance_date: '2026-11-09'
provider_name: Clip
provider_slug: clip
slug: clip-eligibility
source_date: '2026-11-09'
source_filename: clip-eligibility.yml
source_heading: Eligibility
source_page: https://www.clip.mx/terminos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clip\naid: clip\nurl: https://www.clip.mx/terminos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: ofreciendo los Servicios de aceptación de pagos con tarjetas de débito, crédito, y Servicios a través de\n    dispositivos móviles, en México.\nentity_types:\n- type: individual\n  text: una persona física, mayor de edad, con capacidad para celebrar los presentes T&C\n- type: business\n  text: persona moral debidamente constituida conforme las Leyes de los Estados Unidos Mexicanos\nrestricted_uses:\n- summary: Illegal transactions\n  text: Cualquier tipo de transacción\
  \ que infrinja leyes locales, nacionales o internacionales\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: una persona física, mayor de edad\n"
source_yaml_url: https://artifacts.apis.io/clip/eligibility/clip-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Clip's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Acquiring
- SMB Payments
- Point-of-Sale
- mPOS
- Tap to Pay
- Card Acceptance
- Checkout
- Payment Gateway
- Payment Links
- Mexico
- Latin America
- Fintech
- PCI
---
