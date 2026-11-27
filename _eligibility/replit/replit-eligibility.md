---
api_specs:
- filename: replit-deployments-api-openapi.yml
  format: yaml
  label: Replit Deployments API
  slug: replit-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replit/openapi/replit-deployments-api-openapi.yml
- filename: replit-repls-api-openapi.yml
  format: yaml
  label: Replit Repls API
  slug: replit-repls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replit/openapi/replit-repls-api-openapi.yml
- filename: replit-users-api-openapi.yml
  format: yaml
  label: Replit Users API
  slug: replit-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replit/openapi/replit-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use the Service. If you are under 18, you must have your parent or guardian’s permission to use the Service.
    type: individual
  - text: You must have the authority to enter into these Terms on your own behalf and, if applicable, on behalf of any entity or individual for whom you create an account
    type: business
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Prohibited content and conduct
    text: Promoting illegal conduct. Hoaxes, malware, and pyramid schemes.
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
name: Replit
provenance_date: '2026-11-10'
provider_name: Replit
provider_slug: replit
slug: replit-eligibility
source_date: '2026-11-10'
source_filename: replit-eligibility.yml
source_heading: Eligibility
source_page: https://replit.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Replit\naid: replit\nurl: https://replit.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Service. If you are under 18, you must have your parent or\n    guardian’s permission to use the Service.\n- type: business\n  text: You must have the authority to enter into these Terms on your own behalf and, if applicable, on behalf of\n    any entity or individual for whom you create an account\nrestricted_uses:\n- summary: Prohibited content and conduct\n  text: Promoting illegal\
  \ conduct. Hoaxes, malware, and pyramid schemes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/replit/eligibility/replit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Replit's own page on 2026-11-10.
synthetic: false
tags:
- Code
- Compiling
- Developer Tools
- Development Environment
- Programming Language
- Version Control
---
