---
api_specs:
- filename: dashbot-io-openapi-generated.yml
  format: yaml
  label: Dashbot API
  slug: dashbot-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dashbot-io/openapi/_ae-authored/dashbot-io-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You (either an individual or a legal entity that you represent as an authorized employee or agent)
    type: individual
  - text: a legal entity that you represent as an authorized employee or agent
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No collecting personal data of internet users
    text: You will not (and will not allow any third party to) use the Service to track or collect personally identifiable information of Internet users
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
name: Dashbot
provenance_date: '2026-11-09'
provider_name: Dashbot
provider_slug: dashbot-io
slug: dashbot-io-eligibility
source_date: '2026-11-09'
source_filename: dashbot-io-eligibility.yml
source_heading: Eligibility
source_page: https://blog.dashbot.io/legal/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dashbot\naid: dashbot-io\nurl: https://blog.dashbot.io/legal/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You (either an individual or a legal entity that you represent as an authorized employee or agent)\n- type: business\n  text: a legal entity that you represent as an authorized employee or agent\nrestricted_uses:\n- summary: No collecting personal data of internet users\n  text: You will not (and will not allow any third party to) use the Service to track or collect personally identifiable\n    information of Internet users\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dashbot-io/eligibility/dashbot-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Dashbot's own page on 2026-11-09.
synthetic: false
tags:
- AI Analytics
- Customer conversation analytics
- Voice of Customer
- Revenue Intelligence
- Contact Center Analytics
- Software-as-a-Service
---
