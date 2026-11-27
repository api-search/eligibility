---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are not available to users who are not residents of the United States.
  entity_types:
  - text: The Services are provided for your personal and non-commercial use.
    type: individual
  minimum_age:
    text: you are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: The Services are provided for your personal and non-commercial use.
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
name: Atticus
provenance_date: '2026-11-09'
provider_name: Atticus
provider_slug: atticus
slug: atticus-eligibility
source_date: '2026-11-09'
source_filename: atticus-eligibility.yml
source_heading: Eligibility
source_page: https://www.atticus.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atticus\naid: atticus\nurl: https://www.atticus.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are not available to users who are not residents of the United States.\nentity_types:\n- type: individual\n  text: The Services are provided for your personal and non-commercial use.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: The Services are provided for your personal and non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least eighteen\
  \ (18) years old\n"
source_yaml_url: https://artifacts.apis.io/atticus/eligibility/atticus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Atticus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Legal
- Legal Tech
- Disability Benefits
- Workers Compensation
- Government Benefits
- Access to Justice
---
