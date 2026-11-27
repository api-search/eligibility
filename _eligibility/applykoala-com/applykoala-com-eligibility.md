---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You need to be at least 18, or old enough to agree to these Terms where you live, to subscribe.
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful content
    text: store content that is illegal, harmful or someone else's private information without their permission
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
name: ApplyKoala
provenance_date: '2026-11-09'
provider_name: ApplyKoala
provider_slug: applykoala-com
slug: applykoala-com-eligibility
source_date: '2026-11-09'
source_filename: applykoala-com-eligibility.yml
source_heading: Eligibility
source_page: https://applykoala.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ApplyKoala\naid: applykoala-com\nurl: https://applykoala.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: store content that is illegal, harmful or someone else's private information without their permission\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You need to be at least 18, or old enough to agree to these Terms where you live, to subscribe.\n"
source_yaml_url: https://artifacts.apis.io/applykoala-com/eligibility/applykoala-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from ApplyKoala's own page on 2026-11-09.
synthetic: false
tags:
- Job-Tracker
- Artificial Intelligence
- Free
- Chrome Extension
- Recruiting
---
