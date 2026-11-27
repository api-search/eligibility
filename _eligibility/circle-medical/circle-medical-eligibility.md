---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are neither located in a sanctioned country nor a prohibited person.
  entity_types:
  - text: You represent and warrant that you are at least eighteen (18) years of age and that you possess the legal right and ability to enter into agreements
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful or illegitimate purposes
    text: You agree not to use the Website Content or any service the Company provides in an unlawful way or for an unlawful or illegitimate purpose
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
name: Circle Medical
provenance_date: '2026-11-09'
provider_name: Circle Medical
provider_slug: circle-medical
slug: circle-medical-eligibility
source_date: '2026-11-09'
source_filename: circle-medical-eligibility.yml
source_heading: Eligibility
source_page: https://www.circlemedical.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Circle Medical\naid: circle-medical\nurl: https://www.circlemedical.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are neither located in a sanctioned country nor a prohibited person.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least eighteen (18) years of age and that you possess the legal\n    right and ability to enter into agreements\nrestricted_uses:\n- summary: Unlawful or illegitimate purposes\n  text: You agree not to use the Website Content or any service the Company provides\
  \ in an unlawful way or for an\n    unlawful or illegitimate purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/circle-medical/eligibility/circle-medical-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Circle Medical's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Primary Care
- Digital Health
- HIPAA
---
