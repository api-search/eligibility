---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual accessing or using any of the Services on behalf of, or for the benefit of, any corporation, partnership, or other entity with which you are associated (a "Company")
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Support Services for internal use only
    text: Support Services are provided to Company solely for Company's internal use of such Platform
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to access and use the Platform, Company must register for an account and select a subscription
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: RunReveal
provenance_date: '2026-11-10'
provider_name: RunReveal
provider_slug: runreveal
slug: runreveal-eligibility
source_date: '2026-11-10'
source_filename: runreveal-eligibility.yml
source_heading: Eligibility
source_page: https://runreveal.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RunReveal\naid: runreveal\nurl: https://runreveal.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are an individual accessing or using any of the Services on behalf of, or for the benefit of, any\n    corporation, partnership, or other entity with which you are associated (a \"Company\")\nrestricted_uses:\n- summary: Support Services for internal use only\n  text: Support Services are provided to Company solely for Company's internal use of such Platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: In order to access and use the Platform, Company must register for an account and select a subscription\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/runreveal/eligibility/runreveal-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from RunReveal's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- SIEM
- Security Log Management
- Detection Engineering
- Threat Detection
- Incident Response
- Observability
- SQL
- MCP
- Artificial Intelligence
---
