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
  - text: You are at least 18 years of age.
    type: individual
  minimum_age:
    text: You are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Not for users with ileostomy, colostomy or on chemotherapy (test)
    text: in order to do a Gut Health Test, you must not have undergone an ileostomy or colostomy or be undergoing chemotherapy treatment.
  - summary: Strongly discouraged for active eating disorders
    text: We strongly discourage use of the app by anyone with an active eating disorder.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: We reserve the right to accept or reject access to the ZOE app for any reason, including because you do not meet these criteria.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ZOE
provenance_date: '2026-11-09'
provider_name: ZOE
provider_slug: joinzoe
slug: joinzoe-eligibility
source_date: '2026-11-09'
source_filename: joinzoe-eligibility.yml
source_heading: Eligibility
source_page: https://zoe.com/en-gb/terms?lead_id=580b89f8-0b57-4c17-ac72-f868f11220f8
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZOE\naid: joinzoe\nurl: https://zoe.com/en-gb/terms?lead_id=580b89f8-0b57-4c17-ac72-f868f11220f8\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  - IE\n  - NL\n  excluded: []\n  text: You are located in the United Kingdom, Republic of Ireland or the Netherlands.\nentity_types:\n- type: individual\n  text: You are at least 18 years of age.\nrestricted_uses:\n- summary: Not for users with ileostomy, colostomy or on chemotherapy (test)\n  text: in order to do a Gut Health Test, you must not have undergone an ileostomy or colostomy or be undergoing\n    chemotherapy treatment.\n- summary: Strongly discouraged\
  \ for active eating disorders\n  text: We strongly discourage use of the app by anyone with an active eating disorder.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: We reserve the right to accept or reject access to the ZOE app for any reason, including because you do\n    not meet these criteria.\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/joinzoe/eligibility/joinzoe-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from ZOE's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Nutrition
- Wellness
- Personalized Nutrition
- Consumer Health
- Gut Health
- Direct to Consumer
---
