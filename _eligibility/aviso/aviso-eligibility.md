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
  - summary: Prohibited uses of Services
    text: 'Customer shall not use the Services to: (a) send spam or otherwise duplicative or unsolicited messages in violation of applicable laws'
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
name: Aviso
provenance_date: '2026-11-09'
provider_name: Aviso
provider_slug: aviso
slug: aviso-eligibility
source_date: '2026-11-09'
source_filename: aviso-eligibility.yml
source_heading: Eligibility
source_page: https://www.aviso.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aviso\naid: aviso\nurl: https://www.aviso.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited uses of Services\n  text: 'Customer shall not use the Services to: (a) send spam or otherwise duplicative or unsolicited messages\n    in violation of applicable laws'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aviso/eligibility/aviso-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Aviso's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Revenue Intelligence
- Sales
- Artificial Intelligence
- Forecasting
- Conversation Intelligence
- Revenue Operations
- Analytics
---
