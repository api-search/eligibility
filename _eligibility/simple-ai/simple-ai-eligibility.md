---
api_specs:
- filename: simple-ai-agents-api-openapi.yml
  format: yaml
  label: Simple AI Agents API
  slug: simple-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simple-ai/openapi/simple-ai-agents-api-openapi.yml
- filename: simple-ai-call-notes-api-openapi.yml
  format: yaml
  label: Simple AI Call Notes API
  slug: simple-ai-call-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simple-ai/openapi/simple-ai-call-notes-api-openapi.yml
- filename: simple-ai-call-tags-api-openapi.yml
  format: yaml
  label: Simple AI Call Tags API
  slug: simple-ai-call-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simple-ai/openapi/simple-ai-call-tags-api-openapi.yml
- filename: simple-ai-calls-api-openapi.yml
  format: yaml
  label: Simple AI Calls API
  slug: simple-ai-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simple-ai/openapi/simple-ai-calls-api-openapi.yml
- filename: simple-ai-contacts-api-openapi.yml
  format: yaml
  label: Simple AI Contacts API
  slug: simple-ai-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simple-ai/openapi/simple-ai-contacts-api-openapi.yml
- filename: simple-ai-custom-data-api-openapi.yml
  format: yaml
  label: Simple AI Custom Data API
  slug: simple-ai-custom-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simple-ai/openapi/simple-ai-custom-data-api-openapi.yml
- filename: simple-ai-external-calls-api-openapi.yml
  format: yaml
  label: Simple AI External Calls API
  slug: simple-ai-external-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simple-ai/openapi/simple-ai-external-calls-api-openapi.yml
- filename: simple-ai-feedback-api-openapi.yml
  format: yaml
  label: Simple AI Feedback API
  slug: simple-ai-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simple-ai/openapi/simple-ai-feedback-api-openapi.yml
- filename: simple-ai-interactions-api-openapi.yml
  format: yaml
  label: Simple AI Interactions API
  slug: simple-ai-interactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simple-ai/openapi/simple-ai-interactions-api-openapi.yml
- filename: simple-ai-journeys-api-openapi.yml
  format: yaml
  label: Simple AI Journeys API
  slug: simple-ai-journeys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simple-ai/openapi/simple-ai-journeys-api-openapi.yml
- filename: simple-ai-numbers-api-openapi.yml
  format: yaml
  label: Simple AI Numbers API
  slug: simple-ai-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simple-ai/openapi/simple-ai-numbers-api-openapi.yml
- filename: simple-ai-voices-api-openapi.yml
  format: yaml
  label: Simple AI Voices API
  slug: simple-ai-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simple-ai/openapi/simple-ai-voices-api-openapi.yml
- filename: simple-ai-webhooks-api-openapi.yml
  format: yaml
  label: Simple AI Webhooks API
  slug: simple-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simple-ai/openapi/simple-ai-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - US embargoed countries
    served: []
    text: you are not located in, or a resident or a national of, any country subject to a U.S. government embargo or other restriction
  entity_types:
  - text: You must be at least 18 years old to use or order the Services.
    type: individual
  - text: If you place an Order for any of our Services on behalf of an organization or company, you affirm you have the legal authority to bind such organization or company to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use or order the Services.
    value: '18'
  restricted_uses:
  - summary: Unsolicited calls without consent
    text: 'use the Services to communicate with any third party that has: (i) not given you express written consent to contact them using the Services'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US embargoed countries
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Simple AI
provenance_date: '2026-11-10'
provider_name: Simple AI
provider_slug: simple-ai
slug: simple-ai-eligibility
source_date: '2026-11-10'
source_filename: simple-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.usesimple.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Simple AI\naid: simple-ai\nurl: https://www.usesimple.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US embargoed countries\n  text: you are not located in, or a resident or a national of, any country subject to a U.S. government embargo\n    or other restriction\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use or order the Services.\n- type: business\n  text: If you place an Order for any of our Services on behalf of an organization or company, you affirm you have\n    the legal authority to bind such organization or company to these Terms\n\
  restricted_uses:\n- summary: Unsolicited calls without consent\n  text: 'use the Services to communicate with any third party that has: (i) not given you express written consent\n    to contact them using the Services'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use or order the Services.\n"
source_yaml_url: https://artifacts.apis.io/simple-ai/eligibility/simple-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Simple AI's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Voice
- Telephony
- Software-as-a-Service
- Automation
- Contact Center
---
