---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a company or other legal entity, the Services may only be accessed and used by your Authorized Users for the sole purpose of performing their job functions for you.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-compete use of Services
    text: Use the Services to develop, commercialize, license or sell any product, service or technology that could, directly or indirectly, compete with the Services or Coffee;
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
name: Coffee
provenance_date: '2026-11-09'
provider_name: Coffee
provider_slug: coffee-ai
slug: coffee-ai-eligibility
source_date: '2026-11-09'
source_filename: coffee-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.coffee.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coffee\naid: coffee-ai\nurl: https://www.coffee.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are a company or other legal entity, the Services may only be accessed and used by your Authorized\n    Users for the sole purpose of performing their job functions for you.\nrestricted_uses:\n- summary: Non-compete use of Services\n  text: Use the Services to develop, commercialize, license or sell any product, service or technology that could,\n    directly or indirectly, compete with the Services or Coffee;\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coffee-ai/eligibility/coffee-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Coffee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- CRM
- Sales
- Automation
---
