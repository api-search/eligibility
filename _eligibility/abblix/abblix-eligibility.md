---
api_specs:
- filename: abblix-connect-api-openapi.yml
  format: yaml
  label: Abblix Connect API
  slug: abblix-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abblix/openapi/abblix-connect-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you confirm that you are at least 18 years old and have full legal capacity to accept these Terms.
    type: individual
  - text: If you use the Site and Services on behalf of an organization, you confirm that you are authorized to accept these Terms on its behalf.
    type: business
  minimum_age:
    text: you confirm that you are at least 18 years old and have full legal capacity to accept these Terms.
    value: '18'
  restricted_uses:
  - summary: Compliance with applicable law
    text: You agree to use the Site and Services in compliance with all applicable laws and regulations, and you are responsible for your own conduct while using them.
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
name: Abblix
provenance_date: '2026-11-09'
provider_name: Abblix
provider_slug: abblix
slug: abblix-eligibility
source_date: '2026-11-09'
source_filename: abblix-eligibility.yml
source_heading: Eligibility
source_page: https://www.abblix.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Abblix\naid: abblix\nurl: https://www.abblix.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you confirm that you are at least 18 years old and have full legal capacity to accept these Terms.\n- type: business\n  text: If you use the Site and Services on behalf of an organization, you confirm that you are authorized to accept\n    these Terms on its behalf.\nrestricted_uses:\n- summary: Compliance with applicable law\n  text: You agree to use the Site and Services in compliance with all applicable laws and regulations,\
  \ and you are\n    responsible for your own conduct while using them.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you confirm that you are at least 18 years old and have full legal capacity to accept these Terms.\n"
source_yaml_url: https://artifacts.apis.io/abblix/eligibility/abblix-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Abblix's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Identity
- OpenID Connect
- OAuth
- Authentication
- .NET
- Shared Signals
---
