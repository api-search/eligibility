---
api_specs:
- filename: pixepi-apps-api-openapi.yml
  format: yaml
  label: Pixepi Apps API
  slug: pixepi-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixepi/openapi/pixepi-apps-api-openapi.yml
- filename: pixepi-jobs-api-openapi.yml
  format: yaml
  label: Pixepi Jobs API
  slug: pixepi-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixepi/openapi/pixepi-jobs-api-openapi.yml
- filename: pixepi-usage-api-openapi.yml
  format: yaml
  label: Pixepi Usage API
  slug: pixepi-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixepi/openapi/pixepi-usage-api-openapi.yml
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
  - summary: Illegal or rights-infringing files
    text: processing files that are illegal, infringe rights or violate the rights of others.
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
name: Pixepi
provenance_date: '2026-11-10'
provider_name: Pixepi
provider_slug: pixepi
slug: pixepi-eligibility
source_date: '2026-11-10'
source_filename: pixepi-eligibility.yml
source_heading: Eligibility
source_page: https://pixepi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pixepi\naid: pixepi\nurl: https://pixepi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or rights-infringing files\n  text: processing files that are illegal, infringe rights or violate the rights of others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pixepi/eligibility/pixepi-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Pixepi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tools
- PDF
- Image
---
