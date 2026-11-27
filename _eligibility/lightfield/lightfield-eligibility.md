---
api_specs:
- filename: lightfield-accounts-api-openapi.yml
  format: yaml
  label: Lightfield Accounts API
  slug: lightfield-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightfield/openapi/lightfield-accounts-api-openapi.yml
- filename: lightfield-auth-api-openapi.yml
  format: yaml
  label: Lightfield Auth API
  slug: lightfield-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightfield/openapi/lightfield-auth-api-openapi.yml
- filename: lightfield-contacts-api-openapi.yml
  format: yaml
  label: Lightfield Contacts API
  slug: lightfield-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightfield/openapi/lightfield-contacts-api-openapi.yml
- filename: lightfield-emails-api-openapi.yml
  format: yaml
  label: Lightfield Emails API
  slug: lightfield-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightfield/openapi/lightfield-emails-api-openapi.yml
- filename: lightfield-files-api-openapi.yml
  format: yaml
  label: Lightfield Files API
  slug: lightfield-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightfield/openapi/lightfield-files-api-openapi.yml
- filename: lightfield-lists-api-openapi.yml
  format: yaml
  label: Lightfield Lists API
  slug: lightfield-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightfield/openapi/lightfield-lists-api-openapi.yml
- filename: lightfield-meetings-api-openapi.yml
  format: yaml
  label: Lightfield Meetings API
  slug: lightfield-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightfield/openapi/lightfield-meetings-api-openapi.yml
- filename: lightfield-members-api-openapi.yml
  format: yaml
  label: Lightfield Members API
  slug: lightfield-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightfield/openapi/lightfield-members-api-openapi.yml
- filename: lightfield-notes-api-openapi.yml
  format: yaml
  label: Lightfield Notes API
  slug: lightfield-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightfield/openapi/lightfield-notes-api-openapi.yml
- filename: lightfield-objects-api-openapi.yml
  format: yaml
  label: Lightfield Objects API
  slug: lightfield-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightfield/openapi/lightfield-objects-api-openapi.yml
- filename: lightfield-opportunities-api-openapi.yml
  format: yaml
  label: Lightfield Opportunities API
  slug: lightfield-opportunities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightfield/openapi/lightfield-opportunities-api-openapi.yml
- filename: lightfield-tasks-api-openapi.yml
  format: yaml
  label: Lightfield Tasks API
  slug: lightfield-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightfield/openapi/lightfield-tasks-api-openapi.yml
- filename: lightfield-workflow-run-api-openapi.yml
  format: yaml
  label: Lightfield Workflow Run API
  slug: lightfield-workflow-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightfield/openapi/lightfield-workflow-run-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a terrorist-supporting country
  entity_types:
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  - text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with Lightfield
    type: individual
  minimum_age:
    text: You may use the Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Fully automated decisions
    text: is for fully automated decision making that adversely impacts an individual's legal rights or otherwise creates or modifies a binding, enforceable obligation
  - summary: Medical, financial or legal advice via Third-Party Services
    text: uses our Third Party Services to provide medical advice, medical results interpretation, financial advice or legal advice or opinion
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
name: Lightfield
provenance_date: '2026-11-09'
provider_name: Lightfield
provider_slug: lightfield
slug: lightfield-eligibility
source_date: '2026-11-09'
source_filename: lightfield-eligibility.yml
source_heading: Eligibility
source_page: https://lightfield.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lightfield\naid: lightfield\nurl: https://lightfield.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government\n    embargo, or that has been designated by the U.S. Government as a terrorist-supporting country\nentity_types:\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that entity to these Terms.\n- type: individual\n\
  \  text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with\n    Lightfield\nrestricted_uses:\n- summary: Fully automated decisions\n  text: is for fully automated decision making that adversely impacts an individual's legal rights or otherwise\n    creates or modifies a binding, enforceable obligation\n- summary: Medical, financial or legal advice via Third-Party Services\n  text: uses our Third Party Services to provide medical advice, medical results interpretation, financial advice\n    or legal advice or opinion\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/lightfield/eligibility/lightfield-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Lightfield's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Application
- CRM
- Sales
- Artificial Intelligence
- Agents
- Go-To-Market
- Productivity
- Software-as-a-Service
---
