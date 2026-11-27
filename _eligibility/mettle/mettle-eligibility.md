---
api_specs:
- filename: mettle-atm-api-openapi.yml
  format: yaml
  label: Mettle ATM API
  slug: mettle-atm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mettle/openapi/mettle-atm-api-openapi.yml
- filename: mettle-bca-api-openapi.yml
  format: yaml
  label: Mettle BCA API
  slug: mettle-bca-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mettle/openapi/mettle-bca-api-openapi.yml
- filename: mettle-branch-api-openapi.yml
  format: yaml
  label: Mettle Branch API
  slug: mettle-branch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mettle/openapi/mettle-branch-api-openapi.yml
- filename: mettle-ccc-api-openapi.yml
  format: yaml
  label: Mettle CCC API
  slug: mettle-ccc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mettle/openapi/mettle-ccc-api-openapi.yml
- filename: mettle-pca-api-openapi.yml
  format: yaml
  label: Mettle PCA API
  slug: mettle-pca-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mettle/openapi/mettle-pca-api-openapi.yml
- filename: mettle-sme-api-openapi.yml
  format: yaml
  label: Mettle SME API
  slug: mettle-sme-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mettle/openapi/mettle-sme-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: the services and products on this website are intended for use by residents of the United Kingdom only, and are not aimed at or intended for use by residents of any other jurisdiction
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Australian residents
    text: Persons accessing this website from Australia should note that their access to, and use of, the information, services and products on this website may be prohibited under the Australian Corporations Act 2001
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
name: Mettle
provenance_date: '2026-11-10'
provider_name: Mettle
provider_slug: mettle
slug: mettle-eligibility
source_date: '2026-11-10'
source_filename: mettle-eligibility.yml
source_heading: Eligibility
source_page: https://www.mettle.co.uk/docs/terms-and-conditions/1.5.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mettle\naid: mettle\nurl: https://www.mettle.co.uk/docs/terms-and-conditions/1.5.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: the services and products on this website are intended for use by residents of the United Kingdom only,\n    and are not aimed at or intended for use by residents of any other jurisdiction\nentity_types: []\nrestricted_uses:\n- summary: Australian residents\n  text: Persons accessing this website from Australia should note that their access to, and use of, the information,\n    services and products on this website may be prohibited under the Australian\
  \ Corporations Act 2001\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mettle/eligibility/mettle-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Mettle's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- Business Banking
- Open Banking
- PSD2
- OBIE
- FAPI
- United Kingdom
- Payments
- Account Information
- Challenger Bank
- Fintech
---
