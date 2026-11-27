---
api_specs:
- filename: fini-agents-api-openapi.yml
  format: yaml
  label: Fini Agents API
  slug: fini-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-agents-api-openapi.yml
- filename: fini-articles-api-openapi.yml
  format: yaml
  label: Fini Articles API
  slug: fini-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-articles-api-openapi.yml
- filename: fini-conversations-api-openapi.yml
  format: yaml
  label: Fini Conversations API
  slug: fini-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-conversations-api-openapi.yml
- filename: fini-knowledge-api-openapi.yml
  format: yaml
  label: Fini Knowledge API
  slug: fini-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-knowledge-api-openapi.yml
- filename: fini-knowledge-folders-api-openapi.yml
  format: yaml
  label: Fini Knowledge Folders API
  slug: fini-knowledge-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-knowledge-folders-api-openapi.yml
- filename: fini-prompts-api-openapi.yml
  format: yaml
  label: Fini Prompts API
  slug: fini-prompts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-prompts-api-openapi.yml
- filename: fini-rules-api-openapi.yml
  format: yaml
  label: Fini Rules API
  slug: fini-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-rules-api-openapi.yml
- filename: fini-sources-api-openapi.yml
  format: yaml
  label: Fini Sources API
  slug: fini-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-sources-api-openapi.yml
- filename: fini-tags-api-openapi.yml
  format: yaml
  label: Fini Tags API
  slug: fini-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-tags-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'You may not use the Services if: You are located in a country subject to U.S., EU, or UN sanctions;'
  entity_types:
  - text: You are at least 18 years of age or the age of majority in your jurisdiction;
    type: individual
  - text: If you are entering into these Terms on behalf of a legal entity, you represent and warrant that you have the authority to bind the entity to these Terms.
    type: business
  minimum_age:
    text: You are at least 18 years of age or the age of majority in your jurisdiction;
    value: '18'
  restricted_uses:
  - summary: Sanctioned locations or persons
    text: You are on any government list of restricted or prohibited persons.
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
name: Fini
provenance_date: '2026-11-09'
provider_name: Fini
provider_slug: fini
slug: fini-eligibility
source_date: '2026-11-09'
source_filename: fini-eligibility.yml
source_heading: Eligibility
source_page: https://www.usefini.com/security/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fini\naid: fini\nurl: https://www.usefini.com/security/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'You may not use the Services if: You are located in a country subject to U.S., EU, or UN sanctions;'\nentity_types:\n- type: individual\n  text: You are at least 18 years of age or the age of majority in your jurisdiction;\n- type: business\n  text: If you are entering into these Terms on behalf of a legal entity, you represent and warrant that you have\n    the authority to bind the entity to these Terms.\nrestricted_uses:\n- summary: Sanctioned locations or persons\n\
  \  text: You are on any government list of restricted or prohibited persons.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age or the age of majority in your jurisdiction;\n"
source_yaml_url: https://artifacts.apis.io/fini/eligibility/fini-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Fini's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Customer Service
- Customer Experience
- Knowledge Management
- Conversational AI
- Voice AI
- Help Desk
- Regulated Industries
---
