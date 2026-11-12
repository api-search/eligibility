---
api_specs:
- filename: codeqr-io-analytics-api-openapi.yml
  format: yaml
  label: CodeQR Analytics API
  slug: codeqr-io-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-analytics-api-openapi.yml
- filename: codeqr-io-domains-api-openapi.yml
  format: yaml
  label: CodeQR Domains API
  slug: codeqr-io-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-domains-api-openapi.yml
- filename: codeqr-io-events-api-openapi.yml
  format: yaml
  label: CodeQR Events API
  slug: codeqr-io-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-events-api-openapi.yml
- filename: codeqr-io-folders-api-openapi.yml
  format: yaml
  label: CodeQR Folders API
  slug: codeqr-io-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-folders-api-openapi.yml
- filename: codeqr-io-links-api-openapi.yml
  format: yaml
  label: CodeQR Links API
  slug: codeqr-io-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-links-api-openapi.yml
- filename: codeqr-io-projects-api-openapi.yml
  format: yaml
  label: CodeQR Projects API
  slug: codeqr-io-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-projects-api-openapi.yml
- filename: codeqr-io-qr-codes-api-openapi.yml
  format: yaml
  label: CodeQR QR Codes API
  slug: codeqr-io-qr-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-qr-codes-api-openapi.yml
- filename: codeqr-io-tags-api-openapi.yml
  format: yaml
  label: CodeQR Tags API
  slug: codeqr-io-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-tags-api-openapi.yml
- filename: codeqr-io-track-api-openapi.yml
  format: yaml
  label: CodeQR Track API
  slug: codeqr-io-track-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-track-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use the Service, you must be at least 18 years old or the legal age of majority in your jurisdiction.
    type: individual
  - text: We grant you a limited, non-exclusive, non-transferable, and revocable license to access and use the Service in accordance with these Terms and your plan, including for your business purposes.
    type: business
  minimum_age:
    text: To use the Service, you must be at least 18 years old or the legal age of majority in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: Violate any applicable law or regulation.
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
name: CodeQR
provenance_date: '2026-11-09'
provider_name: CodeQR
provider_slug: codeqr-io
slug: codeqr-io-eligibility
source_date: '2026-11-09'
source_filename: codeqr-io-eligibility.yml
source_heading: Eligibility
source_page: https://codeqr.io/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CodeQR\naid: codeqr-io\nurl: https://codeqr.io/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use the Service, you must be at least 18 years old or the legal age of majority in your jurisdiction.\n- type: business\n  text: We grant you a limited, non-exclusive, non-transferable, and revocable license to access and use the Service\n    in accordance with these Terms and your plan, including for your business purposes.\nrestricted_uses:\n- summary: Unlawful use\n  text: Violate any applicable law or regulation.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use the Service, you must be at least 18 years old or the legal age of majority in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/codeqr-io/eligibility/codeqr-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CodeQR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- QR Codes
- Short Links
- URL Shortener
- Link Management
- Analytics
- Marketing
- MCP
---
