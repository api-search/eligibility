---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    - US
    text: The marketplace is currently offered only where the payment jurisdiction is Canada or the United States ; it is not directed to the EEA, the United Kingdom, or Switzerland.
  entity_types:
  - text: You must be at least the age of majority where you live (and at least 18) and able to form a binding contract.
    type: individual
  - text: for having the authority to engage us on behalf of your business
    type: business
  minimum_age:
    text: You must be at least the age of majority where you live (and at least 18)
    value: '18'
  restricted_uses:
  - summary: Not professional advice
    text: Agents produce AI-generated output and are not a substitute for licensed medical, legal, financial, or other regulated professional advice.
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
name: Buy My Agent
provenance_date: '2026-11-09'
provider_name: Buy My Agent
provider_slug: buy-my-agent-com
slug: buy-my-agent-com-eligibility
source_date: '2026-11-09'
source_filename: buy-my-agent-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.buy-my-agent.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buy My Agent\naid: buy-my-agent-com\nurl: https://www.buy-my-agent.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  - US\n  excluded: []\n  text: The marketplace is currently offered only where the payment jurisdiction is Canada or the United States\n    ; it is not directed to the EEA, the United Kingdom, or Switzerland.\nentity_types:\n- type: individual\n  text: You must be at least the age of majority where you live (and at least 18) and able to form a binding contract.\n- type: business\n  text: for having the authority to engage us on behalf of your business\nrestricted_uses:\n- summary:\
  \ Not professional advice\n  text: Agents produce AI-generated output and are not a substitute for licensed medical, legal, financial, or other\n    regulated professional advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least the age of majority where you live (and at least 18)\n"
source_yaml_url: https://artifacts.apis.io/buy-my-agent-com/eligibility/buy-my-agent-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Buy My Agent's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketplace
- Automation
- Agents
- Business
---
