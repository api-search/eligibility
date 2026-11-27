---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Apollo makes no representation that the Site or Content referenced herein are appropriate or available worldwide.
  minimum_age:
    text: BY ACCESSING OR USING THE SITE, YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD
    value: '18'
  restricted_uses:
  - summary: Sanctioned parties and export restrictions
    text: not directly or indirectly export, re-export, or deliver any Apollo products (including software), content, or services to a Sanctions Target
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
name: Apollo GraphQL
provenance_date: '2026-11-09'
provider_name: Apollo GraphQL
provider_slug: apollo-graphql
slug: apollo-graphql-eligibility
source_date: '2026-11-09'
source_filename: apollo-graphql-eligibility.yml
source_heading: Eligibility
source_page: https://www.apollographql.com/Apollo-Website-Terms-of-Service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apollo GraphQL\naid: apollo-graphql\nurl: https://www.apollographql.com/Apollo-Website-Terms-of-Service.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Apollo makes no representation that the Site or Content referenced herein are appropriate or available worldwide.\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned parties and export restrictions\n  text: not directly or indirectly export, re-export, or deliver any Apollo products (including software), content,\n    or services to a Sanctions Target\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: BY ACCESSING OR USING THE SITE, YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/apollo-graphql/eligibility/apollo-graphql-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Apollo GraphQL's own page on 2026-11-09.
synthetic: false
tags:
- API Orchestration
- Clients
- Connectors
- Federation
- Graph
- GraphQL
- Router
- Schema Registry
- Supergraph
---
