---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you personally, or, if you’re entering into this Agreement on behalf of an organization or entity (who you are fully authorized to bind to this Agreement), that organization or entity.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Monitoring systems you do not control
    text: Use the Materials to monitor or secure systems You don’t control.
  - summary: Malicious or illegal use
    text: engage in any fraudulent, deceptive, illegal, or otherwise harmful activity.
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
name: Bluerock Security
provenance_date: '2026-11-09'
provider_name: Bluerock Security
provider_slug: bluerock-security
slug: bluerock-security-eligibility
source_date: '2026-11-09'
source_filename: bluerock-security-eligibility.yml
source_heading: Eligibility
source_page: https://www.bluerock.io/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bluerock Security\naid: bluerock-security\nurl: https://www.bluerock.io/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you personally, or, if you’re entering into this Agreement on behalf of an organization or entity (who you\n    are fully authorized to bind to this Agreement), that organization or entity.\nrestricted_uses:\n- summary: Monitoring systems you do not control\n  text: Use the Materials to monitor or secure systems You don’t control.\n- summary: Malicious or illegal use\n  text: engage in any fraudulent,\
  \ deceptive, illegal, or otherwise harmful activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bluerock-security/eligibility/bluerock-security-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Bluerock Security's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- AI Agents
- Agent Security
- MCP
- Observability
- Runtime Security
- AI Governance
- Guardrails
---
