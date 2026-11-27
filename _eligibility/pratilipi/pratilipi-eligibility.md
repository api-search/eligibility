---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: represent that You are above 18 (eighteen) years of age and have the authority to enter into a binding contract with Company. If You are under 18 (eighteen) years of age, You must obtain consent from Your parent(s) or authorized legal guardian(s)
    type: individual
  minimum_age:
    text: represent that You are above 18 (eighteen) years of age
    value: '18'
  restricted_uses:
  - summary: Illegal activities
    text: Not use the Services to perform any illegal activities nor solicit the performance of any illegal or any activity which leads to violation of third party’s rights.
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
name: Pratilipi
provenance_date: '2026-11-10'
provider_name: Pratilipi
provider_slug: pratilipi
slug: pratilipi-eligibility
source_date: '2026-11-10'
source_filename: pratilipi-eligibility.yml
source_heading: Eligibility
source_page: https://english.pratilipi.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pratilipi\naid: pratilipi\nurl: https://english.pratilipi.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: represent that You are above 18 (eighteen) years of age and have the authority to enter into a binding contract\n    with Company. If You are under 18 (eighteen) years of age, You must obtain consent from Your parent(s) or authorized\n    legal guardian(s)\nrestricted_uses:\n- summary: Illegal activities\n  text: Not use the Services to perform any illegal activities nor solicit the performance of any illegal\
  \ or any\n    activity which leads to violation of third party’s rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: represent that You are above 18 (eighteen) years of age\n"
source_yaml_url: https://artifacts.apis.io/pratilipi/eligibility/pratilipi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Pratilipi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Storytelling
- Publishing
- Content
- Media
- Audio
- Comics
- India
- Consumer
---
