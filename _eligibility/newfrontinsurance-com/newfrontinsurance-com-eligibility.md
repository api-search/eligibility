---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Newfront Insurance Services is a trade name licensed to sell insurance products in all 50 states, the District of Columbia, and Puerto Rico.
  entity_types:
  - text: These Terms permit you to use the Services for your internal business use only.
    type: business
  minimum_age:
    text: THE SERVICES ARE ONLY AVAILABLE TO USERS WHO ARE 16 YEARS OF AGE OR OLDER.
    value: '16'
  restricted_uses:
  - summary: Dangerous, illegal or malicious activities
    text: Use or allow others to use the Services to (a) perform or facilitate dangerous, illegal, or malicious activities
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
name: Newfront
provenance_date: '2026-11-10'
provider_name: Newfront
provider_slug: newfrontinsurance-com
slug: newfrontinsurance-com-eligibility
source_date: '2026-11-10'
source_filename: newfrontinsurance-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.newfront.com:443/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Newfront\naid: newfrontinsurance-com\nurl: https://www.newfront.com:443/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Newfront Insurance Services is a trade name licensed to sell insurance products in all 50 states, the District\n    of Columbia, and Puerto Rico.\nentity_types:\n- type: business\n  text: These Terms permit you to use the Services for your internal business use only.\nrestricted_uses:\n- summary: Dangerous, illegal or malicious activities\n  text: Use or allow others to use the Services to (a) perform or facilitate dangerous, illegal, or malicious activities\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: THE SERVICES ARE ONLY AVAILABLE TO USERS WHO ARE 16 YEARS OF AGE OR OLDER.\n"
source_yaml_url: https://artifacts.apis.io/newfrontinsurance-com/eligibility/newfrontinsurance-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Newfront's own page on 2026-11-10.
synthetic: false
tags:
- Business Insurance
- Benefits Brokerage
- Total Rewards
- Retirement Services
- Technology
- Risk Management
- WTW
---
