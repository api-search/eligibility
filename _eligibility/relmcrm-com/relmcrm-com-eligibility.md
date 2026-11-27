---
api_specs:
- filename: relmcrm-com-activities-api-openapi.yml
  format: yaml
  label: Relm Activities API
  slug: relmcrm-com-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-activities-api-openapi.yml
- filename: relmcrm-com-automations-api-openapi.yml
  format: yaml
  label: Relm Automations API
  slug: relmcrm-com-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-automations-api-openapi.yml
- filename: relmcrm-com-batch-api-openapi.yml
  format: yaml
  label: Relm Batch API
  slug: relmcrm-com-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-batch-api-openapi.yml
- filename: relmcrm-com-companies-api-openapi.yml
  format: yaml
  label: Relm Companies API
  slug: relmcrm-com-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-companies-api-openapi.yml
- filename: relmcrm-com-connections-api-openapi.yml
  format: yaml
  label: Relm Connections API
  slug: relmcrm-com-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-connections-api-openapi.yml
- filename: relmcrm-com-contacts-api-openapi.yml
  format: yaml
  label: Relm Contacts API
  slug: relmcrm-com-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-contacts-api-openapi.yml
- filename: relmcrm-com-deals-api-openapi.yml
  format: yaml
  label: Relm Deals API
  slug: relmcrm-com-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-deals-api-openapi.yml
- filename: relmcrm-com-discovery-api-openapi.yml
  format: yaml
  label: Relm Discovery API
  slug: relmcrm-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-discovery-api-openapi.yml
- filename: relmcrm-com-pipelines-api-openapi.yml
  format: yaml
  label: Relm Pipelines API
  slug: relmcrm-com-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-pipelines-api-openapi.yml
- filename: relmcrm-com-registry-api-openapi.yml
  format: yaml
  label: Relm Registry API
  slug: relmcrm-com-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-registry-api-openapi.yml
- filename: relmcrm-com-search-api-openapi.yml
  format: yaml
  label: Relm Search API
  slug: relmcrm-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-search-api-openapi.yml
- filename: relmcrm-com-sequences-api-openapi.yml
  format: yaml
  label: Relm Sequences API
  slug: relmcrm-com-sequences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-sequences-api-openapi.yml
- filename: relmcrm-com-templates-api-openapi.yml
  format: yaml
  label: Relm Templates API
  slug: relmcrm-com-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-templates-api-openapi.yml
- filename: relmcrm-com-webhooks-api-openapi.yml
  format: yaml
  label: Relm Webhooks API
  slug: relmcrm-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing on behalf of a company, you confirm you may bind that company.
    type: business
  minimum_age:
    text: You must be at least 16.
    value: '16'
  restricted_uses:
  - summary: Unlawful use or data without right
    text: 'Do not use Relm to: break any law, or store data you have no right to hold'
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
name: Relm
provenance_date: '2026-11-10'
provider_name: Relm
provider_slug: relmcrm-com
slug: relmcrm-com-eligibility
source_date: '2026-11-10'
source_filename: relmcrm-com-eligibility.yml
source_heading: Eligibility
source_page: https://relmcrm.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Relm\naid: relmcrm-com\nurl: https://relmcrm.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are agreeing on behalf of a company, you confirm you may bind that company.\nrestricted_uses:\n- summary: Unlawful use or data without right\n  text: 'Do not use Relm to: break any law, or store data you have no right to hold'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16.\n"
source_yaml_url: https://artifacts.apis.io/relmcrm-com/eligibility/relmcrm-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Relm's own page on 2026-11-10.
synthetic: false
tags:
- CRM
- Sales
- Contacts
- Deals
- Sales Pipeline
- Automation
- Webhook
- MCP
- A2A
- AI Agents
- Agent-Native
- United Arab Emirates
---
