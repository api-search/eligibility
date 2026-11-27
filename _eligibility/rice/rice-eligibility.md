---
api_specs:
- filename: rice-datasets-api-openapi.yml
  format: yaml
  label: Rice University Datasets API
  slug: rice-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rice/openapi/rice-datasets-api-openapi.yml
- filename: rice-reference-api-openapi.yml
  format: yaml
  label: Rice University Reference API
  slug: rice-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rice/openapi/rice-reference-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This policy applies to all faculty, staff, students, and other individuals working on behalf of Rice University
    type: other
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
name: Rice University
provenance_date: '2026-11-10'
provider_name: Rice University
provider_slug: rice
slug: rice-eligibility
source_date: '2026-11-10'
source_filename: rice-eligibility.yml
source_heading: Eligibility
source_page: https://policy.rice.edu/808
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rice University\naid: rice\nurl: https://policy.rice.edu/808\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: This policy applies to all faculty, staff, students, and other individuals working on behalf of Rice University\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rice/eligibility/rice-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Rice University's own page on 2026-11-10.
synthetic: false
tags:
- University
- Higher Education
- Education
- United States
- Texas
- Private Research University
- Association of American Universities
- Research Data
- Open Data
- Research Repository
- Course Catalog
- Identity Federation
- Library
- Urban Research
---
