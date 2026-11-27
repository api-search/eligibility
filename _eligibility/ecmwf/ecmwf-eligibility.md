---
api_specs:
- filename: ecmwf-data-stores-processing-openapi.yml
  format: yaml
  label: ECMWF Data Stores Processing API
  slug: ecmwf-data-stores-processing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecmwf/openapi/ecmwf-data-stores-processing-openapi.yml
- filename: ecmwf-data-stores-catalogue-openapi.yml
  format: yaml
  label: ECMWF Data Stores STAC Catalogue API
  slug: ecmwf-data-stores-stac-catalogue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecmwf/openapi/ecmwf-data-stores-catalogue-openapi.yml
- filename: ecmwf-data-stores-profiles-openapi.yml
  format: yaml
  label: ECMWF Data Stores Profile API
  slug: ecmwf-data-stores-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecmwf/openapi/ecmwf-data-stores-profiles-openapi.yml
claim_count: 3
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
  - summary: Non-commercial forums
    text: Forums are for non-commercial use only.
  - summary: Protected content
    text: That content, which is only accessible via an ECMWF user-id, must be used in accordance with the relevant terms, previously agreed between ECMWF and the organisation, for which the user is a representative.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: ECMWF user-ids are not available to members of the public.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ECMWF
provenance_date: '2026-11-09'
provider_name: ECMWF
provider_slug: ecmwf
slug: ecmwf-eligibility
source_date: '2026-11-09'
source_filename: ecmwf-eligibility.yml
source_heading: Eligibility
source_page: https://www.ecmwf.int/en/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ECMWF\naid: ecmwf\nurl: https://www.ecmwf.int/en/terms-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial forums\n  text: Forums are for non-commercial use only.\n- summary: Protected content\n  text: That content, which is only accessible via an ECMWF user-id, must be used in accordance with the relevant\n    terms, previously agreed between ECMWF and the organisation, for which the user is a representative.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: ECMWF user-ids are not available\
  \ to members of the public.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ecmwf/eligibility/ecmwf-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from ECMWF's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Weather
- Meteorology
- Forecasting
- Climate
- Open Data
- Research
- Intergovernmental
---
