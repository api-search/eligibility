---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Flinn is a business-to-business SaaS provider.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or contract-violating use
    text: Where Flinn becomes aware that customer-provided information may violate applicable law, third-party rights or the applicable contractual requirements, the matter is individually reviewed by Flinn.
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
name: Flinn
provenance_date: '2026-11-09'
provider_name: Flinn
provider_slug: flinn
slug: flinn-eligibility
source_date: '2026-11-09'
source_filename: flinn-eligibility.yml
source_heading: Eligibility
source_page: https://www.flinn.ai/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flinn\naid: flinn\nurl: https://www.flinn.ai/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Flinn is a business-to-business SaaS provider.\nrestricted_uses:\n- summary: Unlawful or contract-violating use\n  text: Where Flinn becomes aware that customer-provided information may violate applicable law, third-party rights\n    or the applicable contractual requirements, the matter is individually reviewed by Flinn.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/flinn/eligibility/flinn-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Flinn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medical Technology
- Medical Devices
- Regulatory
- Compliance
- Quality Management
- Post-Market Surveillance
- IVD
- Artificial Intelligence
---
