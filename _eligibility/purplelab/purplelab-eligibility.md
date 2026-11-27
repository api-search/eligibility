---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: THE INDIVIDUAL OR LEGAL ENTITY WHO LICENSES ANY LICENSED MATERIALS FROM PURPLELAB
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sharing with pharmacies or prescribers
    text: You shall not share or otherwise disclose any Licensed Data with any pharmacies or prescribers
  - summary: Export restriction
    text: You shall not permit your Authorized Users to access or use any Service in a U.S.-embargoed country
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
name: PurpleLab
provenance_date: '2026-11-10'
provider_name: PurpleLab
provider_slug: purplelab
slug: purplelab-eligibility
source_date: '2026-11-10'
source_filename: purplelab-eligibility.yml
source_heading: Eligibility
source_page: https://purplelab.com/terms-and-conditions-2026-01-29
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PurpleLab\naid: purplelab\nurl: https://purplelab.com/terms-and-conditions-2026-01-29\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: THE INDIVIDUAL OR LEGAL ENTITY WHO LICENSES ANY LICENSED MATERIALS FROM PURPLELAB\nrestricted_uses:\n- summary: No sharing with pharmacies or prescribers\n  text: You shall not share or otherwise disclose any Licensed Data with any pharmacies or prescribers\n- summary: Export restriction\n  text: You shall not permit your Authorized Users to access or use any Service in a U.S.-embargoed country\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/purplelab/eligibility/purplelab-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from PurpleLab's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Health Data
- Real-World Data
- Real-World Evidence
- Medical Claims
- Pharmacy Claims
- Provider Data
- Healthcare Analytics
- Life Sciences
- Data Products
- HIPAA
- Company
---
