---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    - IE
    - NL
    text: You are located in the United Kingdom, Republic of Ireland or the Netherlands.
  entity_types:
  - text: Only you are permitted to use the account and you must not share your password with anyone else
    type: individual
  minimum_age:
    text: You are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Gut Health Test exclusions
    text: you must not have undergone an ileostomy or colostomy or be undergoing chemotherapy treatment.
  - summary: Eating disorder warning
    text: We strongly discourage use of the app by anyone with an active eating disorder.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We reserve the right to accept or reject access to the ZOE app for any reason, including because you do not meet these criteria.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: joinzoe
provenance_date: '2026-11-09'
provider_name: joinzoe
provider_slug: joinzoe-com
slug: joinzoe-com-eligibility
source_date: '2026-11-09'
source_filename: joinzoe-com-eligibility.yml
source_heading: Eligibility
source_page: https://zoe.com/en-gb/terms?lead_id=1e10ed18-c80b-4294-898f-91acd77a0633
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: joinzoe\naid: joinzoe-com\nurl: https://zoe.com/en-gb/terms?lead_id=1e10ed18-c80b-4294-898f-91acd77a0633\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  - IE\n  - NL\n  excluded: []\n  text: You are located in the United Kingdom, Republic of Ireland or the Netherlands.\nentity_types:\n- type: individual\n  text: Only you are permitted to use the account and you must not share your password with anyone else\nrestricted_uses:\n- summary: Gut Health Test exclusions\n  text: you must not have undergone an ileostomy or colostomy or be undergoing chemotherapy treatment.\n- summary: Eating disorder warning\n\
  \  text: We strongly discourage use of the app by anyone with an active eating disorder.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We reserve the right to accept or reject access to the ZOE app for any reason, including because you do\n    not meet these criteria.\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/joinzoe-com/eligibility/joinzoe-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from joinzoe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Nutrition
- Gut Health
- Science
- Wellness
---
