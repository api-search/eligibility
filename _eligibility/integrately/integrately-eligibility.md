---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you, the person or company who is being given a limited license to use the Integrately application
    type: individual
  - text: you, the person or company who is being given a limited license to use the Integrately application
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Hazardous or fail-safe environments
    text: the Service is not designed or licensed for use in hazardous environments requiring fail-safe controls, including without limitation operation of nuclear facilities, aircraft navigation/communication systems, air traffic control, and life support or weapons systems.
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
name: Integrately
provenance_date: '2026-11-09'
provider_name: Integrately
provider_slug: integrately
slug: integrately-eligibility
source_date: '2026-11-09'
source_filename: integrately-eligibility.yml
source_heading: Eligibility
source_page: https://integrately.com/home/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Integrately\naid: integrately\nurl: https://integrately.com/home/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you, the person or company who is being given a limited license to use the Integrately application\n- type: business\n  text: you, the person or company who is being given a limited license to use the Integrately application\nrestricted_uses:\n- summary: Hazardous or fail-safe environments\n  text: the Service is not designed or licensed for use in hazardous environments requiring fail-safe controls,\n    including\
  \ without limitation operation of nuclear facilities, aircraft navigation/communication systems, air\n    traffic control, and life support or weapons systems.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/integrately/eligibility/integrately-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Integrately's own page on 2026-11-09.
synthetic: false
tags:
- Automation
- Business Process Automation
- iPaaS
- No-Code
- SaaS Integration
- Small Business
- Triggers and Actions
- Webhook
- Workflow Automation
- Workflows
---
