---
api_specs:
- filename: descope-apps-api-openapi.yml
  format: yaml
  label: Descope Apps API
  slug: descope-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descope/openapi/descope-apps-api-openapi.yml
- filename: descope-auth-api-openapi.yml
  format: yaml
  label: Descope Auth API
  slug: descope-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descope/openapi/descope-auth-api-openapi.yml
- filename: descope-custom-attributes-api-openapi.yml
  format: yaml
  label: Descope Custom Attributes API
  slug: descope-custom-attributes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descope/openapi/descope-custom-attributes-api-openapi.yml
- filename: descope-email-api-openapi.yml
  format: yaml
  label: Descope Email API
  slug: descope-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descope/openapi/descope-email-api-openapi.yml
- filename: descope-embedded-link-api-openapi.yml
  format: yaml
  label: Descope Embedded Link API
  slug: descope-embedded-link-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descope/openapi/descope-embedded-link-api-openapi.yml
- filename: descope-fedcm-api-openapi.yml
  format: yaml
  label: Descope Fedcm API
  slug: descope-fedcm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descope/openapi/descope-fedcm-api-openapi.yml
- filename: descope-instant-message-im-api-openapi.yml
  format: yaml
  label: Descope Instant Message (IM) API
  slug: descope-instant-message-im-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descope/openapi/descope-instant-message-im-api-openapi.yml
- filename: descope-keys-api-openapi.yml
  format: yaml
  label: Descope Keys API
  slug: descope-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descope/openapi/descope-keys-api-openapi.yml
- filename: descope-mgmt-api-openapi.yml
  format: yaml
  label: Descope Mgmt API
  slug: descope-mgmt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descope/openapi/descope-mgmt-api-openapi.yml
- filename: descope-scim-api-openapi.yml
  format: yaml
  label: Descope Scim API
  slug: descope-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descope/openapi/descope-scim-api-openapi.yml
- filename: descope-text-message-sms-api-openapi.yml
  format: yaml
  label: Descope Text Message (SMS) API
  slug: descope-text-message-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descope/openapi/descope-text-message-sms-api-openapi.yml
- filename: descope-verification-api-openapi.yml
  format: yaml
  label: Descope Verification API
  slug: descope-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descope/openapi/descope-verification-api-openapi.yml
- filename: descope-voice-message-phone-api-openapi.yml
  format: yaml
  label: Descope Voice Message (Phone) API
  slug: descope-voice-message-phone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descope/openapi/descope-voice-message-phone-api-openapi.yml
- filename: descope-well-known-api-openapi.yml
  format: yaml
  label: Descope .well Known API
  slug: descope-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descope/openapi/descope-well-known-api-openapi.yml
- filename: descope-oauth2-api-openapi.yml
  format: yaml
  label: Descope Oauth2 API
  slug: descope-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descope/openapi/descope-oauth2-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk environments
    text: Customer will not use the Service in connection with any high-risk, hazardous environments requiring fail-safe performance, including, without limitation, in the operation of aircraft systems, air traffic control, nuclear facilities, weapon systems
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
name: Descope
provenance_date: '2026-11-09'
provider_name: Descope
provider_slug: descope
slug: descope-eligibility
source_date: '2026-11-09'
source_filename: descope-eligibility.yml
source_heading: Eligibility
source_page: https://www.descope.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Descope\naid: descope\nurl: https://www.descope.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High-risk environments\n  text: Customer will not use the Service in connection with any high-risk, hazardous environments requiring fail-safe\n    performance, including, without limitation, in the operation of aircraft systems, air traffic control, nuclear\n    facilities, weapon systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/descope/eligibility/descope-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Descope's own page on 2026-11-09.
synthetic: false
tags:
- Authentication
- Identity
- CIAM
- Passwordless
- Passkeys
- MFA
- SSO
- OAuth
- OpenID Connect
- SAML
- SCIM
- Authorization
- FGA
- Agentic Identity
- MCP
- Identity Federation
---
