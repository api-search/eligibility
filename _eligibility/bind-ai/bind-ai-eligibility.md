---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are operated by us in the United States.
  entity_types:
  - text: you must be an authorized representative of a company or entity invited and onboarded to the Services through an insurance broker with a Platform subscription
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: you will not export or re-export, directly or indirectly, the Services and/or other information or materials provided by Bind AI hereunder, to any country for which the United States or any other relevant jurisdiction requires any export license
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you need to create an account on the Platform through the link or invitation provided by Your Broker
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bind AI
provenance_date: '2026-11-09'
provider_name: Bind AI
provider_slug: bind-ai
slug: bind-ai-eligibility
source_date: '2026-11-09'
source_filename: bind-ai-eligibility.yml
source_heading: Eligibility
source_page: https://bind.ai/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bind AI\naid: bind-ai\nurl: https://bind.ai/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are operated by us in the United States.\nentity_types:\n- type: business\n  text: you must be an authorized representative of a company or entity invited and onboarded to the Services through\n    an insurance broker with a Platform subscription\nrestricted_uses:\n- summary: Export restrictions\n  text: you will not export or re-export, directly or indirectly, the Services and/or other information or materials\n    provided by Bind AI hereunder, to any country\
  \ for which the United States or any other relevant jurisdiction\n    requires any export license\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you need to create an account on the Platform through the link or invitation provided by Your Broker\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bind-ai/eligibility/bind-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Bind AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Artificial Intelligence
- Brokerage
- Automation
- Software-as-a-Service
---
