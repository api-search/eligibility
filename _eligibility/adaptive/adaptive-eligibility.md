---
claim_count: 2
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
  - summary: Illegal or rights-violating use
    text: Use the Adaptive Services in any manner or for any purpose that violates any law or regulation, promotes illegal activities, violates any right of any person
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Use or otherwise access Adaptive Services until you have received approval from Adaptive which shall not be unreasonably withheld.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Adaptive
provenance_date: '2026-11-09'
provider_name: Adaptive
provider_slug: adaptive
slug: adaptive-eligibility
source_date: '2026-11-09'
source_filename: adaptive-eligibility.yml
source_heading: Eligibility
source_page: https://www.adaptive.build/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adaptive\naid: adaptive\nurl: https://www.adaptive.build/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or rights-violating use\n  text: Use the Adaptive Services in any manner or for any purpose that violates any law or regulation, promotes\n    illegal activities, violates any right of any person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Use or otherwise access Adaptive Services until you have received approval from Adaptive which shall not\n    be unreasonably withheld.\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adaptive/eligibility/adaptive-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Adaptive's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Accounting
- Project Accounting
- Construction Finance
- Accounts Payable
- AI Agents
- Software-as-a-Service
- Fintech
---
