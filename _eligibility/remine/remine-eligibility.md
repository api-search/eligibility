---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Website and the Services are directed to Visitors and Authorized Users in the United States.
  minimum_age:
    text: The Services are provided only for users eighteen years of age and older.
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
name: Remine
provenance_date: '2026-11-10'
provider_name: Remine
provider_slug: remine
slug: remine-eligibility
source_date: '2026-11-10'
source_filename: remine-eligibility.yml
source_heading: Eligibility
source_page: https://remine.com/tos-privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Remine\naid: remine\nurl: https://remine.com/tos-privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Website and the Services are directed to Visitors and Authorized Users in the United States.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are provided only for users eighteen years of age and older.\n"
source_yaml_url: https://artifacts.apis.io/remine/eligibility/remine-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Remine's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Property Data
- Mortgage Data
- Lead Generation
- Predictive Analytics
- MLS
---
