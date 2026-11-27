---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You represent and warrant that you are at least eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Services offered only for own use
    text: the Services are offered only for your use, and not for the use or benefit of any third party.
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
name: Wildfire
provenance_date: '2026-11-10'
provider_name: Wildfire
provider_slug: wildfire-corp-com
slug: wildfire-corp-com-eligibility
source_date: '2026-11-10'
source_filename: wildfire-corp-com-eligibility.yml
source_heading: Eligibility
source_page: https://support.wildfire-corp.com/for-wildlink-users/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wildfire\naid: wildfire-corp-com\nurl: https://support.wildfire-corp.com/for-wildlink-users/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Services offered only for own use\n  text: the Services are offered only for your use, and not for the use or benefit of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/wildfire-corp-com/eligibility/wildfire-corp-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Wildfire's own page on 2026-11-10.
synthetic: false
tags:
- Loyalty
- Rewards
- Consumer Insights
- Commerce Media
- Merchant Network
---
