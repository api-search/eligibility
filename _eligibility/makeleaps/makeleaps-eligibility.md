---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 当社が申込みを承諾した法人または個人
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: ただし、当社は、理由を問わず、その裁量によりユーザーの申込みを拒絶することがあります。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MakeLeaps
provenance_date: '2026-11-10'
provider_name: MakeLeaps
provider_slug: makeleaps
slug: makeleaps-eligibility
source_date: '2026-11-10'
source_filename: makeleaps-eligibility.yml
source_heading: Eligibility
source_page: https://www.makeleaps.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MakeLeaps\naid: makeleaps\nurl: https://www.makeleaps.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 当社が申込みを承諾した法人または個人\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: ただし、当社は、理由を問わず、その裁量によりユーザーの申込みを拒絶することがあります。\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/makeleaps/eligibility/makeleaps-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from MakeLeaps's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Invoicing
- Billing
- Accounting
- Finance
- Payments
- Document Management
- E-Invoicing
- Software-as-a-Service
- Japan
- Ricoh
---
