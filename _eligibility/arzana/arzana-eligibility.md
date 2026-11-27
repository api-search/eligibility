---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are built for businesses. You may use them only for your business, and only if you can form a binding contract.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export-controlled data
    text: Send ITAR controlled technical data or Controlled Unclassified Information without telling us first, so we can host it in AWS GovCloud (US)
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
name: Arzana
provenance_date: '2026-11-09'
provider_name: Arzana
provider_slug: arzana
slug: arzana-eligibility
source_date: '2026-11-09'
source_filename: arzana-eligibility.yml
source_heading: Eligibility
source_page: https://www.arzana.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arzana\naid: arzana\nurl: https://www.arzana.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are built for businesses. You may use them only for your business, and only if you can form\n    a binding contract.\nrestricted_uses:\n- summary: Export-controlled data\n  text: Send ITAR controlled technical data or Controlled Unclassified Information without telling us first, so\n    we can host it in AWS GovCloud (US)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/arzana/eligibility/arzana-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Arzana's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Manufacturing
- ERP
- AI Agents
- Automation
- CRM
- Office Automation
- Distribution
- Y Combinator
---
