---
api_specs:
- filename: verisoul-account-api-openapi.yml
  format: yaml
  label: Verisoul Account API
  slug: verisoul-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-account-api-openapi.yml
- filename: verisoul-email-api-openapi.yml
  format: yaml
  label: Verisoul Email API
  slug: verisoul-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-email-api-openapi.yml
- filename: verisoul-enrollment-api-openapi.yml
  format: yaml
  label: Verisoul Enrollment API
  slug: verisoul-enrollment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-enrollment-api-openapi.yml
- filename: verisoul-list-api-openapi.yml
  format: yaml
  label: Verisoul List API
  slug: verisoul-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-list-api-openapi.yml
- filename: verisoul-phone-api-openapi.yml
  format: yaml
  label: Verisoul Phone API
  slug: verisoul-phone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-phone-api-openapi.yml
- filename: verisoul-public-api-openapi.yml
  format: yaml
  label: Verisoul Public API
  slug: verisoul-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-public-api-openapi.yml
- filename: verisoul-session-api-openapi.yml
  format: yaml
  label: Verisoul Session API
  slug: verisoul-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-session-api-openapi.yml
- filename: verisoul-verification-api-openapi.yml
  format: yaml
  label: Verisoul Verification API
  slug: verisoul-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-verification-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services
    type: individual
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 16 years of age; if you are a child under 16 years of age, please do not attempt to register for or otherwise use the Services
    value: '16'
  restricted_uses:
  - summary: Unlawful or prohibited uses
    text: You will only use the Services in a manner that complies with all laws that apply to you. If your use of the Services is prohibited by applicable laws, then you aren’t authorized to use the Services.
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
name: Verisoul
provenance_date: '2026-11-10'
provider_name: Verisoul
provider_slug: verisoul
slug: verisoul-eligibility
source_date: '2026-11-10'
source_filename: verisoul-eligibility.yml
source_heading: Eligibility
source_page: https://policies.verisoul.ai/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Verisoul\naid: verisoul\nurl: https://policies.verisoul.ai/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services\nrestricted_uses:\n- summary: Unlawful or prohibited uses\n  text: You will only use the Services in a manner that complies with all laws that apply to you. If your use of\n    the Services is prohibited by applicable laws, then you aren’t\
  \ authorized to use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 16 years\n    of age; if you are a child under 16 years of age, please do not attempt to register for or otherwise use the\n    Services\n"
source_yaml_url: https://artifacts.apis.io/verisoul/eligibility/verisoul-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Verisoul's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fraud Prevention
- Identity Verification
- Fake Account Detection
- Device Fingerprinting
- Email Intelligence
- Bot Detection
- KYC
- Trust and Safety
- Risk Scoring
---
