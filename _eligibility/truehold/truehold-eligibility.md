---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Services for use only by persons located in the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited conduct
    text: 'You agree not to use the Services: In any way that violates any applicable federal, state, local, or international law or regulation.'
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
name: Truehold
provenance_date: '2026-11-10'
provider_name: Truehold
provider_slug: truehold
slug: truehold-eligibility
source_date: '2026-11-10'
source_filename: truehold-eligibility.yml
source_heading: Eligibility
source_page: https://www.truehold.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Truehold\naid: truehold\nurl: https://www.truehold.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Services for use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited conduct\n  text: 'You agree not to use the Services: In any way that violates any applicable federal, state, local, or international\n    law or regulation.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/truehold/eligibility/truehold-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Truehold's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Residential Real Estate
- Sale-Leaseback
- Home Equity
- Property Investment
- Lending
- Financial Services
---
