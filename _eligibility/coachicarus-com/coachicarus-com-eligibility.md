---
api_specs:
- filename: coachicarus-com-agent-api-openapi.yml
  format: yaml
  label: Coach Icarus Agent API
  slug: coachicarus-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coachicarus-com/openapi/coachicarus-com-agent-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use the Service. If you are under 18, you may only use the Service with the consent and supervision of a parent or legal guardian who agrees to these Terms on your behalf.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Non-commercial personal use
    text: for your personal, non-commercial use
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
name: Coach Icarus
provenance_date: '2026-11-09'
provider_name: Coach Icarus
provider_slug: coachicarus-com
slug: coachicarus-com-eligibility
source_date: '2026-11-09'
source_filename: coachicarus-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.coachicarus.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coach Icarus\naid: coachicarus-com\nurl: https://www.coachicarus.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Service. If you are under 18, you may only use the Service\n    with the consent and supervision of a parent or legal guardian who agrees to these Terms on your behalf.\nrestricted_uses:\n- summary: Non-commercial personal use\n  text: for your personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/coachicarus-com/eligibility/coachicarus-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Coach Icarus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Running
- Fitness
- Coaching
- Garmin
- Health
- Wearables
- MCP
- AI Agents
---
