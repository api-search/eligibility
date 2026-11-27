---
api_specs:
- filename: doximity-openid-connect-api-openapi.yml
  format: yaml
  label: Doximity OpenID Connect API
  slug: doximity-openid-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doximity/openapi/doximity-openid-connect-api-openapi.yml
- filename: doximity-oauth-api-openapi.yml
  format: yaml
  label: Doximity O Auth API
  slug: doximity-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doximity/openapi/doximity-oauth-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are designed specifically for users in the United States.
  entity_types:
  - text: a United States physician, medical student, or other healthcare professional
    type: individual
  minimum_age:
    text: you certify that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Competing product development
    text: Use the Services to develop, test, or enhance a competing product or service
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: only Doximity members we have verified are healthcare providers are eligible to use the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Doximity
provenance_date: '2026-11-09'
provider_name: Doximity
provider_slug: doximity
slug: doximity-eligibility
source_date: '2026-11-09'
source_filename: doximity-eligibility.yml
source_heading: Eligibility
source_page: https://www.doximity.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Doximity\naid: doximity\nurl: https://www.doximity.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are designed specifically for users in the United States.\nentity_types:\n- type: individual\n  text: a United States physician, medical student, or other healthcare professional\nrestricted_uses:\n- summary: Competing product development\n  text: Use the Services to develop, test, or enhance a competing product or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: only Doximity members we have verified are healthcare\
  \ providers are eligible to use the Services\nminimum_age:\n  value: '18'\n  text: you certify that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/doximity/eligibility/doximity-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Doximity's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Identity
- OAuth
- OpenID Connect
- Authentication
- Physician Network
- Healthcare
- SSO
- Verification
---
