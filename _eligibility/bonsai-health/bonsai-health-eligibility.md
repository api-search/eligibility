---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: (2) YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH BONSAI HEALTH
    value: null
  restricted_uses:
  - summary: No time-critical or mission-critical use
    text: use the Services in connection with any of Your time-critical or mission-critical functions
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
name: Bonsai Health
provenance_date: '2026-11-09'
provider_name: Bonsai Health
provider_slug: bonsai-health
slug: bonsai-health-eligibility
source_date: '2026-11-09'
source_filename: bonsai-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.bonsaihealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bonsai Health\naid: bonsai-health\nurl: https://www.bonsaihealth.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No time-critical or mission-critical use\n  text: use the Services in connection with any of Your time-critical or mission-critical functions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: (2) YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH BONSAI HEALTH\n"
source_yaml_url: https://artifacts.apis.io/bonsai-health/eligibility/bonsai-health-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Bonsai Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Patient Engagement
- Automation
---
