---
api_specs:
- filename: dopesecurity-authorization-api-openapi.yml
  format: yaml
  label: dope.security Authorization API
  slug: dopesecurity-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dopesecurity/openapi/dopesecurity-authorization-api-openapi.yml
- filename: dopesecurity-custom-categories-api-openapi.yml
  format: yaml
  label: dope.security Custom Categories API
  slug: dopesecurity-custom-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dopesecurity/openapi/dopesecurity-custom-categories-api-openapi.yml
- filename: dopesecurity-endpoints-api-openapi.yml
  format: yaml
  label: dope.security Endpoints API
  slug: dopesecurity-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dopesecurity/openapi/dopesecurity-endpoints-api-openapi.yml
- filename: dopesecurity-policies-api-openapi.yml
  format: yaml
  label: dope.security Policies API
  slug: dopesecurity-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dopesecurity/openapi/dopesecurity-policies-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ACCEPTING THE AGREEMENT ON BEHALF OF YOUR EMPLOYER OR ANOTHER PARTY, YOU REPRESENT AND WARRANT THAT YOU HAVE AUTHORITY AS AN AGENT TO ACCEPT THE TERMS AND CONDITIONS OF THIS AGREEMENT ON BEHALF OF THAT PARTY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Anonymization
    text: (vi) use the Service for anonymization
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
name: dope.security
provenance_date: '2026-11-09'
provider_name: dope.security
provider_slug: dopesecurity
slug: dopesecurity-eligibility
source_date: '2026-11-09'
source_filename: dopesecurity-eligibility.yml
source_heading: Eligibility
source_page: https://dope.security/legal/eula
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: dope.security\naid: dopesecurity\nurl: https://dope.security/legal/eula\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ACCEPTING THE AGREEMENT ON BEHALF OF YOUR EMPLOYER OR ANOTHER PARTY, YOU REPRESENT AND WARRANT\n    THAT YOU HAVE AUTHORITY AS AN AGENT TO ACCEPT THE TERMS AND CONDITIONS OF THIS AGREEMENT ON BEHALF OF THAT PARTY\nrestricted_uses:\n- summary: Anonymization\n  text: (vi) use the Service for anonymization\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dopesecurity/eligibility/dopesecurity-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from dope.security's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Security
- Cybersecurity
- Secure Web Gateway
- SASE
- SSE
- Data Loss Prevention
- CASB
- Endpoint Security
---
