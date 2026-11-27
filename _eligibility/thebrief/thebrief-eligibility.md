---
api_specs:
- filename: graphql-api
  format: yaml
  label: The Brief Public GraphQL API
  slug: the-brief-public-graphql-api
  spec_type: Postman
  url: https://www.postman.com/thebrieftechnical/the-brief-api/collection/1lfct1g/graphql-api
- filename: creatopy-com-openapi-generated.yml
  format: yaml
  label: TheBrief API
  slug: creatopy-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thebrief/openapi/_ae-authored/creatopy-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, organized under the laws of, or ordinarily resident in a country subject to a U.S. Government embargo or designated as a "terrorist supporting" country
  entity_types:
  - text: These Terms apply to individual visitors and to Customers using the Services under the Free or Pro subscription plans
    type: individual
  - text: you, whether as an individual or as an authorized representative of an entity
    type: business
  minimum_age:
    text: You may only use our Services if you are of legal age to enter into these Terms according to the applicable laws and regulations in your jurisdiction.
    value: null
  restricted_uses:
  - summary: Export control restrictions
    text: will not export, re-export, or transfer the Services or related technology to any prohibited country, entity, or person.
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
name: TheBrief
provenance_date: '2026-11-10'
provider_name: TheBrief
provider_slug: thebrief
slug: thebrief-eligibility
source_date: '2026-11-10'
source_filename: thebrief-eligibility.yml
source_heading: Eligibility
source_page: https://www.thebrief.ai/legal-information/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TheBrief\naid: thebrief\nurl: https://www.thebrief.ai/legal-information/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, organized under the laws of, or ordinarily resident in a country\n    subject to a U.S. Government embargo or designated as a \"terrorist supporting\" country\nentity_types:\n- type: individual\n  text: These Terms apply to individual visitors and to Customers using the Services under the Free or Pro subscription\n    plans\n- type: business\n  text: you, whether as an individual or as an authorized representative\
  \ of an entity\nrestricted_uses:\n- summary: Export control restrictions\n  text: will not export, re-export, or transfer the Services or related technology to any prohibited country, entity,\n    or person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You may only use our Services if you are of legal age to enter into these Terms according to the applicable\n    laws and regulations in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/thebrief/eligibility/thebrief-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from TheBrief's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Advertising
- Creative
- Design
- Artificial Intelligence
- Marketing
- Ad Serving
- Software-as-a-Service
- GraphQL
- Creative Automation
- Digital Asset Management
- Webhook
- Platform
---
