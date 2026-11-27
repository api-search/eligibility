---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Website is not intended for any children under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Adults only
    text: The Website is intended for adults only. The Website is not intended for any children under the age of 18.
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
name: YourPath
provenance_date: '2026-11-10'
provider_name: YourPath
provider_slug: yourpath
slug: yourpath-eligibility
source_date: '2026-11-10'
source_filename: yourpath-eligibility.yml
source_heading: Eligibility
source_page: https://yourpathhealth.org/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: YourPath\naid: yourpath\nurl: https://yourpathhealth.org/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Adults only\n  text: The Website is intended for adults only. The Website is not intended for any children under the age of 18.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website is not intended for any children under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/yourpath/eligibility/yourpath-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from YourPath's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Mental Health
- Telehealth
- SubstanceUse
---
