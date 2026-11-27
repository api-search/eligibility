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
  - summary: Unlawful or harmful transmissions
    text: 'you may not transmit to AECOM in any way any communications, text, graphics or other information that: (a) is obscene, fraudulent, indecent, or that defames, abuses, harasses, or threatens others'
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
name: AECOM
provenance_date: '2026-11-09'
provider_name: AECOM
provider_slug: aecom
slug: aecom-eligibility
source_date: '2026-11-09'
source_filename: aecom-eligibility.yml
source_heading: Eligibility
source_page: https://aecom.com/terms-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AECOM\naid: aecom\nurl: https://aecom.com/terms-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful transmissions\n  text: 'you may not transmit to AECOM in any way any communications, text, graphics or other information that:\n    (a) is obscene, fraudulent, indecent, or that defames, abuses, harasses, or threatens others'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aecom/eligibility/aecom-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from AECOM's own page on 2026-11-09.
synthetic: false
tags:
- Engineering
- Infrastructure
- Construction
- Environmental Services
- Transportation
- Fortune 500
---
