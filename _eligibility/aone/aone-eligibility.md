---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: your company’s name, company’s registration number, director’s name and director’s IC number
    type: business
  minimum_age:
    text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    value: '18'
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
name: AOne
provenance_date: '2026-11-09'
provider_name: AOne
provider_slug: aone
slug: aone-eligibility
source_date: '2026-11-09'
source_filename: aone-eligibility.yml
source_heading: Eligibility
source_page: https://aone.com.my/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AOne\naid: aone\nurl: https://aone.com.my/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: your company’s name, company’s registration number, director’s name and director’s IC number\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Service is intended only for access and use by individuals at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/aone/eligibility/aone-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from AOne's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- LMS
- School Management
- Tuition Centre
- Software-as-a-Service
- Malaysia
---
