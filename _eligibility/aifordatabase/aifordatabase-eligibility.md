---
api_specs:
- filename: aifordatabase-chat-api-openapi.yml
  format: yaml
  label: AI for Database Chat API
  slug: aifordatabase-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-chat-api-openapi.yml
- filename: aifordatabase-connections-api-openapi.yml
  format: yaml
  label: AI for Database Connections API
  slug: aifordatabase-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-connections-api-openapi.yml
- filename: aifordatabase-conversations-api-openapi.yml
  format: yaml
  label: AI for Database Conversations API
  slug: aifordatabase-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-conversations-api-openapi.yml
- filename: aifordatabase-dashboards-api-openapi.yml
  format: yaml
  label: AI for Database Dashboards API
  slug: aifordatabase-dashboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-dashboards-api-openapi.yml
- filename: aifordatabase-keys-api-openapi.yml
  format: yaml
  label: AI for Database Keys API
  slug: aifordatabase-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-keys-api-openapi.yml
- filename: aifordatabase-metrics-api-openapi.yml
  format: yaml
  label: AI for Database Metrics API
  slug: aifordatabase-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-metrics-api-openapi.yml
- filename: aifordatabase-query-approval-api-openapi.yml
  format: yaml
  label: AI for Database Query Approval API
  slug: aifordatabase-query-approval-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-query-approval-api-openapi.yml
- filename: aifordatabase-saved-queries-api-openapi.yml
  format: yaml
  label: AI for Database Saved Queries API
  slug: aifordatabase-saved-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-saved-queries-api-openapi.yml
- filename: aifordatabase-usage-api-openapi.yml
  format: yaml
  label: AI for Database Usage API
  slug: aifordatabase-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-usage-api-openapi.yml
- filename: aifordatabase-webhooks-api-openapi.yml
  format: yaml
  label: AI for Database Webhooks API
  slug: aifordatabase-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-webhooks-api-openapi.yml
- filename: aifordatabase-workflow-credentials-api-openapi.yml
  format: yaml
  label: AI for Database Workflow Credentials API
  slug: aifordatabase-workflow-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-workflow-credentials-api-openapi.yml
- filename: aifordatabase-workflows-api-openapi.yml
  format: yaml
  label: AI for Database Workflows API
  slug: aifordatabase-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-workflows-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and have the legal authority to enter into these Terms.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent that you have the authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and have the legal authority to enter into these Terms.
    value: '18'
  restricted_uses:
  - summary: Unlawful purpose
    text: Use the Service for any unlawful purpose or to violate any applicable law or regulation.
  - summary: Unauthorized data processing
    text: You should not connect databases containing data you are not authorized to process through third-party AI services.
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
name: AI for Database
provenance_date: '2026-11-09'
provider_name: AI for Database
provider_slug: aifordatabase
slug: aifordatabase-eligibility
source_date: '2026-11-09'
source_filename: aifordatabase-eligibility.yml
source_heading: Eligibility
source_page: https://www.aifordatabase.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AI for Database\naid: aifordatabase\nurl: https://www.aifordatabase.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have the legal authority to enter into these Terms.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have the authority to\n    bind that organization.\nrestricted_uses:\n- summary: Unlawful purpose\n  text: Use the Service for any unlawful purpose or to violate any applicable law or regulation.\n- summary: Unauthorized\
  \ data processing\n  text: You should not connect databases containing data you are not authorized to process through third-party AI\n    services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and have the legal authority to enter into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/aifordatabase/eligibility/aifordatabase-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from AI for Database's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Database
- Analytics
- Developer Tools
- Natural Language Query
- Text-to-SQL
- Dashboards
- Business Intelligence
- Workflow Automation
- Alerts
- Agent-Native
- Llms.txt
- OpenAPI
- Webhook
- MCP
- PostgreSQL
- MySQL
- MongoDB
---
