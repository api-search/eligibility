---
api_specs:
- filename: cuein-answers-api-openapi.yml
  format: yaml
  label: Cuein Answers API
  slug: cuein-answers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cuein/openapi/cuein-answers-api-openapi.yml
- filename: cuein-conversations-api-openapi.yml
  format: yaml
  label: Cuein Conversations API
  slug: cuein-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cuein/openapi/cuein-conversations-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ACCEPTING THESE TERMS OF USE ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THIS AGREEMENT
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Soliciting info from minors
    text: e. solicit personal information from anyone under the age of 18
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
name: Cuein
provenance_date: '2026-11-09'
provider_name: Cuein
provider_slug: cuein
slug: cuein-eligibility
source_date: '2026-11-09'
source_filename: cuein-eligibility.yml
source_heading: Eligibility
source_page: https://cuein.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cuein\naid: cuein\nurl: https://cuein.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ACCEPTING THESE TERMS OF USE ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THIS AGREEMENT\nrestricted_uses:\n- summary: Soliciting info from minors\n  text: e. solicit personal information from anyone under the age of 18\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cuein/eligibility/cuein-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Cuein's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Experience
- Customer Service
- Conversation Intelligence
- Generative AI
- Insights
- Knowledge Base
- Contact Center
---
