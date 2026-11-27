---
api_specs:
- filename: lancaster-oai2-api-openapi.yml
  format: yaml
  label: Lancaster EPrints OAI-PMH 2.0 Interface
  slug: lancaster-oai2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lancaster/openapi/lancaster-oai2-api-openapi.yml
- filename: lancaster-idp-api-openapi.yml
  format: yaml
  label: Lancaster University Idp API
  slug: lancaster-idp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lancaster/openapi/lancaster-idp-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Applicants and new and continuing students should familiarise themselves with these documents, particularly those that are most likely to be relevant to them and their studies.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Lancaster University
provenance_date: '2026-11-09'
provider_name: Lancaster University
provider_slug: lancaster
slug: lancaster-eligibility
source_date: '2026-11-09'
source_filename: lancaster-eligibility.yml
source_heading: Eligibility
source_page: https://www.lancaster.ac.uk/study/important-information/terms-and-conditions-for-students/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lancaster University\naid: lancaster\nurl: https://www.lancaster.ac.uk/study/important-information/terms-and-conditions-for-students/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Applicants and new and continuing students should familiarise themselves with these documents, particularly\n    those that are most likely to be relevant to them and their studies.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lancaster/eligibility/lancaster-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Lancaster University's own page on 2026-11-09.
synthetic: false
tags:
- University
- Higher Education
- Education
- United Kingdom
- N8 Research Partnership
- Research Data
- Institutional Repository
- Identity Federation
- Library
- Open Source
---
