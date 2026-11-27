---
api_specs:
- filename: asking-com-br-openapi-generated.yml
  format: yaml
  label: Asking API
  slug: asking-com-br-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asking-com-br/openapi/_ae-authored/asking-com-br-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you have authority to accept them for yourself or the organization you represent.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Asking
provenance_date: '2026-11-09'
provider_name: Asking
provider_slug: asking-com-br
slug: asking-com-br-eligibility
source_date: '2026-11-09'
source_filename: asking-com-br-eligibility.yml
source_heading: Eligibility
source_page: https://asking.com.br/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Asking\naid: asking-com-br\nurl: https://asking.com.br/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You represent that you have authority to accept them for yourself or the organization you represent.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/asking-com-br/eligibility/asking-com-br-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Asking's own page on 2026-11-09.
synthetic: false
tags:
- Customer Service
- Unified Inbox
- Team Collaboration
- AI Assistant
- Reporting
- Integration
---
