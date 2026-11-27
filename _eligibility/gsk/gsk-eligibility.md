---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: GSK makes no representation that material in the site is appropriate or available for use outside of the territory of the intended audience.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No medical advice reliance
    text: nothing on this website should be construed as providing any kind of medical advice or recommendation, and should not be relied on as the basis for any decision or action.
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
name: GSK
provenance_date: '2026-11-09'
provider_name: GSK
provider_slug: gsk
slug: gsk-eligibility
source_date: '2026-11-09'
source_filename: gsk-eligibility.yml
source_heading: Eligibility
source_page: https://www.gsk.com/en-gb/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GSK\naid: gsk\nurl: https://www.gsk.com/en-gb/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: GSK makes no representation that material in the site is appropriate or available for use outside of the\n    territory of the intended audience.\nentity_types: []\nrestricted_uses:\n- summary: No medical advice reliance\n  text: nothing on this website should be construed as providing any kind of medical advice or recommendation, and\n    should not be relied on as the basis for any decision or action.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n \
  \ text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gsk/eligibility/gsk-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from GSK's own page on 2026-11-09.
synthetic: false
tags:
- Pharmaceuticals
- Biotechnology
- Vaccines
- HIV
- Oncology
- Healthcare
- Clinical Trials
---
