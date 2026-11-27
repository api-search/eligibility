---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To register and create an Account, you must select an account designation and password and provide certain personal information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ResMan
provenance_date: '2026-11-10'
provider_name: ResMan
provider_slug: resman
slug: resman-eligibility
source_date: '2026-11-10'
source_filename: resman-eligibility.yml
source_heading: Eligibility
source_page: https://www.myresman.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ResMan\naid: resman\nurl: https://www.myresman.com/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To register and create an Account, you must select an account designation and password and provide certain\n    personal information.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/resman/eligibility/resman-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from ResMan's own page on 2026-11-10.
synthetic: false
tags:
- Property Management
- Software-as-a-Service
- Real Estate
- Artificial Intelligence
- Multifamily
---
