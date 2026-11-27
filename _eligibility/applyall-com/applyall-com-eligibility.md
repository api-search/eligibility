---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use our Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use our Services.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: You must not use our Services for any illegal or unauthorized purposes.
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
name: ApplyAll
provenance_date: '2026-11-09'
provider_name: ApplyAll
provider_slug: applyall-com
slug: applyall-com-eligibility
source_date: '2026-11-09'
source_filename: applyall-com-eligibility.yml
source_heading: Eligibility
source_page: https://applyall.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ApplyAll\naid: applyall-com\nurl: https://applyall.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use our Services.\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: You must not use our Services for any illegal or unauthorized purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction)\
  \ to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/applyall-com/eligibility/applyall-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ApplyAll's own page on 2026-11-09.
synthetic: false
tags:
- Job Search
- Artificial Intelligence
- InterviewGuarantee
- Career Coaching
- White Label
---
