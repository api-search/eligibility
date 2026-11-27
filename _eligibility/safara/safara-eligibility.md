---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are subject to U.S. export restrictions or are located in a jurisdiction subject to comprehensive U.S. trade sanctions.
  minimum_age:
    text: under no condition may you use the Site or Services if you are under the age of eighteen (18)
    value: '18'
  restricted_uses:
  - summary: Sanctioned jurisdictions and export-restricted users
    text: You may not use the Services if you are subject to U.S. export restrictions or are located in a jurisdiction subject to comprehensive U.S. trade sanctions.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Access to the Platform as an Advisor is by invitation or application only, and Drift may accept or decline any application, or condition access on additional criteria, in its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Safara
provenance_date: '2026-11-10'
provider_name: Safara
provider_slug: safara
slug: safara-eligibility
source_date: '2026-11-10'
source_filename: safara-eligibility.yml
source_heading: Eligibility
source_page: https://www.godrift.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Safara\naid: safara\nurl: https://www.godrift.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are subject to U.S. export restrictions or are located in a jurisdiction\n    subject to comprehensive U.S. trade sanctions.\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned jurisdictions and export-restricted users\n  text: You may not use the Services if you are subject to U.S. export restrictions or are located in a jurisdiction\n    subject to comprehensive U.S. trade sanctions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ true\n  text: Access to the Platform as an Advisor is by invitation or application only, and Drift may accept or decline\n    any application, or condition access on additional criteria, in its sole discretion.\nminimum_age:\n  value: '18'\n  text: under no condition may you use the Site or Services if you are under the age of eighteen (18)\n"
source_yaml_url: https://artifacts.apis.io/safara/eligibility/safara-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Safara's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
