---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: not barred from receiving the Service under the laws of the United States or other applicable jurisdiction
  entity_types:
  - text: you must be capable of forming a binding contract, and not be barred from receiving the Service under the laws of the United States or other applicable jurisdiction
    type: individual
  minimum_age:
    text: If you are under 18, you may only use the Service under the supervision of a parent or legal guardian who agrees to be bound by these Terms.
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: solely for your own personal, non-commercial purposes
  - summary: Illegal or unsafe purposes
    text: you will not use the Service for any illegal, unauthorized, unintended, unsafe, hazardous, or unlawful purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To create an Account for the Service, you must sign into the Service, in which case we will have access to your first name, last name and email address
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vermeer
provenance_date: '2026-11-10'
provider_name: Vermeer
provider_slug: vermeer
slug: vermeer-eligibility
source_date: '2026-11-10'
source_filename: vermeer-eligibility.yml
source_heading: Eligibility
source_page: https://www.getvermeer.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vermeer\naid: vermeer\nurl: https://www.getvermeer.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: not barred from receiving the Service under the laws of the United States or other applicable jurisdiction\nentity_types:\n- type: individual\n  text: you must be capable of forming a binding contract, and not be barred from receiving the Service under the\n    laws of the United States or other applicable jurisdiction\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: solely for your own personal, non-commercial purposes\n- summary: Illegal or unsafe\
  \ purposes\n  text: you will not use the Service for any illegal, unauthorized, unintended, unsafe, hazardous, or unlawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To create an Account for the Service, you must sign into the Service, in which case we will have access\n    to your first name, last name and email address\nminimum_age:\n  value: '18'\n  text: If you are under 18, you may only use the Service under the supervision of a parent or legal guardian who\n    agrees to be bound by these Terms.\n"
source_yaml_url: https://artifacts.apis.io/vermeer/eligibility/vermeer-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Vermeer's own page on 2026-11-10.
synthetic: false
tags:
- Company
- B2B
- Defense
- Aerospace
- Drones
- Navigation
- Computer Vision
- Autonomy
- GPS-Denied
---
