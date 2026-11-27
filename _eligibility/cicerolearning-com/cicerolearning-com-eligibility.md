---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The parent or guardian who sets up an account, or any adult who uses the service on their own behalf.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Students under 18 self-enrolling
    text: Students under 18 may not enrol themselves or open their own account.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By creating an account you confirm that you are the parent or guardian of the student you are enrolling — or an adult enrolling for yourself
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cicero Learning
provenance_date: '2026-11-09'
provider_name: Cicero Learning
provider_slug: cicerolearning-com
slug: cicerolearning-com-eligibility
source_date: '2026-11-09'
source_filename: cicerolearning-com-eligibility.yml
source_heading: Eligibility
source_page: https://cicerolearning.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cicero Learning\naid: cicerolearning-com\nurl: https://cicerolearning.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The parent or guardian who sets up an account, or any adult who uses the service on their own behalf.\nrestricted_uses:\n- summary: Students under 18 self-enrolling\n  text: Students under 18 may not enrol themselves or open their own account.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By creating an account you confirm that you are the parent or guardian of the\
  \ student you are enrolling\n    — or an adult enrolling for yourself\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cicerolearning-com/eligibility/cicerolearning-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Cicero Learning's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Tutoring
- Homeschool
- Worldschooling
- Personalized Learning
---
