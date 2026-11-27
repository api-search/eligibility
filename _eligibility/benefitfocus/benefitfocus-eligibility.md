---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or infringing use
    text: You agree not to use the Services or Content on this website in a manner that violates any applicable law, regulation or these Terms of Use.
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
name: Benefitfocus
provenance_date: '2026-11-09'
provider_name: Benefitfocus
provider_slug: benefitfocus
slug: benefitfocus-eligibility
source_date: '2026-11-09'
source_filename: benefitfocus-eligibility.yml
source_heading: Eligibility
source_page: https://www.benefitfocus.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Benefitfocus\naid: benefitfocus\nurl: https://www.benefitfocus.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or infringing use\n  text: You agree not to use the Services or Content on this website in a manner that violates any applicable law,\n    regulation or these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/benefitfocus/eligibility/benefitfocus-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Benefitfocus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Benefits
- Human Resources
- Software-as-a-Service
- Healthcare
- Cloud
---
