---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old or the age of majority in your state or country of residence, whichever is older, to use the Services.
    value: '18'
  restricted_uses:
  - summary: Export-restricted countries and parties
    text: Any software from our Services shall be not be exported or re-exported (i) into (or to a national or resident of) Cuba, Sudan, Iraq, Libya, Crimea – Region of Ukraine, North Korea, Iran, Syria, or any other country to which the U.S. has embargoed goods
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
name: P.F. Chang's
provenance_date: '2026-11-10'
provider_name: P.F. Chang's
provider_slug: pf-changs
slug: pf-changs-eligibility
source_date: '2026-11-10'
source_filename: pf-changs-eligibility.yml
source_heading: Eligibility
source_page: https://www.pfchangs.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: P.F. Chang's\naid: pf-changs\nurl: https://www.pfchangs.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export-restricted countries and parties\n  text: Any software from our Services shall be not be exported or re-exported (i) into (or to a national or resident\n    of) Cuba, Sudan, Iraq, Libya, Crimea – Region of Ukraine, North Korea, Iran, Syria, or any other country to\n    which the U.S. has embargoed goods\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: You must be at least 18 years old or the age of majority in your state or country of residence, whichever\n    is older, to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/pf-changs/eligibility/pf-changs-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from P.F. Chang's's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Restaurant
- Dining
- Food
- Hospitality
---
