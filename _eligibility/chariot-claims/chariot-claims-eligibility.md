---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use our Website if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
  minimum_age:
    text: Any use or access to the Website by anyone under eighteen (18) years of age is strictly prohibited and in violation of these Terms of Use.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: In any way that violates any applicable federal, state, local, or international law or regulation
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
name: Chariot Claims
provenance_date: '2026-11-09'
provider_name: Chariot Claims
provider_slug: chariot-claims
slug: chariot-claims-eligibility
source_date: '2026-11-09'
source_filename: chariot-claims-eligibility.yml
source_heading: Eligibility
source_page: https://www.chariotclaims.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chariot Claims\naid: chariot-claims\nurl: https://www.chariotclaims.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use our Website if you are a resident of a country embargoed by the United States, or are a\n    foreign person or entity blocked or denied by the United States government.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: In any way that violates any applicable federal, state, local, or international law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: Any use or access to the Website by anyone under eighteen (18) years of age is strictly prohibited and in\n    violation of these Terms of Use.\n"
source_yaml_url: https://artifacts.apis.io/chariot-claims/eligibility/chariot-claims-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Chariot Claims's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Legal Tech
- Claims
- Consumer Protection
---
