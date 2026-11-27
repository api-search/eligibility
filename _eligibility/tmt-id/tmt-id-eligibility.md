---
api_specs:
- filename: tmt-id-authenticate-api-openapi.yml
  format: yaml
  label: TMT ID Authenticate API
  slug: tmt-id-authenticate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-authenticate-api-openapi.yml
- filename: tmt-id-http-api-api-openapi.yml
  format: yaml
  label: TMT ID HTTP API
  slug: tmt-id-http-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-http-api-api-openapi.yml
- filename: tmt-id-http-api-v1-3-api-openapi.yml
  format: yaml
  label: TMT ID HTTP API v1.3 API
  slug: tmt-id-http-api-v1-3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-http-api-v1-3-api-openapi.yml
- filename: tmt-id-http-api-v2-0-api-openapi.yml
  format: yaml
  label: TMT ID HTTP API v2.0 API
  slug: tmt-id-http-api-v2-0-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-http-api-v2-0-api-openapi.yml
- filename: tmt-id-network-biometrics-api-openapi.yml
  format: yaml
  label: TMT ID Network Biometrics API
  slug: tmt-id-network-biometrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-network-biometrics-api-openapi.yml
- filename: tmt-id-service-api-openapi.yml
  format: yaml
  label: TMT ID Service API
  slug: tmt-id-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-service-api-openapi.yml
- filename: tmt-id-standard-api-call-api-openapi.yml
  format: yaml
  label: TMT ID Standard API Call API
  slug: tmt-id-standard-api-call-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-standard-api-call-api-openapi.yml
- filename: tmt-id-v2-deprecated-api-openapi.yml
  format: yaml
  label: TMT ID v2 (deprecated) API
  slug: tmt-id-v2-deprecated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-v2-deprecated-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no promise that the Site is appropriate or available for use in locations outside of the UK.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Misuse or attack of the Site
    text: misuse or attack our Site by knowingly introducing viruses, trojans, worms, logic bombs or any other material which is malicious or technologically harmful
  - source: https://tmtid.com/acceptable-use-policy/
    summary: Unacceptable uses of the Site
    text: for any purpose that is unlawful under any applicable law or prohibited by this Policy or our website terms and conditions of use
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
name: TMT ID
provenance_date: '2026-11-10'
provider_name: TMT ID
provider_slug: tmt-id
slug: tmt-id-eligibility
source_date: '2026-11-10'
source_filename: tmt-id-eligibility.yml
source_heading: Eligibility
source_page: https://tmtid.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TMT ID\naid: tmt-id\nurl: https://tmtid.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://tmtid.com/acceptable-use-policy/\n  - https://tmtid.com/terms-and-conditions/\ncountries:\n  served: []\n  excluded: []\n  text: We make no promise that the Site is appropriate or available for use in locations outside of the UK.\nentity_types: []\nrestricted_uses:\n- summary: Misuse or attack of the Site\n  text: misuse or attack our Site by knowingly introducing viruses, trojans, worms, logic bombs or any other material\n    which is malicious or technologically harmful\n- summary: Unacceptable\
  \ uses of the Site\n  text: for any purpose that is unlawful under any applicable law or prohibited by this Policy or our website terms\n    and conditions of use\n  source: https://tmtid.com/acceptable-use-policy/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tmt-id/eligibility/tmt-id-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from TMT ID's own page on 2026-11-10.
synthetic: false
tags:
- Telecommunications
- United Kingdom
- Identity Verification
- Mobile Identity
- SIM Swap
- Fraud Prevention
- Number Intelligence
- Silent Network Authentication
- GSMA Open Gateway
- Network APIs
- ENUM
- KYC
---
