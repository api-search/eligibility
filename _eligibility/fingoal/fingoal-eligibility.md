---
api_specs:
- filename: fingoal-enrichment-api-openapi.yml
  format: yaml
  label: FinGoal Enrichment API
  slug: fingoal-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fingoal/openapi/fingoal-enrichment-api-openapi.yml
- filename: fingoal-user-tagging-api-openapi.yml
  format: yaml
  label: FinGoal User Tagging API
  slug: fingoal-user-tagging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fingoal/openapi/fingoal-user-tagging-api-openapi.yml
- filename: fingoal-webhook-configurations-api-openapi.yml
  format: yaml
  label: FinGoal Webhook Configurations API
  slug: fingoal-webhook-configurations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fingoal/openapi/fingoal-webhook-configurations-api-openapi.yml
- filename: fingoal-client-management-api-openapi.yml
  format: yaml
  label: FinGoal Client Management API
  slug: fingoal-client-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fingoal/openapi/fingoal-client-management-api-openapi.yml
- filename: fingoal-fastlink-api-openapi.yml
  format: yaml
  label: FinGoal Fastlink API
  slug: fingoal-fastlink-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fingoal/openapi/fingoal-fastlink-api-openapi.yml
- filename: fingoal-webhooks-api-openapi.yml
  format: yaml
  label: FinGoal Webhooks API
  slug: fingoal-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fingoal/openapi/fingoal-webhooks-api-openapi.yml
- filename: fingoal-oauth-api-openapi.yml
  format: yaml
  label: FinGoal OAUTH API
  slug: fingoal-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fingoal/openapi/fingoal-oauth-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: or are not at least 18 years of age and, in any event, of a legal age to form a binding contract with FinGoal.
    type: individual
  minimum_age:
    text: are not at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You are only entitled to access and use the Sites and Services for lawful purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We may verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FinGoal
provenance_date: '2026-11-09'
provider_name: FinGoal
provider_slug: fingoal
slug: fingoal-eligibility
source_date: '2026-11-09'
source_filename: fingoal-eligibility.yml
source_heading: Eligibility
source_page: https://fingoal.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FinGoal\naid: fingoal\nurl: https://fingoal.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: or are not at least 18 years of age and, in any event, of a legal age to form a binding contract with FinGoal.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You are only entitled to access and use the Sites and Services for lawful purposes.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We may verify your identity.\nminimum_age:\n  value: '18'\n  text: are not at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/fingoal/eligibility/fingoal-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from FinGoal's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Fintech
- Transaction Enrichment
- Data Enrichment
- Personal Financial Management
- Banking
- Categorization
- Webhook
---
