---
api_specs:
- filename: unifonic-call-management-and-status-api-openapi.yml
  format: yaml
  label: Unifonic Call Management and Status API
  slug: unifonic-call-management-and-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unifonic/openapi/unifonic-call-management-and-status-api-openapi.yml
- filename: unifonic-call-queue-management-api-openapi.yml
  format: yaml
  label: Unifonic Call Queue Management API
  slug: unifonic-call-queue-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unifonic/openapi/unifonic-call-queue-management-api-openapi.yml
- filename: unifonic-number-masking-api-openapi.yml
  format: yaml
  label: Unifonic Number Masking API
  slug: unifonic-number-masking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unifonic/openapi/unifonic-number-masking-api-openapi.yml
- filename: unifonic-rest-api-openapi.yml
  format: yaml
  label: Unifonic Rest API
  slug: unifonic-rest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unifonic/openapi/unifonic-rest-api-openapi.yml
- filename: unifonic-verifications-api-openapi.yml
  format: yaml
  label: Unifonic Verifications API
  slug: unifonic-verifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unifonic/openapi/unifonic-verifications-api-openapi.yml
- filename: unifonic-webhooks-api-openapi.yml
  format: yaml
  label: Unifonic Webhooks API
  slug: unifonic-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unifonic/openapi/unifonic-webhooks-api-openapi.yml
- filename: unifonic-wrapper-api-openapi.yml
  format: yaml
  label: Unifonic Wrapper API
  slug: unifonic-wrapper-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unifonic/openapi/unifonic-wrapper-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: THE SERVICES ARE INTENDED FOR BUSINESS USE OR USE IN CONNECTION WITH AN INDIVIDUAL’S TRADE, CRAFT, OR PROFESSION ONLY.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Spam messages
    text: Send SPAM Messages as defined in the SMS Service Specific Terms.
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
name: Unifonic
provenance_date: '2026-11-10'
provider_name: Unifonic
provider_slug: unifonic
slug: unifonic-eligibility
source_date: '2026-11-10'
source_filename: unifonic-eligibility.yml
source_heading: Eligibility
source_page: https://www.unifonic.com/en/general-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unifonic\naid: unifonic\nurl: https://www.unifonic.com/en/general-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: THE SERVICES ARE INTENDED FOR BUSINESS USE OR USE IN CONNECTION WITH AN INDIVIDUAL’S TRADE, CRAFT, OR PROFESSION\n    ONLY.\nrestricted_uses:\n- summary: Spam messages\n  text: Send SPAM Messages as defined in the SMS Service Specific Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/unifonic/eligibility/unifonic-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Unifonic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- CPaaS
- Messaging
- SMS
- WhatsApp
- Voice
- Push Notifications
- OTP
- Customer Engagement
- Saudi Arabia
- MENA
---
