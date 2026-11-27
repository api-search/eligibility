---
api_specs:
- filename: emailverifier-dev-domains-api-openapi.yml
  format: yaml
  label: emailverifier-dev Domains API
  slug: emailverifier-dev-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailverifier-dev/openapi/emailverifier-dev-domains-api-openapi.yml
- filename: emailverifier-dev-usage-api-openapi.yml
  format: yaml
  label: emailverifier-dev Usage API
  slug: emailverifier-dev-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailverifier-dev/openapi/emailverifier-dev-usage-api-openapi.yml
- filename: emailverifier-dev-verification-api-openapi.yml
  format: yaml
  label: emailverifier-dev Verification API
  slug: emailverifier-dev-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailverifier-dev/openapi/emailverifier-dev-verification-api-openapi.yml
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
  - summary: Acceptable use restrictions
    text: Do not use the service to break the law, invade privacy, harvest addresses, send spam, bypass consent requirements, attack systems, resell access without permission, or interfere with service availability.
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
name: emailverifier-dev
provenance_date: '2026-11-09'
provider_name: emailverifier-dev
provider_slug: emailverifier-dev
slug: emailverifier-dev-eligibility
source_date: '2026-11-09'
source_filename: emailverifier-dev-eligibility.yml
source_heading: Eligibility
source_page: https://emailverifier.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: emailverifier-dev\naid: emailverifier-dev\nurl: https://emailverifier.dev/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: Do not use the service to break the law, invade privacy, harvest addresses, send spam, bypass consent requirements,\n    attack systems, resell access without permission, or interfere with service availability.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/emailverifier-dev/eligibility/emailverifier-dev-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from emailverifier-dev's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Verification
- Software-as-a-Service
- Data Quality
---
