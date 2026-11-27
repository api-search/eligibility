---
api_specs:
- filename: blinkpdf-io-account-api-openapi.yml
  format: yaml
  label: blinkpdf-io Account API
  slug: blinkpdf-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-account-api-openapi.yml
- filename: blinkpdf-io-compose-api-openapi.yml
  format: yaml
  label: blinkpdf-io Compose API
  slug: blinkpdf-io-compose-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-compose-api-openapi.yml
- filename: blinkpdf-io-discovery-api-openapi.yml
  format: yaml
  label: blinkpdf-io Discovery API
  slug: blinkpdf-io-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-discovery-api-openapi.yml
- filename: blinkpdf-io-docs-api-openapi.yml
  format: yaml
  label: blinkpdf-io Docs API
  slug: blinkpdf-io-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-docs-api-openapi.yml
- filename: blinkpdf-io-fill-api-openapi.yml
  format: yaml
  label: blinkpdf-io Fill API
  slug: blinkpdf-io-fill-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-fill-api-openapi.yml
- filename: blinkpdf-io-fonts-api-openapi.yml
  format: yaml
  label: blinkpdf-io Fonts API
  slug: blinkpdf-io-fonts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-fonts-api-openapi.yml
- filename: blinkpdf-io-health-api-openapi.yml
  format: yaml
  label: blinkpdf-io Health API
  slug: blinkpdf-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-health-api-openapi.yml
- filename: blinkpdf-io-layoutdocument-api-openapi.yml
  format: yaml
  label: blinkpdf-io Layout Document API
  slug: blinkpdf-io-layoutdocument-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-layoutdocument-api-openapi.yml
- filename: blinkpdf-io-pages-api-openapi.yml
  format: yaml
  label: blinkpdf-io Pages API
  slug: blinkpdf-io-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-pages-api-openapi.yml
- filename: blinkpdf-io-read-api-openapi.yml
  format: yaml
  label: blinkpdf-io Read API
  slug: blinkpdf-io-read-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-read-api-openapi.yml
- filename: blinkpdf-io-render-api-openapi.yml
  format: yaml
  label: blinkpdf-io Render API
  slug: blinkpdf-io-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-render-api-openapi.yml
- filename: blinkpdf-io-sandwichdocument-api-openapi.yml
  format: yaml
  label: blinkpdf-io Sandwich Document API
  slug: blinkpdf-io-sandwichdocument-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-sandwichdocument-api-openapi.yml
- filename: blinkpdf-io-stamp-api-openapi.yml
  format: yaml
  label: blinkpdf-io Stamp API
  slug: blinkpdf-io-stamp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-stamp-api-openapi.yml
- filename: blinkpdf-io-templates-api-openapi.yml
  format: yaml
  label: blinkpdf-io Templates API
  slug: blinkpdf-io-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-templates-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use restrictions
    text: You may use the Service only for lawful purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Email verification is required before an account can be used.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: blinkpdf-io
provenance_date: '2026-11-09'
provider_name: blinkpdf-io
provider_slug: blinkpdf-io
slug: blinkpdf-io-eligibility
source_date: '2026-11-09'
source_filename: blinkpdf-io-eligibility.yml
source_heading: Eligibility
source_page: https://blinkpdf.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: blinkpdf-io\naid: blinkpdf-io\nurl: https://blinkpdf.io/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization.\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: You may use the Service only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Email verification is required before an account can be used.\nminimum_age:\n  value: null\n \
  \ text: null\n"
source_yaml_url: https://artifacts.apis.io/blinkpdf-io/eligibility/blinkpdf-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from blinkpdf-io's own page on 2026-11-09.
synthetic: false
tags:
- PDF
- Document Processing
- Software-as-a-Service
- Automation
---
