---
api_specs:
- filename: australian-bureau-of-statistics-get-data-api-openapi.yml
  format: yaml
  label: Australian Bureau of Statistics Get Data API
  slug: australian-bureau-of-statistics-get-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/australian-bureau-of-statistics/openapi/australian-bureau-of-statistics-get-data-api-openapi.yml
- filename: australian-bureau-of-statistics-get-metadata-api-openapi.yml
  format: yaml
  label: Australian Bureau of Statistics Get Metadata API
  slug: australian-bureau-of-statistics-get-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/australian-bureau-of-statistics/openapi/australian-bureau-of-statistics-get-metadata-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are an individual accepting these Terms of Use on behalf of an organisation, You warrant and represent to the ABS that You are properly authorised
    type: individual
  - text: the person or organisation using the API ('You')
    type: business
  - text: If You are a non-corporate Commonwealth entity (as defined by the Public Governance, Performance and Accountability Act 2013 (Cth) the ABS acknowledge these Terms of Use are not legally enforceable
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal activity
    text: use the facilities and capabilities of the API or ABS’ IT systems or resources to conduct any illegal activity or solicit the performance of any illegal activity
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The ABS will facilitate access by You of the API through provision of an API Key.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Australian Bureau of Statistics
provenance_date: '2026-11-09'
provider_name: Australian Bureau of Statistics
provider_slug: australian-bureau-of-statistics
slug: australian-bureau-of-statistics-eligibility
source_date: '2026-11-09'
source_filename: australian-bureau-of-statistics-eligibility.yml
source_heading: Eligibility
source_page: https://www.abs.gov.au/about/data-services/application-programming-interfaces-apis/indicator-api/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Australian Bureau of Statistics\naid: australian-bureau-of-statistics\nurl: https://www.abs.gov.au/about/data-services/application-programming-interfaces-apis/indicator-api/terms-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If You are an individual accepting these Terms of Use on behalf of an organisation, You warrant and represent\n    to the ABS that You are properly authorised\n- type: business\n  text: the person or organisation using the API ('You')\n- type: government\n  text: If You are a non-corporate Commonwealth entity\
  \ (as defined by the Public Governance, Performance and Accountability\n    Act 2013 (Cth) the ABS acknowledge these Terms of Use are not legally enforceable\nrestricted_uses:\n- summary: Illegal activity\n  text: use the facilities and capabilities of the API or ABS’ IT systems or resources to conduct any illegal activity\n    or solicit the performance of any illegal activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The ABS will facilitate access by You of the API through provision of an API Key.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/australian-bureau-of-statistics/eligibility/australian-bureau-of-statistics-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Australian Bureau of Statistics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Government
- Statistics
- Open Data
- SDMX
- Census
- Economic Indicators
- Australia
---
