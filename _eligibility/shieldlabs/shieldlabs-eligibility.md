---
api_specs:
- filename: shieldlabs-history-api-api-openapi.yml
  format: yaml
  label: ShieldLabs History API
  slug: shieldlabs-history-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shieldlabs/openapi/shieldlabs-history-api-api-openapi.yml
- filename: shieldlabs-management-api-api-openapi.yml
  format: yaml
  label: ShieldLabs Management API
  slug: shieldlabs-management-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shieldlabs/openapi/shieldlabs-management-api-api-openapi.yml
- filename: shieldlabs-shieldlabs-api-api-openapi.yml
  format: yaml
  label: ShieldLabs API
  slug: shieldlabs-shieldlabs-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shieldlabs/openapi/shieldlabs-shieldlabs-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is offered for business use (B2B) only.
    type: business
  minimum_age:
    text: the individual creating the account is at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No consumer or personal use
    text: Consumer or personal use is not permitted.
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
name: ShieldLabs
provenance_date: '2026-11-10'
provider_name: ShieldLabs
provider_slug: shieldlabs
slug: shieldlabs-eligibility
source_date: '2026-11-10'
source_filename: shieldlabs-eligibility.yml
source_heading: Eligibility
source_page: https://docs.shieldlabs.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ShieldLabs\naid: shieldlabs\nurl: https://docs.shieldlabs.ai/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is offered for business use (B2B) only.\nrestricted_uses:\n- summary: No consumer or personal use\n  text: Consumer or personal use is not permitted.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the individual creating the account is at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/shieldlabs/eligibility/shieldlabs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ShieldLabs's own page on 2026-11-10.
synthetic: false
tags:
- Fraud Prevention
- Abuse Prevention
- Visitor Identification
- Device Fingerprinting
- Bot Detection
- vpn-proxy-detection
- Risk Scoring
- Identity
- Security
- Webhook
- Traffic Quality
- A2A
---
