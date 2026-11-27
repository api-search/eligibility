---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Order Form and/or Statement of Work will not be deemed entered into until signed by an authorized representative of each Party.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Named users only
    text: Users are named and sharing of a user is not permitted.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Order Form and/or Statement of Work will not be deemed entered into until signed by an authorized representative of each Party.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Glia
provenance_date: '2026-11-09'
provider_name: Glia
provider_slug: glia
slug: glia-eligibility
source_date: '2026-11-09'
source_filename: glia-eligibility.yml
source_heading: Eligibility
source_page: https://www.glia.com/security-compliance/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Glia\naid: glia\nurl: https://www.glia.com/security-compliance/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Order Form and/or Statement of Work will not be deemed entered into until signed by an authorized representative\n    of each Party.\nrestricted_uses:\n- summary: Named users only\n  text: Users are named and sharing of a user is not permitted.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Order Form and/or Statement of Work will not be deemed entered into until signed by an authorized\
  \ representative\n    of each Party.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/glia/eligibility/glia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Glia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Service
- Contact Center
- Banking
- Credit Union
- Financial Services
- Conversational AI
- Voice
- Co-Browsing
- Serverless
---
