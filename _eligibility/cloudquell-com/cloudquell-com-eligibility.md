---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended solely for business and professional use.
    type: business
  minimum_age:
    text: You must be at least 18 years of age and legally able to enter into a binding contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: Business use only, not consumer
    text: By creating an account you represent that you are acting in the course of a trade, business, or profession — whether as a company, sole trader, or self-employed professional — and not as a consumer.
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
name: CloudQuell
provenance_date: '2026-11-09'
provider_name: CloudQuell
provider_slug: cloudquell-com
slug: cloudquell-com-eligibility
source_date: '2026-11-09'
source_filename: cloudquell-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.cloudquell.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CloudQuell\naid: cloudquell-com\nurl: https://www.cloudquell.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended solely for business and professional use.\nrestricted_uses:\n- summary: Business use only, not consumer\n  text: By creating an account you represent that you are acting in the course of a trade, business, or profession\n    — whether as a company, sole trader, or self-employed professional — and not as a consumer.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You must be at least 18 years of age and legally able to enter into a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cloudquell-com/eligibility/cloudquell-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CloudQuell's own page on 2026-11-09.
synthetic: false
tags:
- Company
- FinOps
- Cloud Cost Management
- AI Cost Management
- Cost Allocation
- Anomaly Detection
- Multi-Cloud
- MCP
---
