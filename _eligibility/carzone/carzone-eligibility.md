---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IE
    text: The Website and related services are intended primarily for residents of Ireland. If you access the Website from outside Ireland, you do so at your own risk and are responsible for compliance with any laws applicable to you.
  entity_types:
  - text: 'You must be legally capable of entering into binding contracts in order to: create an account; place Advertisements in your own name; or buy paid services, including Car Check.'
    type: individual
  minimum_age:
    text: 'If you are under 18: you may browse the Website for information with the knowledge and consent of a parent or legal guardian; you must not create an account, place Advertisements in your own name, or enter into any contract for paid services'
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You agree to use the Website, Private Portal and related services only for lawful purposes and in line with these Terms and any policies we publish.
  - summary: No use of Category A/B write-offs
    text: 'Where a vehicle is recorded as a Category A/B Vehicle, we may at any time: refuse to publish an Advertisement for that vehicle'
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
name: Carzone
provenance_date: '2026-11-09'
provider_name: Carzone
provider_slug: carzone
slug: carzone-eligibility
source_date: '2026-11-09'
source_filename: carzone-eligibility.yml
source_heading: Eligibility
source_page: https://www.carzone.ie/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carzone\naid: carzone\nurl: https://www.carzone.ie/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IE\n  excluded: []\n  text: The Website and related services are intended primarily for residents of Ireland. If you access the Website\n    from outside Ireland, you do so at your own risk and are responsible for compliance with any laws applicable\n    to you.\nentity_types:\n- type: individual\n  text: 'You must be legally capable of entering into binding contracts in order to: create an account; place Advertisements\n    in your own name; or buy paid services, including Car Check.'\n\
  restricted_uses:\n- summary: Lawful use only\n  text: You agree to use the Website, Private Portal and related services only for lawful purposes and in line with\n    these Terms and any policies we publish.\n- summary: No use of Category A/B write-offs\n  text: 'Where a vehicle is recorded as a Category A/B Vehicle, we may at any time: refuse to publish an Advertisement\n    for that vehicle'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'If you are under 18: you may browse the Website for information with the knowledge and consent of a parent\n    or legal guardian; you must not create an account, place Advertisements in your own name, or enter into any\n    contract for paid services'\n"
source_yaml_url: https://artifacts.apis.io/carzone/eligibility/carzone-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Carzone's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Automotive
- Ireland
- Cars
---
