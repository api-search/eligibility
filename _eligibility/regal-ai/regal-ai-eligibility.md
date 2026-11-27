---
api_specs:
- filename: regal-reporting-webhooks-asyncapi.yml
  format: yaml
  label: Regal Reporting Webhooks
  slug: regal-reporting-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/regal-ai/asyncapi/regal-reporting-webhooks-asyncapi.yml
- filename: regal-ai-campaigns-api-openapi.yml
  format: yaml
  label: Regal Campaigns API
  slug: regal-ai-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-campaigns-api-openapi.yml
- filename: regal-ai-dispositions-api-openapi.yml
  format: yaml
  label: Regal Dispositions API
  slug: regal-ai-dispositions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-dispositions-api-openapi.yml
- filename: regal-ai-events-api-openapi.yml
  format: yaml
  label: Regal Events API
  slug: regal-ai-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-events-api-openapi.yml
- filename: regal-ai-messages-api-openapi.yml
  format: yaml
  label: Regal Messages API
  slug: regal-ai-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-messages-api-openapi.yml
- filename: regal-ai-users-api-openapi.yml
  format: yaml
  label: Regal Users API
  slug: regal-ai-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-users-api-openapi.yml
- filename: regal-ai-activephonenumbers-api-openapi.yml
  format: yaml
  label: Regal Active Phone Numbers API
  slug: regal-ai-activephonenumbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-activephonenumbers-api-openapi.yml
- filename: regal-ai-brandedphonenumbers-api-openapi.yml
  format: yaml
  label: Regal Branded Phone Numbers API
  slug: regal-ai-brandedphonenumbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-brandedphonenumbers-api-openapi.yml
- filename: regal-ai-businessprofiles-api-openapi.yml
  format: yaml
  label: Regal Business Profiles API
  slug: regal-ai-businessprofiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-businessprofiles-api-openapi.yml
- filename: regal-ai-callhandoffs-api-openapi.yml
  format: yaml
  label: Regal Call Handoffs API
  slug: regal-ai-callhandoffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-callhandoffs-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the individual, company and/or organization subscribing to the Platform and Services
    type: business
  - text: individuals, companies and/or organizations using the Website (each, a “User”)
    type: individual
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE REGAL OFFERINGS OR ENTER INTO THIS AGREEMENT IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: No credit, employment or insurance eligibility use
    text: use the Service to establish an individual’s eligibility for credit, employment or insurance.
  - summary: No adult or illegal drug content
    text: send via or store within the Service any adult content, content promoting illegal drugs
  - summary: No unsolicited messages
    text: create accounts for the purposes of, or send, unsolicited messages (spam)
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
name: Regal
provenance_date: '2026-11-10'
provider_name: Regal
provider_slug: regal-ai
slug: regal-ai-eligibility
source_date: '2026-11-10'
source_filename: regal-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.regal.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Regal\naid: regal-ai\nurl: https://www.regal.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the individual, company and/or organization subscribing to the Platform and Services\n- type: individual\n  text: individuals, companies and/or organizations using the Website (each, a “User”)\nrestricted_uses:\n- summary: No credit, employment or insurance eligibility use\n  text: use the Service to establish an individual’s eligibility for credit, employment or insurance.\n- summary: No adult or illegal drug content\n  text:\
  \ send via or store within the Service any adult content, content promoting illegal drugs\n- summary: No unsolicited messages\n  text: create accounts for the purposes of, or send, unsolicited messages (spam)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE REGAL OFFERINGS OR ENTER INTO THIS AGREEMENT IF YOU ARE NOT AT LEAST 18 YEARS\n    OLD.\n"
source_yaml_url: https://artifacts.apis.io/regal-ai/eligibility/regal-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Regal's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- AI Agents
- Voice AI
- Contact Center
- Outbound Calling
- Inbound Calling
- Phone Agents
- SMS
- Chat
- WebRTC
- Conversation Intelligence
- Journey Orchestration
- Branded Caller ID
- CCaaS
- CPaaS
- Sales Dialer
- Customer Engagement
---
