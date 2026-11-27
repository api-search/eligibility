---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Kintsugi makes no representations that Kintsugi Properties are appropriate or available for use in other locations.
  entity_types:
  - text: You represent that you are (a) of legal age to form a binding contract
    type: individual
  - text: THE TERM “YOU” REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE, IDENTIFIED AS THE USER WHEN YOU REGISTERED ON THE APPLICATION.
    type: business
  minimum_age:
    text: You represent that you are (a) of legal age to form a binding contract
    value: null
  restricted_uses:
  - summary: Not for emergency medical needs
    text: DO NOT USE THESE SERVICES FOR EMERGENCY MEDICAL NEEDS.
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
name: Kintsugi
provenance_date: '2026-11-09'
provider_name: Kintsugi
provider_slug: kintsugihello-com
slug: kintsugihello-com-eligibility
source_date: '2026-11-09'
source_filename: kintsugihello-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.kintsugihealth.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kintsugi\naid: kintsugihello-com\nurl: https://www.kintsugihealth.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Kintsugi makes no representations that Kintsugi Properties are appropriate or available for use in other\n    locations.\nentity_types:\n- type: individual\n  text: You represent that you are (a) of legal age to form a binding contract\n- type: business\n  text: THE TERM “YOU” REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE, IDENTIFIED AS THE USER WHEN YOU\n    REGISTERED ON THE APPLICATION.\nrestricted_uses:\n- summary: Not for emergency\
  \ medical needs\n  text: DO NOT USE THESE SERVICES FOR EMERGENCY MEDICAL NEEDS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent that you are (a) of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/kintsugihello-com/eligibility/kintsugihello-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Kintsugi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Mental Health
- VoiceBiomarkers
- Artificial Intelligence
---
