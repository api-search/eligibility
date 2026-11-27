---
api_specs:
- filename: accessibe-accounts-api-openapi.yml
  format: yaml
  label: accessiBe Accounts API
  slug: accessibe-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accessibe/openapi/accessibe-accounts-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Governing law differs for US/Canada versus outside; Sanctions clause: you confirm you are not located in a country subject to U.S. or Israeli sanctions.'
  entity_types:
  - text: If you are agreeing on behalf of an organization, you also confirm that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: Our Services are intended for users who are at least 18 years old and legally able to enter into binding contracts.
    value: '18'
  restricted_uses:
  - summary: Unlawful or discriminatory content sites
    text: use the Services in connection with any website that contains illegal, discriminatory, or otherwise unlawful content
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
name: accessiBe
provenance_date: '2026-11-09'
provider_name: accessiBe
provider_slug: accessibe
slug: accessibe-eligibility
source_date: '2026-11-09'
source_filename: accessibe-eligibility.yml
source_heading: Eligibility
source_page: https://accessibe.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: accessiBe\naid: accessibe\nurl: https://accessibe.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: 'Governing law differs for US/Canada versus outside; Sanctions clause: you confirm you are not located in\n    a country subject to U.S. or Israeli sanctions.'\nentity_types:\n- type: business\n  text: If you are agreeing on behalf of an organization, you also confirm that you have the authority to bind that\n    organization to these Terms.\nrestricted_uses:\n- summary: Unlawful or discriminatory content sites\n  text: use the Services in connection\
  \ with any website that contains illegal, discriminatory, or otherwise unlawful\n    content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Services are intended for users who are at least 18 years old and legally able to enter into binding\n    contracts.\n"
source_yaml_url: https://artifacts.apis.io/accessibe/eligibility/accessibe-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from accessiBe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accessibility
- Web Accessibility
- WCAG
- ADA Compliance
- Compliance
- Developer Tools
- Testing
- Quality Assurance
- Artificial Intelligence
---
