---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
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
name: BetterDoctor
provenance_date: '2026-11-10'
provider_name: BetterDoctor
provider_slug: questanalytics-com
slug: questanalytics-com-eligibility
source_date: '2026-11-10'
source_filename: questanalytics-com-eligibility.yml
source_heading: Eligibility
source_page: https://questanalytics.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BetterDoctor\naid: questanalytics-com\nurl: https://questanalytics.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/questanalytics-com/eligibility/questanalytics-com-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from BetterDoctor's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Data Verification
- Provider Network
- Analytics
---
