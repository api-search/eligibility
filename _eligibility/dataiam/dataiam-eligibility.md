---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 16 years old (or the age of majority in your jurisdiction, whichever is higher).
    type: individual
  minimum_age:
    text: You are at least 16 years old (or the age of majority in your jurisdiction, whichever is higher).
    value: '16'
  restricted_uses:
  - summary: Lawful use only
    text: You will use our Services only in compliance with these Terms, all applicable laws, and regulations.
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
name: Data I Am
provenance_date: '2026-11-09'
provider_name: Data I Am
provider_slug: dataiam
slug: dataiam-eligibility
source_date: '2026-11-09'
source_filename: dataiam-eligibility.yml
source_heading: Eligibility
source_page: https://dataiam.com/fix-and-load/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Data I Am\naid: dataiam\nurl: https://dataiam.com/fix-and-load/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 16 years old (or the age of majority in your jurisdiction, whichever is higher).\nrestricted_uses:\n- summary: Lawful use only\n  text: You will use our Services only in compliance with these Terms, all applicable laws, and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You are at least 16 years old (or\
  \ the age of majority in your jurisdiction, whichever is higher).\n"
source_yaml_url: https://artifacts.apis.io/dataiam/eligibility/dataiam-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Data I Am's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Salesforce
- Data Integration
- Financial Services
---
