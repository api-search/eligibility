---
api_specs:
- filename: weav-com-openapi-generated.yml
  format: yaml
  label: weav-com API
  slug: weav-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weav-com/openapi/_ae-authored/weav-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing on behalf of a company or other legal entity, you represent that you have authority to bind that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Illegal or infringing content
    text: You will not use the Service to transmit or store content that is illegal, harmful, abusive, infringing, or that violates laws or third-party rights.
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
name: weav-com
provenance_date: '2026-11-10'
provider_name: weav-com
provider_slug: weav-com
slug: weav-com-eligibility
source_date: '2026-11-10'
source_filename: weav-com-eligibility.yml
source_heading: Eligibility
source_page: https://weav.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: weav-com\naid: weav-com\nurl: https://weav.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are agreeing on behalf of a company or other legal entity, you represent that you have authority\n    to bind that entity.\nrestricted_uses:\n- summary: Illegal or infringing content\n  text: You will not use the Service to transmit or store content that is illegal, harmful, abusive, infringing,\n    or that violates laws or third-party rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/weav-com/eligibility/weav-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from weav-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Customer Service
- Automation
- Software-as-a-Service
- Chatbots
---
