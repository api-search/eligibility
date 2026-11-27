---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You affirm that you are either more than 18 years of age, or an emancipated minor, or possess legal parental or guardian consent
    type: individual
  minimum_age:
    text: In any case, you affirm that you are over the age of 18, as the Service is not intended for children under 18.
    value: '18'
  restricted_uses:
  - summary: Lawful non-commercial use only
    text: The Services may be used and accessed for lawful and non-commercial purposes only.
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
name: Ranker
provenance_date: '2026-11-10'
provider_name: Ranker
provider_slug: ranker
slug: ranker-eligibility
source_date: '2026-11-10'
source_filename: ranker-eligibility.yml
source_heading: Eligibility
source_page: https://www.ranker.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ranker\naid: ranker\nurl: https://www.ranker.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You affirm that you are either more than 18 years of age, or an emancipated minor, or possess legal parental\n    or guardian consent\nrestricted_uses:\n- summary: Lawful non-commercial use only\n  text: The Services may be used and accessed for lawful and non-commercial purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In any case,\
  \ you affirm that you are over the age of 18, as the Service is not intended for children under\n    18.\n"
source_yaml_url: https://artifacts.apis.io/ranker/eligibility/ranker-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ranker's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Entertainment
- Media
- Rankings
- Audience Intelligence
- Data Licensing
- Market Research
---
