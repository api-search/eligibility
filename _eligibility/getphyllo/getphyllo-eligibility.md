---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you are accepting the Agreement on behalf of any Person (including a Minor) other than yourself, you represent and warrant that: (i) you have full legal authority to bind that Person to the Agreement'
    type: business
  minimum_age:
    text: in no event will such age be less than 16 years.
    value: '16'
  restricted_uses:
  - summary: Unlawful or harmful material
    text: 'You will not use Phyllo’s Offering to access, store, distribute or transmit any material that: (i) is unlawful, wrongful, tortious, libellous, slanderous or defamatory'
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
name: Phyllo
provenance_date: '2026-11-09'
provider_name: Phyllo
provider_slug: getphyllo
slug: getphyllo-eligibility
source_date: '2026-11-09'
source_filename: getphyllo-eligibility.yml
source_heading: Eligibility
source_page: https://www.getphyllo.com/end-user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Phyllo\naid: getphyllo\nurl: https://www.getphyllo.com/end-user-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If you are accepting the Agreement on behalf of any Person (including a Minor) other than yourself, you\n    represent and warrant that: (i) you have full legal authority to bind that Person to the Agreement'\nrestricted_uses:\n- summary: Unlawful or harmful material\n  text: 'You will not use Phyllo’s Offering to access, store, distribute or transmit any material that: (i) is unlawful,\n    wrongful, tortious, libellous,\
  \ slanderous or defamatory'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: in no event will such age be less than 16 years.\n"
source_yaml_url: https://artifacts.apis.io/getphyllo/eligibility/getphyllo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Phyllo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social Data
- Influencer Marketing
- Fintech
---
