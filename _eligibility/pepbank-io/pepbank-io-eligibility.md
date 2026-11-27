---
api_specs:
- filename: pepbank-io-account-api-openapi.yml
  format: yaml
  label: PepBank Account API
  slug: pepbank-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pepbank-io/openapi/pepbank-io-account-api-openapi.yml
- filename: pepbank-io-contribute-api-openapi.yml
  format: yaml
  label: PepBank Contribute API
  slug: pepbank-io-contribute-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pepbank-io/openapi/pepbank-io-contribute-api-openapi.yml
- filename: pepbank-io-evidence-api-openapi.yml
  format: yaml
  label: PepBank Evidence API
  slug: pepbank-io-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pepbank-io/openapi/pepbank-io-evidence-api-openapi.yml
- filename: pepbank-io-exports-api-openapi.yml
  format: yaml
  label: PepBank Exports API
  slug: pepbank-io-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pepbank-io/openapi/pepbank-io-exports-api-openapi.yml
- filename: pepbank-io-peptides-api-openapi.yml
  format: yaml
  label: PepBank Peptides API
  slug: pepbank-io-peptides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pepbank-io/openapi/pepbank-io-peptides-api-openapi.yml
- filename: pepbank-io-records-api-openapi.yml
  format: yaml
  label: PepBank Records API
  slug: pepbank-io-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pepbank-io/openapi/pepbank-io-records-api-openapi.yml
- filename: pepbank-io-sync-api-openapi.yml
  format: yaml
  label: PepBank Sync API
  slug: pepbank-io-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pepbank-io/openapi/pepbank-io-sync-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organization, you confirm that you can accept these Terms for it, and "you" includes that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: use the Service for anything unlawful
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
name: PepBank
provenance_date: '2026-11-10'
provider_name: PepBank
provider_slug: pepbank-io
slug: pepbank-io-eligibility
source_date: '2026-11-10'
source_filename: pepbank-io-eligibility.yml
source_heading: Eligibility
source_page: https://pepbank.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PepBank\naid: pepbank-io\nurl: https://pepbank.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you confirm that you can accept these Terms for it,\n    and \"you\" includes that organization.\nrestricted_uses:\n- summary: Unlawful use\n  text: use the Service for anything unlawful\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/pepbank-io/eligibility/pepbank-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from PepBank's own page on 2026-11-10.
synthetic: false
tags:
- Peptides
- Research
- Database
- Biotechnology
- Free
---
