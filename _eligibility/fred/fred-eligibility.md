---
api_specs:
- filename: fred-categories-api-openapi.yml
  format: yaml
  label: FRED Categories API
  slug: fred-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-categories-api-openapi.yml
- filename: fred-observations-api-openapi.yml
  format: yaml
  label: FRED Observations API
  slug: fred-observations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-observations-api-openapi.yml
- filename: fred-regional-data-api-openapi.yml
  format: yaml
  label: FRED Regional Data API
  slug: fred-regional-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-regional-data-api-openapi.yml
- filename: fred-releases-api-openapi.yml
  format: yaml
  label: FRED Releases API
  slug: fred-releases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-releases-api-openapi.yml
- filename: fred-series-api-openapi.yml
  format: yaml
  label: FRED Series API
  slug: fred-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-series-api-openapi.yml
- filename: fred-series-data-api-openapi.yml
  format: yaml
  label: FRED Series Data API
  slug: fred-series-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-series-data-api-openapi.yml
- filename: fred-series-group-api-openapi.yml
  format: yaml
  label: FRED Series Group API
  slug: fred-series-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-series-group-api-openapi.yml
- filename: fred-shapes-api-openapi.yml
  format: yaml
  label: FRED Shapes API
  slug: fred-shapes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-shapes-api-openapi.yml
- filename: fred-sources-api-openapi.yml
  format: yaml
  label: FRED Sources API
  slug: fred-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-sources-api-openapi.yml
- filename: fred-tags-api-openapi.yml
  format: yaml
  label: FRED Tags API
  slug: fred-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-tags-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: In any event, you represent and warrant that you are over thirteen (13) years of age.
    type: individual
  minimum_age:
    text: In any event, you represent and warrant that you are over thirteen (13) years of age.
    value: '13'
  restricted_uses:
  - summary: Commercial use requires consent
    text: Except as expressly authorized in the FRED® Terms of Service, use the FRED® Services for any commercial use without the prior written consent of the Bank.
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
name: FRED
provenance_date: '2026-11-09'
provider_name: FRED
provider_slug: fred
slug: fred-eligibility
source_date: '2026-11-09'
source_filename: fred-eligibility.yml
source_heading: Eligibility
source_page: https://fred.stlouisfed.org/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FRED\naid: fred\nurl: https://fred.stlouisfed.org/legal/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: In any event, you represent and warrant that you are over thirteen (13) years of age.\nrestricted_uses:\n- summary: Commercial use requires consent\n  text: Except as expressly authorized in the FRED® Terms of Service, use the FRED® Services for any commercial\n    use without the prior written consent of the Bank.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: In any event, you represent and warrant that you are over thirteen (13) years of age.\n"
source_yaml_url: https://artifacts.apis.io/fred/eligibility/fred-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from FRED's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Government
- Economic Data
- Federal Reserve
- Time Series
- Open Data
- Public APIs
- Government Data
---
