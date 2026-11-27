---
api_specs:
- filename: boom-ai-cdp-custom-objects-api-openapi.yml
  format: yaml
  label: Boom Ai CDP Custom Objects API
  slug: boom-ai-cdp-custom-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boom-ai/openapi/boom-ai-cdp-custom-objects-api-openapi.yml
- filename: boom-ai-cdp-events-api-openapi.yml
  format: yaml
  label: Boom Ai CDP Events API
  slug: boom-ai-cdp-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boom-ai/openapi/boom-ai-cdp-events-api-openapi.yml
- filename: boom-ai-cdp-people-api-openapi.yml
  format: yaml
  label: Boom Ai CDP People API
  slug: boom-ai-cdp-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boom-ai/openapi/boom-ai-cdp-people-api-openapi.yml
- filename: boom-ai-cdp-relationships-api-openapi.yml
  format: yaml
  label: Boom Ai CDP Relationships API
  slug: boom-ai-cdp-relationships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boom-ai/openapi/boom-ai-cdp-relationships-api-openapi.yml
- filename: boom-ai-cdp-sources-api-openapi.yml
  format: yaml
  label: Boom Ai CDP Sources API
  slug: boom-ai-cdp-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boom-ai/openapi/boom-ai-cdp-sources-api-openapi.yml
- filename: boom-ai-http-credentials-api-openapi.yml
  format: yaml
  label: Boom Ai HTTP credentials API
  slug: boom-ai-http-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boom-ai/openapi/boom-ai-http-credentials-api-openapi.yml
- filename: boom-ai-initiatives-api-openapi.yml
  format: yaml
  label: Boom Ai Initiatives API
  slug: boom-ai-initiatives-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boom-ai/openapi/boom-ai-initiatives-api-openapi.yml
- filename: boom-ai-journeys-api-openapi.yml
  format: yaml
  label: Boom Ai Journeys API
  slug: boom-ai-journeys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boom-ai/openapi/boom-ai-journeys-api-openapi.yml
- filename: boom-ai-segments-api-openapi.yml
  format: yaml
  label: Boom Ai Segments API
  slug: boom-ai-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boom-ai/openapi/boom-ai-segments-api-openapi.yml
- filename: boom-ai-whatsapp-templates-api-openapi.yml
  format: yaml
  label: Boom Ai WhatsApp templates API
  slug: boom-ai-whatsapp-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boom-ai/openapi/boom-ai-whatsapp-templates-api-openapi.yml
- filename: boom-ai-environments-api-openapi.yml
  format: yaml
  label: Boom Ai Environments API
  slug: boom-ai-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boom-ai/openapi/boom-ai-environments-api-openapi.yml
- filename: boom-ai-cdp-sensitive-fields-api-openapi.yml
  format: yaml
  label: Boom Ai CDP Sensitive fields API
  slug: boom-ai-cdp-sensitive-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boom-ai/openapi/boom-ai-cdp-sensitive-fields-api-openapi.yml
- filename: boom-ai-email-templates-api-openapi.yml
  format: yaml
  label: Boom Ai Email templates API
  slug: boom-ai-email-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boom-ai/openapi/boom-ai-email-templates-api-openapi.yml
- filename: boom-ai-lead-capture-api-openapi.yml
  format: yaml
  label: Boom Ai Lead Capture API
  slug: boom-ai-lead-capture-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boom-ai/openapi/boom-ai-lead-capture-api-openapi.yml
- filename: boom-ai-message-logs-api-openapi.yml
  format: yaml
  label: Boom Ai Message logs API
  slug: boom-ai-message-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boom-ai/openapi/boom-ai-message-logs-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing or using the Product on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Customer responsibility for end-user content
    text: The Customer is solely responsible for the content, legality, and compliance of messages or outputs delivered to its end-users via the Provider
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
name: Boom Ai
provenance_date: '2026-11-09'
provider_name: Boom Ai
provider_slug: boom-ai
slug: boom-ai-eligibility
source_date: '2026-11-09'
source_filename: boom-ai-eligibility.yml
source_heading: Eligibility
source_page: https://drive.google.com/file/d/1SlTp1_QWhVASpbxncSj1NpmFqiiGBcF1/view
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boom Ai\naid: boom-ai\nurl: https://drive.google.com/file/d/1SlTp1_QWhVASpbxncSj1NpmFqiiGBcF1/view\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing or using the Product on behalf of your company, you represent that you are authorized\n    to accept this Agreement on behalf of your company.\nrestricted_uses:\n- summary: Customer responsibility for end-user content\n  text: The Customer is solely responsible for the content, legality, and compliance of messages or outputs delivered\n    to its end-users via the Provider\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/boom-ai/eligibility/boom-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Boom Ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Conversational AI
- Customer Engagement
- Customer Data Platform
- Messaging
- WhatsApp
- SMS
- Marketing Automation
- E-Commerce
- Agents
- MCP
- A2A
---
