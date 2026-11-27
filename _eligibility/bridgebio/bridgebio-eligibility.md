---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This site is intended for U.S. residents.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No medical advice reliance
    text: Our Sites are not intended to provide medical advice or diagnose or treat any disease.
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
name: BridgeBio
provenance_date: '2026-11-09'
provider_name: BridgeBio
provider_slug: bridgebio
slug: bridgebio-eligibility
source_date: '2026-11-09'
source_filename: bridgebio-eligibility.yml
source_heading: Eligibility
source_page: https://bridgebio.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BridgeBio\naid: bridgebio\nurl: https://bridgebio.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This site is intended for U.S. residents.\nentity_types: []\nrestricted_uses:\n- summary: No medical advice reliance\n  text: Our Sites are not intended to provide medical advice or diagnose or treat any disease.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bridgebio/eligibility/bridgebio-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from BridgeBio's own page on 2026-11-09.
synthetic: false
tags:
- Biotechnology
- Genetics
- Precision Medicine
- Drug Development
- Healthcare
---
