---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Radial makes no claims that Radial or any Services and related content are appropriate or may be accessed from outside the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No medical advice or emergency use
    text: Users should not rely on the Services for emergency medical treatment.
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
name: Radial Analytics
provenance_date: '2026-11-10'
provider_name: Radial Analytics
provider_slug: radialanalytics-com
slug: radialanalytics-com-eligibility
source_date: '2026-11-10'
source_filename: radialanalytics-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.radialcare.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Radial Analytics\naid: radialanalytics-com\nurl: https://www.radialcare.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Radial makes no claims that Radial or any Services and related content are appropriate or may be accessed\n    from outside the United States.\nentity_types: []\nrestricted_uses:\n- summary: No medical advice or emergency use\n  text: Users should not rely on the Services for emergency medical treatment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/radialanalytics-com/eligibility/radialanalytics-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Radial Analytics's own page on 2026-11-10.
synthetic: false
tags:
- Decision Support
- Value-Based Care
- ACO
- Payers
- Healthcare Analytics
- Clinical Decision Support
---
