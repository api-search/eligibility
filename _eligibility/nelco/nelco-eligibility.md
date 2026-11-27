---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You agree that you are only authorized to use the Site for your own personal use, and not for a commercial purpose except as expressly authorized by Nelco Solutions in writing.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial purpose without written authorization
    text: not for a commercial purpose except as expressly authorized by Nelco Solutions in writing
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
name: Nelco
provenance_date: '2026-11-10'
provider_name: Nelco
provider_slug: nelco
slug: nelco-eligibility
source_date: '2026-11-10'
source_filename: nelco-eligibility.yml
source_heading: Eligibility
source_page: https://www.nelcosolutions.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nelco\naid: nelco\nurl: https://www.nelcosolutions.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You agree that you are only authorized to use the Site for your own personal use, and not for a commercial\n    purpose except as expressly authorized by Nelco Solutions in writing.\nrestricted_uses:\n- summary: No commercial purpose without written authorization\n  text: not for a commercial purpose except as expressly authorized by Nelco Solutions in writing\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nelco/eligibility/nelco-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Nelco's own page on 2026-11-10.
synthetic: false
tags:
- Tax Forms
- Software Integration
- Electronic Filing
- Compliance
- Partners
---
