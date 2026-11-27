---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: individual healthcare providers
    type: individual
  - text: healthcare facility owners or managers, vendors, suppliers, or other users
    type: business
  minimum_age:
    text: (i) are at least 18 years of age, or otherwise over the age of majority in the jurisdiction in which you reside
    value: '18'
  restricted_uses:
  - summary: No use while driving
    text: Using the Services while operating a motor vehicle;
  - summary: Not for medical emergencies or critical care
    text: THE SERVICES ARE NOT FAULT TOLERANT AND ARE NOT DESIGNED OR INTENDED FOR USE AS A “CRITICAL CONTROL APPLICATION” IN MEDICAL EMERGENCIES
  - summary: Lawful purposes only
    text: Using the Services for anything other than lawful purposes including, but not limited to, intentionally or unintentionally violating any applicable local, state, national or international law
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
name: SnapCare
provenance_date: '2026-11-10'
provider_name: SnapCare
provider_slug: snapcare
slug: snapcare-eligibility
source_date: '2026-11-10'
source_filename: snapcare-eligibility.yml
source_heading: Eligibility
source_page: https://snapcare.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SnapCare\naid: snapcare\nurl: https://snapcare.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country that is subject to a U.S. Government embargo,\n    or that has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: individual healthcare providers\n- type: business\n  text: healthcare facility owners or managers, vendors, suppliers, or other users\nrestricted_uses:\n- summary: No use while driving\n  text: Using the Services while operating\
  \ a motor vehicle;\n- summary: Not for medical emergencies or critical care\n  text: THE SERVICES ARE NOT FAULT TOLERANT AND ARE NOT DESIGNED OR INTENDED FOR USE AS A “CRITICAL CONTROL APPLICATION”\n    IN MEDICAL EMERGENCIES\n- summary: Lawful purposes only\n  text: Using the Services for anything other than lawful purposes including, but not limited to, intentionally\n    or unintentionally violating any applicable local, state, national or international law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: (i) are at least 18 years of age, or otherwise over the age of majority in the jurisdiction in which you\n    reside\n"
source_yaml_url: https://artifacts.apis.io/snapcare/eligibility/snapcare-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from SnapCare's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Staffing
- Workforce Management
- Scheduling
- Marketplace
- Human Resources
- Nursing
---
