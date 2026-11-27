---
api_specs:
- filename: templafy-datasourcefields-api-openapi.yml
  format: yaml
  label: Templafy DataSourceFields API
  slug: templafy-datasourcefields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-datasourcefields-api-openapi.yml
- filename: templafy-datasourceitemfields-api-openapi.yml
  format: yaml
  label: Templafy DataSourceItemFields API
  slug: templafy-datasourceitemfields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-datasourceitemfields-api-openapi.yml
- filename: templafy-datasourceitems-api-openapi.yml
  format: yaml
  label: Templafy DataSourceItems API
  slug: templafy-datasourceitems-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-datasourceitems-api-openapi.yml
- filename: templafy-documents-api-openapi.yml
  format: yaml
  label: Templafy Documents API
  slug: templafy-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-documents-api-openapi.yml
- filename: templafy-emailelements-api-openapi.yml
  format: yaml
  label: Templafy EmailElements API
  slug: templafy-emailelements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-emailelements-api-openapi.yml
- filename: templafy-folders-api-openapi.yml
  format: yaml
  label: Templafy Folders API
  slug: templafy-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-folders-api-openapi.yml
- filename: templafy-images-api-openapi.yml
  format: yaml
  label: Templafy Images API
  slug: templafy-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-images-api-openapi.yml
- filename: templafy-libraries-api-openapi.yml
  format: yaml
  label: Templafy Libraries API
  slug: templafy-libraries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-libraries-api-openapi.yml
- filename: templafy-links-api-openapi.yml
  format: yaml
  label: Templafy Links API
  slug: templafy-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-links-api-openapi.yml
- filename: templafy-presentations-api-openapi.yml
  format: yaml
  label: Templafy Presentations API
  slug: templafy-presentations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-presentations-api-openapi.yml
- filename: templafy-slideelements-api-openapi.yml
  format: yaml
  label: Templafy SlideElements API
  slug: templafy-slideelements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-slideelements-api-openapi.yml
- filename: templafy-slides-api-openapi.yml
  format: yaml
  label: Templafy Slides API
  slug: templafy-slides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-slides-api-openapi.yml
- filename: templafy-spaces-api-openapi.yml
  format: yaml
  label: Templafy Spaces API
  slug: templafy-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-spaces-api-openapi.yml
- filename: templafy-spreadsheets-api-openapi.yml
  format: yaml
  label: Templafy Spreadsheets API
  slug: templafy-spreadsheets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-spreadsheets-api-openapi.yml
- filename: templafy-textelements-api-openapi.yml
  format: yaml
  label: Templafy TextElements API
  slug: templafy-textelements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-textelements-api-openapi.yml
- filename: templafy-pdfs-api-openapi.yml
  format: yaml
  label: Templafy Pdfs API
  slug: templafy-pdfs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-pdfs-api-openapi.yml
- filename: templafy-data-sources-api-openapi.yml
  format: yaml
  label: Templafy Data Sources API
  slug: templafy-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/templafy/openapi/templafy-data-sources-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services and this Agreement are intended solely for legal entities and individuals acting in a professional or business capacity, including sole proprietors.
    type: business
  - text: The Services and this Agreement are intended solely for legal entities and individuals acting in a professional or business capacity, including sole proprietors.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing use
    text: use the Services in any manner or for any purpose that infringes, misappropriates, or otherwise violates any intellectual property right or other right of any person, or that violates any applicable law
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
name: Templafy
provenance_date: '2026-11-10'
provider_name: Templafy
provider_slug: templafy
slug: templafy-eligibility
source_date: '2026-11-10'
source_filename: templafy-eligibility.yml
source_heading: Eligibility
source_page: https://www.templafy.com/home/legal/templafy-saas-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Templafy\naid: templafy\nurl: https://www.templafy.com/home/legal/templafy-saas-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services and this Agreement are intended solely for legal entities and individuals acting in a professional\n    or business capacity, including sole proprietors.\n- type: individual\n  text: The Services and this Agreement are intended solely for legal entities and individuals acting in a professional\n    or business capacity, including sole proprietors.\nrestricted_uses:\n- summary: Unlawful\
  \ or infringing use\n  text: use the Services in any manner or for any purpose that infringes, misappropriates, or otherwise violates\n    any intellectual property right or other right of any person, or that violates any applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/templafy/eligibility/templafy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Templafy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Document Generation
- Templates
- Content Management
- Digital Asset Management
- Document Automation
- Productivity
- Enterprise
- Software-as-a-Service
---
