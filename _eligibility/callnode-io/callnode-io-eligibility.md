---
api_specs:
- filename: callnode-io-call-records-api-openapi.yml
  format: yaml
  label: CallNode Call Records API
  slug: callnode-io-call-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-call-records-api-openapi.yml
- filename: callnode-io-email-api-openapi.yml
  format: yaml
  label: CallNode Email API
  slug: callnode-io-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-email-api-openapi.yml
- filename: callnode-io-faxes-api-openapi.yml
  format: yaml
  label: CallNode Faxes API
  slug: callnode-io-faxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-faxes-api-openapi.yml
- filename: callnode-io-messaging-api-openapi.yml
  format: yaml
  label: CallNode Messaging API
  slug: callnode-io-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-messaging-api-openapi.yml
- filename: callnode-io-outbound-calls-api-openapi.yml
  format: yaml
  label: CallNode Outbound Calls API
  slug: callnode-io-outbound-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-outbound-calls-api-openapi.yml
- filename: callnode-io-phone-numbers-api-openapi.yml
  format: yaml
  label: CallNode Phone Numbers API
  slug: callnode-io-phone-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-phone-numbers-api-openapi.yml
- filename: callnode-io-sip-trunks-api-openapi.yml
  format: yaml
  label: CallNode SIP Trunks API
  slug: callnode-io-sip-trunks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-sip-trunks-api-openapi.yml
- filename: callnode-io-wholesale-api-openapi.yml
  format: yaml
  label: CallNode Wholesale API
  slug: callnode-io-wholesale-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-wholesale-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Ordering requires an activated wholesale account and completed business verification.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Robocalls without consent
    text: 'Robocalls: Automated calling campaigns without consent'
  verification:
    approval_required: true
    kyb: true
    kyc: null
    text: Outbound calling is disabled on new accounts until you provide your legal business name, website, calling use case, and a description of how you obtain consent, and we approve it.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CallNode
provenance_date: '2026-11-09'
provider_name: CallNode
provider_slug: callnode-io
slug: callnode-io-eligibility
source_date: '2026-11-09'
source_filename: callnode-io-eligibility.yml
source_heading: Eligibility
source_page: https://callnode.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CallNode\naid: callnode-io\nurl: https://callnode.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Ordering requires an activated wholesale account and completed business verification.\nrestricted_uses:\n- summary: Robocalls without consent\n  text: 'Robocalls: Automated calling campaigns without consent'\nverification:\n  kyc: null\n  kyb: true\n  approval_required: true\n  text: Outbound calling is disabled on new accounts until you provide your legal business name, website, calling\n    use case, and a description of how you\
  \ obtain consent, and we approve it.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/callnode-io/eligibility/callnode-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from CallNode's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice AI
- Telephony
- Phone Numbers
- SMS
- Webhook
- SIP Trunking
- AI Agents
- Communications
---
