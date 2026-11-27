---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not barred from using the Services under the laws of the United States, your place of residence or any other applicable jurisdiction.
  entity_types:
  - text: THE TERM “YOU” REFERS TO THE INDIVIDUAL IDENTIFIED AS THE USER WHEN REGISTERING ON OR ACCESSING THE SERVICES.
    type: individual
  minimum_age:
    text: You represent that you are (i) at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Controlled substance prescriptions
    text: YOU ACKNOWLEDGE THAT YOU WILL NOT BE ABLE TO FILL PRESCRIPTIONS FOR CONTROLLED SUBSTANCES THROUGH THE SERVICES.
  - summary: Use by Competitors
    text: You will not create or maintain an Account, or use, access, or attempt to use or access the Services in any capacity
  - summary: Not for emergencies
    text: OUR SERVICES SHOULD NEVER BE USED FOR MEDICAL EMERGENCIES OR URGENT SITUATIONS
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Clara reserves the right, at any time and in its reasonable discretion, to require that you verify your identity, employment, professional affiliations, or any other facts bearing on this Section
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clara 2
provenance_date: '2026-11-09'
provider_name: Clara 2
provider_slug: clara-2
slug: clara-2-eligibility
source_date: '2026-11-09'
source_filename: clara-2-eligibility.yml
source_heading: Eligibility
source_page: https://askclara.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clara 2\naid: clara-2\nurl: https://askclara.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not barred from using the Services under the laws of the United States, your\n    place of residence or any other applicable jurisdiction.\nentity_types:\n- type: individual\n  text: THE TERM “YOU” REFERS TO THE INDIVIDUAL IDENTIFIED AS THE USER WHEN REGISTERING ON OR ACCESSING THE SERVICES.\nrestricted_uses:\n- summary: Controlled substance prescriptions\n  text: YOU ACKNOWLEDGE THAT YOU WILL NOT BE ABLE TO FILL PRESCRIPTIONS\
  \ FOR CONTROLLED SUBSTANCES THROUGH THE SERVICES.\n- summary: Use by Competitors\n  text: You will not create or maintain an Account, or use, access, or attempt to use or access the Services in\n    any capacity\n- summary: Not for emergencies\n  text: OUR SERVICES SHOULD NEVER BE USED FOR MEDICAL EMERGENCIES OR URGENT SITUATIONS\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Clara reserves the right, at any time and in its reasonable discretion, to require that you verify your\n    identity, employment, professional affiliations, or any other facts bearing on this Section\nminimum_age:\n  value: '18'\n  text: You represent that you are (i) at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/clara-2/eligibility/clara-2-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Clara 2's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Primary Care
- Telehealth
- Artificial Intelligence
- Longevity
- Digital Health
- HIPAA
- Y Combinator
---
