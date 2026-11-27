---
api_specs:
- filename: numbers-online-account-api-openapi.yml
  format: yaml
  label: Numbers Online Account API
  slug: numbers-online-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-account-api-openapi.yml
- filename: numbers-online-community-reporting-api-openapi.yml
  format: yaml
  label: Numbers Online Community reporting API
  slug: numbers-online-community-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-community-reporting-api-openapi.yml
- filename: numbers-online-inbound-api-openapi.yml
  format: yaml
  label: Numbers Online Inbound API
  slug: numbers-online-inbound-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-inbound-api-openapi.yml
- filename: numbers-online-lookup-api-openapi.yml
  format: yaml
  label: Numbers Online Lookup API
  slug: numbers-online-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-lookup-api-openapi.yml
- filename: numbers-online-mcp-api-openapi.yml
  format: yaml
  label: Numbers Online MCP API
  slug: numbers-online-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-mcp-api-openapi.yml
- filename: numbers-online-msp-api-openapi.yml
  format: yaml
  label: Numbers Online MSP API
  slug: numbers-online-msp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-msp-api-openapi.yml
- filename: numbers-online-outbound-api-openapi.yml
  format: yaml
  label: Numbers Online Outbound API
  slug: numbers-online-outbound-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-outbound-api-openapi.yml
- filename: numbers-online-parsing-api-openapi.yml
  format: yaml
  label: Numbers Online Parsing API
  slug: numbers-online-parsing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-parsing-api-openapi.yml
- filename: numbers-online-pbx-api-openapi.yml
  format: yaml
  label: Numbers Online PBX API
  slug: numbers-online-pbx-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-pbx-api-openapi.yml
- filename: numbers-online-receipts-api-openapi.yml
  format: yaml
  label: Numbers Online Receipts API
  slug: numbers-online-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-receipts-api-openapi.yml
- filename: numbers-online-reference-api-openapi.yml
  format: yaml
  label: Numbers Online Reference API
  slug: numbers-online-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-reference-api-openapi.yml
- filename: numbers-online-sbc-sip-api-openapi.yml
  format: yaml
  label: Numbers Online SBC / SIP API
  slug: numbers-online-sbc-sip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-sbc-sip-api-openapi.yml
- filename: numbers-online-system-api-openapi.yml
  format: yaml
  label: Numbers Online System API
  slug: numbers-online-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-system-api-openapi.yml
- filename: numbers-online-trust-api-openapi.yml
  format: yaml
  label: Numbers Online Trust API
  slug: numbers-online-trust-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-trust-api-openapi.yml
- filename: numbers-online-webhooks-api-openapi.yml
  format: yaml
  label: Numbers Online Webhooks API
  slug: numbers-online-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You confirm that you are at least 18 years old and legally able to enter into a contract.
    type: individual
  - text: If you use the Service on behalf of a company, organisation or other legal entity, you represent that you are authorised to bind that entity
    type: business
  minimum_age:
    text: You confirm that you are at least 18 years old and legally able to enter into a contract.
    value: '18'
  restricted_uses:
  - summary: No eligibility decisions under FCRA-type laws
    text: 'You may not use the Service to decide a person''s eligibility for: (a) credit or lending; (b) insurance; (c) employment, volunteering or background screening; (d) housing or tenancy'
  - summary: No sole basis for significant decisions
    text: You must not use it as the sole or decisive basis for any decision that produces legal effects concerning a person or similarly significantly affects them
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
name: Numbers Online
provenance_date: '2026-11-10'
provider_name: Numbers Online
provider_slug: numbers-online
slug: numbers-online-eligibility
source_date: '2026-11-10'
source_filename: numbers-online-eligibility.yml
source_heading: Eligibility
source_page: https://numbers.online/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Numbers Online\naid: numbers-online\nurl: https://numbers.online/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You confirm that you are at least 18 years old and legally able to enter into a contract.\n- type: business\n  text: If you use the Service on behalf of a company, organisation or other legal entity, you represent that you\n    are authorised to bind that entity\nrestricted_uses:\n- summary: No eligibility decisions under FCRA-type laws\n  text: 'You may not use the Service to decide a person''s eligibility for: (a)\
  \ credit or lending; (b) insurance;\n    (c) employment, volunteering or background screening; (d) housing or tenancy'\n- summary: No sole basis for significant decisions\n  text: You must not use it as the sole or decisive basis for any decision that produces legal effects concerning\n    a person or similarly significantly affects them\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You confirm that you are at least 18 years old and legally able to enter into a contract.\n"
source_yaml_url: https://artifacts.apis.io/numbers-online/eligibility/numbers-online-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Numbers Online's own page on 2026-11-10.
synthetic: false
tags:
- Phone Intelligence
- Caller ID
- CNAM
- Reverse Phone Lookup
- Spam Detection
- Do Not Call
- Telephony
- STIR/SHAKEN
- MCP
- Agent-Native
- Compliance
- Company
- A2A
---
