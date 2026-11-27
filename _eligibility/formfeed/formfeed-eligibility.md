---
api_specs:
- filename: formfeed-account-api-openapi.yml
  format: yaml
  label: Formfeed Account API
  slug: formfeed-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-account-api-openapi.yml
- filename: formfeed-brand-api-openapi.yml
  format: yaml
  label: Formfeed Brand API
  slug: formfeed-brand-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-brand-api-openapi.yml
- filename: formfeed-compat-api-openapi.yml
  format: yaml
  label: Formfeed Compat API
  slug: formfeed-compat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-compat-api-openapi.yml
- filename: formfeed-files-api-openapi.yml
  format: yaml
  label: Formfeed Files API
  slug: formfeed-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-files-api-openapi.yml
- filename: formfeed-partials-api-openapi.yml
  format: yaml
  label: Formfeed Partials API
  slug: formfeed-partials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-partials-api-openapi.yml
- filename: formfeed-pdf-tools-api-openapi.yml
  format: yaml
  label: Formfeed PDF tools API
  slug: formfeed-pdf-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-pdf-tools-api-openapi.yml
- filename: formfeed-renders-api-openapi.yml
  format: yaml
  label: Formfeed Renders API
  slug: formfeed-renders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-renders-api-openapi.yml
- filename: formfeed-templates-api-openapi.yml
  format: yaml
  label: Formfeed Templates API
  slug: formfeed-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-templates-api-openapi.yml
- filename: formfeed-webhooks-api-openapi.yml
  format: yaml
  label: Formfeed Webhooks API
  slug: formfeed-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal content
    text: You must not render illegal content, attack the service or circumvent limits.
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
name: Formfeed
provenance_date: '2026-11-09'
provider_name: Formfeed
provider_slug: formfeed
slug: formfeed-eligibility
source_date: '2026-11-09'
source_filename: formfeed-eligibility.yml
source_heading: Eligibility
source_page: https://formfeed.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Formfeed\naid: formfeed\nurl: https://formfeed.dev/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal content\n  text: You must not render illegal content, attack the service or circumvent limits.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/formfeed/eligibility/formfeed-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Formfeed's own page on 2026-11-09.
synthetic: false
tags:
- PDF
- Image Generation
- Templates
- Developer Tools
- Software-as-a-Service
---
