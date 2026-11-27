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
  - summary: Export and sanctions compliance
    text: You will not directly or indirectly export, re-export, or transfer the Free Service, Subscription Service or Consulting Services to prohibited countries or individuals
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
name: Cloverpop
provenance_date: '2026-11-09'
provider_name: Cloverpop
provider_slug: cloverpop
slug: cloverpop-eligibility
source_date: '2026-11-09'
source_filename: cloverpop-eligibility.yml
source_heading: Eligibility
source_page: https://www.cloverpop.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cloverpop\naid: cloverpop\nurl: https://www.cloverpop.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: You will not directly or indirectly export, re-export, or transfer the Free Service, Subscription Service\n    or Consulting Services to prohibited countries or individuals\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cloverpop/eligibility/cloverpop-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Cloverpop's own page on 2026-11-09.
synthetic: false
tags:
- Decision Intelligence
- AI Assistant
- Business Analytics
- Supply Chain
- Sales & Marketing
- Pharma R&D
- Innovation
---
