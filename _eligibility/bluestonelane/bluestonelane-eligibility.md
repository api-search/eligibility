---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This Site may be accessed from countries other than the United States.
  entity_types:
  - text: for the purpose of shopping for personal items sold on the Site and not for any commercial use or use on behalf of any third party
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 18 years old or visiting the Site under the supervision of a parent or guardian.
    value: '18'
  restricted_uses:
  - summary: Commercial or third-party use
    text: not for any commercial use or use on behalf of any third party, except as explicitly permitted by Bluestone Lane in advance
  - summary: Automated use of the system
    text: Involves any automated use of the system such as, but not limited to, using scripts to add friends or send comments or messages
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
name: Bluestonelane
provenance_date: '2026-11-09'
provider_name: Bluestonelane
provider_slug: bluestonelane
slug: bluestonelane-eligibility
source_date: '2026-11-09'
source_filename: bluestonelane-eligibility.yml
source_heading: Eligibility
source_page: https://bluestonelane.com/policies/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bluestonelane\naid: bluestonelane\nurl: https://bluestonelane.com/policies/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This Site may be accessed from countries other than the United States.\nentity_types:\n- type: individual\n  text: for the purpose of shopping for personal items sold on the Site and not for any commercial use or use on\n    behalf of any third party\nrestricted_uses:\n- summary: Commercial or third-party use\n  text: not for any commercial use or use on behalf of any third party, except as explicitly permitted by Bluestone\n    Lane in advance\n\
  - summary: Automated use of the system\n  text: Involves any automated use of the system such as, but not limited to, using scripts to add friends or send\n    comments or messages\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years old or visiting the Site under the supervision\n    of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/bluestonelane/eligibility/bluestonelane-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Bluestonelane's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coffee
- Retail
- Subscription
- Sustainability
---
