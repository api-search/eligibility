---
api_specs:
- filename: citation-co-balance-api-openapi.yml
  format: yaml
  label: Citation Balance API
  slug: citation-co-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citation-co/openapi/citation-co-balance-api-openapi.yml
- filename: citation-co-checks-api-openapi.yml
  format: yaml
  label: Citation Checks API
  slug: citation-co-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citation-co/openapi/citation-co-checks-api-openapi.yml
- filename: citation-co-documents-api-openapi.yml
  format: yaml
  label: Citation Documents API
  slug: citation-co-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citation-co/openapi/citation-co-documents-api-openapi.yml
- filename: citation-co-events-api-openapi.yml
  format: yaml
  label: Citation Events API
  slug: citation-co-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citation-co/openapi/citation-co-events-api-openapi.yml
- filename: citation-co-exports-api-openapi.yml
  format: yaml
  label: Citation Exports API
  slug: citation-co-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citation-co/openapi/citation-co-exports-api-openapi.yml
- filename: citation-co-files-api-openapi.yml
  format: yaml
  label: Citation Files API
  slug: citation-co-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citation-co/openapi/citation-co-files-api-openapi.yml
- filename: citation-co-imports-api-openapi.yml
  format: yaml
  label: Citation Imports API
  slug: citation-co-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citation-co/openapi/citation-co-imports-api-openapi.yml
- filename: citation-co-jobs-api-openapi.yml
  format: yaml
  label: Citation Jobs API
  slug: citation-co-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citation-co/openapi/citation-co-jobs-api-openapi.yml
- filename: citation-co-ledger-api-openapi.yml
  format: yaml
  label: Citation Ledger API
  slug: citation-co-ledger-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citation-co/openapi/citation-co-ledger-api-openapi.yml
- filename: citation-co-me-api-openapi.yml
  format: yaml
  label: Citation Me API
  slug: citation-co-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citation-co/openapi/citation-co-me-api-openapi.yml
- filename: citation-co-pricing-api-openapi.yml
  format: yaml
  label: Citation Pricing API
  slug: citation-co-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citation-co/openapi/citation-co-pricing-api-openapi.yml
- filename: citation-co-sources-api-openapi.yml
  format: yaml
  label: Citation Sources API
  slug: citation-co-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citation-co/openapi/citation-co-sources-api-openapi.yml
- filename: citation-co-webhooks-api-openapi.yml
  format: yaml
  label: Citation Webhooks API
  slug: citation-co-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citation-co/openapi/citation-co-webhooks-api-openapi.yml
- filename: citation-co-write-api-openapi.yml
  format: yaml
  label: Citation Write API
  slug: citation-co-write-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citation-co/openapi/citation-co-write-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be legally able to enter an agreement for the service.
    type: individual
  minimum_age:
    text: Citation is not intended for children under 13.
    value: '13'
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
name: Citation
provenance_date: '2026-11-09'
provider_name: Citation
provider_slug: citation-co
slug: citation-co-eligibility
source_date: '2026-11-09'
source_filename: citation-co-eligibility.yml
source_heading: Eligibility
source_page: https://citation.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Citation\naid: citation-co\nurl: https://citation.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be legally able to enter an agreement for the service.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Citation is not intended for children under 13.\n"
source_yaml_url: https://artifacts.apis.io/citation-co/eligibility/citation-co-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Citation's own page on 2026-11-09.
synthetic: false
tags:
- Citations
- Bibliography
- WritingTool
- Academic
- Productivity
---
