---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Individuals may access the Service, but it is not marketed as a consumer product.
    type: individual
  - text: The Service is intended primarily for professional and business use.
    type: business
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Safety-critical environments
    text: The Service is not intended for safety-critical environments.
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
name: Logicstar
provenance_date: '2026-11-09'
provider_name: Logicstar
provider_slug: logicstar
slug: logicstar-eligibility
source_date: '2026-11-09'
source_filename: logicstar-eligibility.yml
source_heading: Eligibility
source_page: https://logicstar.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Logicstar\naid: logicstar\nurl: https://logicstar.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Individuals may access the Service, but it is not marketed as a consumer product.\n- type: business\n  text: The Service is intended primarily for professional and business use.\nrestricted_uses:\n- summary: Safety-critical environments\n  text: The Service is not intended for safety-critical environments.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/logicstar/eligibility/logicstar-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Logicstar's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Artificial Intelligence
- AI Agents
- Software Maintenance
- Bug Fixing
- Developer Tools
- Code Quality
---
