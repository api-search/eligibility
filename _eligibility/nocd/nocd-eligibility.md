---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: if you are under the age of eighteen, you must receive your parent or guardian's permission to access the Application.
    value: '18'
  restricted_uses:
  - summary: No unlawful use
    text: you warrant to the Company that you will not use the Application for any purpose that is unlawful or prohibited by these Terms.
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
name: NOCD
provenance_date: '2026-11-10'
provider_name: NOCD
provider_slug: nocd
slug: nocd-eligibility
source_date: '2026-11-10'
source_filename: nocd-eligibility.yml
source_heading: Eligibility
source_page: https://www.treatmyocd.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NOCD\naid: nocd\nurl: https://www.treatmyocd.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No unlawful use\n  text: you warrant to the Company that you will not use the Application for any purpose that is unlawful or prohibited\n    by these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if you are under the age of eighteen, you must receive your parent or guardian's permission to access the\n    Application.\n"
source_yaml_url: https://artifacts.apis.io/nocd/eligibility/nocd-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from NOCD's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Mental Health
- Telehealth
- Digital Health
- Therapy
- Behavioral Health
- Consumer Applications
---
