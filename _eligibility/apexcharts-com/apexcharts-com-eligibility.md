---
api_specs:
- filename: apexcharts-com-openapi-generated.yml
  format: yaml
  label: ApexCharts API
  slug: apexcharts-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexcharts-com/openapi/_ae-authored/apexcharts-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Free to use for individuals
    type: individual
  - text: Commercial License For you, your parent company, affiliates, or any entity under common control with annual revenue, operating budget, funding, or equivalent financial resources of USD $2,000,000 or more .
    type: business
  - text: Any Software which is downloaded from this Server for or on behalf of the United States of America, its agencies and/or instrumentalities ("U.S. Government"), is provided with Restricted Rights.
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use in violation of law
    text: Use the Software in any way that violates applicable law or regulation .
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
name: ApexCharts
provenance_date: '2026-11-09'
provider_name: ApexCharts
provider_slug: apexcharts-com
slug: apexcharts-com-eligibility
source_date: '2026-11-09'
source_filename: apexcharts-com-eligibility.yml
source_heading: Eligibility
source_page: https://apexcharts.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ApexCharts\naid: apexcharts-com\nurl: https://apexcharts.com/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Free to use for individuals\n- type: business\n  text: Commercial License For you, your parent company, affiliates, or any entity under common control with annual\n    revenue, operating budget, funding, or equivalent financial resources of USD $2,000,000 or more .\n- type: government\n  text: Any Software which is downloaded from this Server for or on behalf of the United States of America, its\n    agencies and/or\
  \ instrumentalities (\"U.S. Government\"), is provided with Restricted Rights.\nrestricted_uses:\n- summary: Use in violation of law\n  text: Use the Software in any way that violates applicable law or regulation .\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apexcharts-com/eligibility/apexcharts-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from ApexCharts's own page on 2026-11-09.
synthetic: false
tags:
- JavaScript
- Charts
- Data Visualization
- Open Source
- Library
---
