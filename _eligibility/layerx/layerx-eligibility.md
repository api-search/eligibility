---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 当社が所定の方法により本APIの利用を承諾した法人、団体、組織又は個人等を指します。
    type: business
  - text: 当社が所定の方法により本APIの利用を承諾した法人、団体、組織又は個人等を指します。
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Purpose-limited use
    text: API契約者は、当該目的の範囲を超えて本APIを利用することはできません。
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
name: LayerX
provenance_date: '2026-11-09'
provider_name: LayerX
provider_slug: layerx
slug: layerx-eligibility
source_date: '2026-11-09'
source_filename: layerx-eligibility.yml
source_heading: Eligibility
source_page: https://bakuraku.jp/terms/api-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LayerX\naid: layerx\nurl: https://bakuraku.jp/terms/api-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 当社が所定の方法により本APIの利用を承諾した法人、団体、組織又は個人等を指します。\n- type: individual\n  text: 当社が所定の方法により本APIの利用を承諾した法人、団体、組織又は個人等を指します。\nrestricted_uses:\n- summary: Purpose-limited use\n  text: API契約者は、当該目的の範囲を超えて本APIを利用することはできません。\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/layerx/eligibility/layerx-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from LayerX's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Japan
- Back Office
- Expense Management
- Invoicing
- Accounts Payable
- Workflows
- Approvals
- Accounting
- Payroll
- Attendance
- Corporate Cards
- Artificial Intelligence
- AI Agents
- Document Processing
- Software-as-a-Service
- Enterprise Software
- Fintech
---
