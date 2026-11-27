---
api_specs:
- filename: doconda-com-dashboard-api-openapi.yml
  format: yaml
  label: doconda-com Dashboard API
  slug: doconda-com-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doconda-com/openapi/doconda-com-dashboard-api-openapi.yml
- filename: doconda-com-documents-api-openapi.yml
  format: yaml
  label: doconda-com Documents API
  slug: doconda-com-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doconda-com/openapi/doconda-com-documents-api-openapi.yml
- filename: doconda-com-editor-api-openapi.yml
  format: yaml
  label: doconda-com Editor API
  slug: doconda-com-editor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doconda-com/openapi/doconda-com-editor-api-openapi.yml
- filename: doconda-com-files-api-openapi.yml
  format: yaml
  label: doconda-com Files API
  slug: doconda-com-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doconda-com/openapi/doconda-com-files-api-openapi.yml
- filename: doconda-com-webhooks-api-openapi.yml
  format: yaml
  label: doconda-com Webhooks API
  slug: doconda-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doconda-com/openapi/doconda-com-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Doconda is a service for businesses and professionals: it is not aimed at consumers.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or infringing content
    text: illegal content, content that infringes third-party rights, or to deceive or defraud;
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
name: doconda-com
provenance_date: '2026-11-09'
provider_name: doconda-com
provider_slug: doconda-com
slug: doconda-com-eligibility
source_date: '2026-11-09'
source_filename: doconda-com-eligibility.yml
source_heading: Eligibility
source_page: https://doconda.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: doconda-com\naid: doconda-com\nurl: https://doconda.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'Doconda is a service for businesses and professionals: it is not aimed at consumers.'\nrestricted_uses:\n- summary: Illegal or infringing content\n  text: illegal content, content that infringes third-party rights, or to deceive or defraud;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/doconda-com/eligibility/doconda-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from doconda-com's own page on 2026-11-09.
synthetic: false
tags:
- Document Generation
- Conversion
- Automation
- Artificial Intelligence
---
