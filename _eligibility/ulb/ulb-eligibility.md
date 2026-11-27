---
api_specs:
- filename: ulb-group-api-openapi.yml
  format: yaml
  label: Université libre de Bruxelles Group API
  slug: ulb-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ulb/openapi/ulb-group-api-openapi.yml
- filename: ulb-oai-pmh-api-openapi.yml
  format: yaml
  label: Université libre de Bruxelles OAI PMH API
  slug: ulb-oai-pmh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ulb/openapi/ulb-oai-pmh-api-openapi.yml
- filename: ulb-scholar-api-openapi.yml
  format: yaml
  label: Université libre de Bruxelles Scholar API
  slug: ulb-scholar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ulb/openapi/ulb-scholar-api-openapi.yml
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
  - summary: Non-profit purpose for harvesting and teaching/research use
    text: for a non-profit purpose, harvest the metadata
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
name: Université libre de Bruxelles
provenance_date: '2026-11-10'
provider_name: Université libre de Bruxelles
provider_slug: ulb
slug: ulb-eligibility
source_date: '2026-11-10'
source_filename: ulb-eligibility.yml
source_heading: Eligibility
source_page: https://bib.ulb.be/en/find-documents/di-fusion/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Université libre de Bruxelles\naid: ulb\nurl: https://bib.ulb.be/en/find-documents/di-fusion/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-profit purpose for harvesting and teaching/research use\n  text: for a non-profit purpose, harvest the metadata\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ulb/eligibility/ulb-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Université libre de Bruxelles's own page on 2026-11-10.
synthetic: false
tags:
- University
- Higher Education
- Education
- Belgium
- Europe
- Research
- Research Data
- Institutional Repository
- Open Access
- Identity Federation
- OAI-PMH
- Library
---
