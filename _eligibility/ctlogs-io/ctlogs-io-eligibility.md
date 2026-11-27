---
api_specs:
- filename: ctlogs-io-certs-api-openapi.yml
  format: yaml
  label: CTlogs.io Certs API
  slug: ctlogs-io-certs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctlogs-io/openapi/ctlogs-io-certs-api-openapi.yml
- filename: ctlogs-io-me-api-openapi.yml
  format: yaml
  label: CTlogs.io Me API
  slug: ctlogs-io-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctlogs-io/openapi/ctlogs-io-me-api-openapi.yml
- filename: ctlogs-io-search-api-openapi.yml
  format: yaml
  label: CTlogs.io Search API
  slug: ctlogs-io-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctlogs-io/openapi/ctlogs-io-search-api-openapi.yml
- filename: ctlogs-io-stats-api-openapi.yml
  format: yaml
  label: CTlogs.io Stats API
  slug: ctlogs-io-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctlogs-io/openapi/ctlogs-io-stats-api-openapi.yml
- filename: ctlogs-io-subdomains-api-openapi.yml
  format: yaml
  label: CTlogs.io Subdomains API
  slug: ctlogs-io-subdomains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctlogs-io/openapi/ctlogs-io-subdomains-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to open an account, to subscribe, or to use the service.
    type: individual
  - text: Accounts are for a single organisation.
    type: business
  minimum_age:
    text: You must be at least 18 years old to open an account, to subscribe, or to use the service.
    value: '18'
  restricted_uses:
  - summary: No profiling of natural persons
    text: use the service or its output to identify, locate, profile, market to or generate leads on natural persons, or to enrich data about them
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: To open an account you must provide a valid email address and verify it.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CTlogs.io
provenance_date: '2026-11-09'
provider_name: CTlogs.io
provider_slug: ctlogs-io
slug: ctlogs-io-eligibility
source_date: '2026-11-09'
source_filename: ctlogs-io-eligibility.yml
source_heading: Eligibility
source_page: https://ctlogs.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CTlogs.io\naid: ctlogs-io\nurl: https://ctlogs.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to open an account, to subscribe, or to use the service.\n- type: business\n  text: Accounts are for a single organisation.\nrestricted_uses:\n- summary: No profiling of natural persons\n  text: use the service or its output to identify, locate, profile, market to or generate leads on natural persons,\n    or to enrich data about them\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ false\n  text: To open an account you must provide a valid email address and verify it.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to open an account, to subscribe, or to use the service.\n"
source_yaml_url: https://artifacts.apis.io/ctlogs-io/eligibility/ctlogs-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from CTlogs.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Certificate Transparency
- TLS Certificates
- SSL
- Security
- PKI
- Domains
- MCP
---
