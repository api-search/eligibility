---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are not at least 13 years of age, do not access or use the Site.
    value: '13'
  restricted_uses:
  - summary: Use by minors under 18 without parental supervision
    text: If you are under the age of 18 (and over the age of 13), do not access or use this Site without the involvement and supervision of a parent or guardian.
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
name: Bondbloxx Investment
provenance_date: '2026-11-09'
provider_name: Bondbloxx Investment
provider_slug: bondbloxx-investment
slug: bondbloxx-investment-eligibility
source_date: '2026-11-09'
source_filename: bondbloxx-investment-eligibility.yml
source_heading: Eligibility
source_page: https://bondbloxxetf.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bondbloxx Investment\naid: bondbloxx-investment\nurl: https://bondbloxxetf.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Use by minors under 18 without parental supervision\n  text: If you are under the age of 18 (and over the age of 13), do not access or use this Site without the involvement\n    and supervision of a parent or guardian.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are not at least 13 years of age, do not access\
  \ or use the Site.\n"
source_yaml_url: https://artifacts.apis.io/bondbloxx-investment/eligibility/bondbloxx-investment-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Bondbloxx Investment's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- ETFs
- Fixed Income
- Investment
- Asset Management
---
