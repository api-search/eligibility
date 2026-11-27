---
api_specs:
- filename: osis-co-ai-api-openapi.yml
  format: yaml
  label: osis-co AI API
  slug: osis-co-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-ai-api-openapi.yml
- filename: osis-co-calls-api-openapi.yml
  format: yaml
  label: osis-co Calls API
  slug: osis-co-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-calls-api-openapi.yml
- filename: osis-co-capabilities-api-openapi.yml
  format: yaml
  label: osis-co Capabilities API
  slug: osis-co-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-capabilities-api-openapi.yml
- filename: osis-co-conversations-api-openapi.yml
  format: yaml
  label: osis-co Conversations API
  slug: osis-co-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-conversations-api-openapi.yml
- filename: osis-co-events-api-openapi.yml
  format: yaml
  label: osis-co Events API
  slug: osis-co-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-events-api-openapi.yml
- filename: osis-co-groups-api-openapi.yml
  format: yaml
  label: osis-co Groups API
  slug: osis-co-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-groups-api-openapi.yml
- filename: osis-co-lines-api-openapi.yml
  format: yaml
  label: osis-co Lines API
  slug: osis-co-lines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-lines-api-openapi.yml
- filename: osis-co-messages-api-openapi.yml
  format: yaml
  label: osis-co Messages API
  slug: osis-co-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-messages-api-openapi.yml
- filename: osis-co-number-changes-api-openapi.yml
  format: yaml
  label: osis-co Number Changes API
  slug: osis-co-number-changes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-number-changes-api-openapi.yml
- filename: osis-co-payments-api-openapi.yml
  format: yaml
  label: osis-co Payments API
  slug: osis-co-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-payments-api-openapi.yml
- filename: osis-co-webhooks-api-openapi.yml
  format: yaml
  label: osis-co Webhooks API
  slug: osis-co-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of a company or other legal entity, “Customer” refers to that entity and you represent that you have authority to bind it.
    type: business
  - text: You must be at least 18 years old and able to form a binding contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Prohibited content
    text: You will not use the Service to create, send, or facilitate content that is illegal, fraudulent, deceptive, harmful, harassing, abusive, hateful, defamatory, or infringing
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with a phone number verified by one-time code.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: osis-co
provenance_date: '2026-11-10'
provider_name: osis-co
provider_slug: osis-co
slug: osis-co-eligibility
source_date: '2026-11-10'
source_filename: osis-co-eligibility.yml
source_heading: Eligibility
source_page: https://comms.osis.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: osis-co\naid: osis-co\nurl: https://comms.osis.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of a company or other legal entity, “Customer” refers to that entity and\n    you represent that you have authority to bind it.\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract.\nrestricted_uses:\n- summary: Prohibited content\n  text: You will not use the Service to create, send, or facilitate content that is illegal, fraudulent, deceptive,\n    harmful,\
  \ harassing, abusive, hateful, defamatory, or infringing\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with a phone number verified by one-time code.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/osis-co/eligibility/osis-co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from osis-co's own page on 2026-11-10.
synthetic: false
tags:
- Messaging
- Communications
- Software-as-a-Service
- Customer Service
---
