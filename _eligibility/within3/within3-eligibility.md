---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Within3 makes no claims that the content is appropriate or may be downloaded outside of the United States, or that Within3’s practices and policies will comply with the laws of other countries or states.
  entity_types:
  - text: To register and obtain an account, you must be a licensed physician or a research professional in the healthcare sector.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: 'Your activities on the Site shall not: (a) violate any law, statute, ordinance or regulation'
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
name: Within3
provenance_date: '2026-11-10'
provider_name: Within3
provider_slug: within3
slug: within3-eligibility
source_date: '2026-11-10'
source_filename: within3-eligibility.yml
source_heading: Eligibility
source_page: https://within3.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Within3\naid: within3\nurl: https://within3.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Within3 makes no claims that the content is appropriate or may be downloaded outside of the United States,\n    or that Within3’s practices and policies will comply with the laws of other countries or states.\nentity_types:\n- type: individual\n  text: To register and obtain an account, you must be a licensed physician or a research professional in the healthcare\n    sector.\nrestricted_uses:\n- summary: Lawful use only\n  text: 'Your activities on the Site shall not: (a)\
  \ violate any law, statute, ordinance or regulation'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/within3/eligibility/within3-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Within3's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Life Sciences
- Medical Affairs
- Insights Management
- Virtual Engagement
- Pharmaceuticals
---
