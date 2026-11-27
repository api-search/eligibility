---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - DE
    text: Eligible to participate are natural persons aged 18 or over who are resident in the Federal Republic of Germany
  entity_types:
  - text: Eligible to participate are natural persons aged 18 or over who are resident in the Federal Republic of Germany
    type: individual
  minimum_age:
    text: Eligible to participate are natural persons aged 18 or over
    value: '18'
  restricted_uses:
  - summary: Provider and rental devices excluded
    text: 'Expressly excluded from the Old for New programme are: (Former) Provider FRITZ!Box devices, i.e. devices provided by an internet/telecommunications provider'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Provider reserves the right to verify this and, in the event of suspected misuse, to request supporting evidence.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FRITZ! (formerly AVM, FRITZ!Box)
provenance_date: '2026-11-09'
provider_name: FRITZ! (formerly AVM, FRITZ!Box)
provider_slug: fritz-com
slug: fritz-com-eligibility
source_date: '2026-11-09'
source_filename: fritz-com-eligibility.yml
source_heading: Eligibility
source_page: https://fritz.com/en/policies/legal-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FRITZ! (formerly AVM, FRITZ!Box)\naid: fritz-com\nurl: https://fritz.com/en/policies/legal-notice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - DE\n  excluded: []\n  text: Eligible to participate are natural persons aged 18 or over who are resident in the Federal Republic of\n    Germany\nentity_types:\n- type: individual\n  text: Eligible to participate are natural persons aged 18 or over who are resident in the Federal Republic of\n    Germany\nrestricted_uses:\n- summary: Provider and rental devices excluded\n  text: 'Expressly excluded from the Old for New programme are: (Former) Provider FRITZ!Box\
  \ devices, i.e. devices\n    provided by an internet/telecommunications provider'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Provider reserves the right to verify this and, in the event of suspected misuse, to request supporting\n    evidence.\nminimum_age:\n  value: '18'\n  text: Eligible to participate are natural persons aged 18 or over\n"
source_yaml_url: https://artifacts.apis.io/fritz-com/eligibility/fritz-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from FRITZ! (formerly AVM, FRITZ!Box)'s own page on 2026-11-09.
synthetic: false
tags:
- Router
- Mesh Wi‑Fi
- Smart Home
- Telephony
---
