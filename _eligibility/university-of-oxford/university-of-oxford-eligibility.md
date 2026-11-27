---
api_specs:
- filename: university-of-oxford-iiif-api-openapi.yml
  format: yaml
  label: University of Oxford IIIF API
  slug: university-of-oxford-iiif-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-oxford/openapi/university-of-oxford-iiif-api-openapi.yml
- filename: university-of-oxford-repository-api-openapi.yml
  format: yaml
  label: University of Oxford Repository API
  slug: university-of-oxford-repository-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-oxford/openapi/university-of-oxford-repository-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms that may apply to our site or any content on it.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial or business purposes
    text: We only provide our site for research and private use. You agree not to use our site for any commercial or business purposes
  - source: https://ora.ox.ac.uk/terms_of_use
    summary: Non-commercial use only unless item licence permits otherwise
    text: Subject to such licences, users may not use material obtained from ORA for any profit-making activities or any commercial gain.
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
name: University of Oxford
provenance_date: '2026-11-10'
provider_name: University of Oxford
provider_slug: university-of-oxford
slug: university-of-oxford-eligibility
source_date: '2026-11-10'
source_filename: university-of-oxford-eligibility.yml
source_heading: Eligibility
source_page: https://digital.bodleian.ox.ac.uk/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: University of Oxford\naid: university-of-oxford\nurl: https://digital.bodleian.ox.ac.uk/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://digital.bodleian.ox.ac.uk/terms/\n  - https://ora.ox.ac.uk/terms_of_use\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms\n    that may apply to our site or any content on it.'\nrestricted_uses:\n- summary: Commercial or business purposes\n  text: We only provide our site for research and private use. You agree not\
  \ to use our site for any commercial\n    or business purposes\n- summary: Non-commercial use only unless item licence permits otherwise\n  text: Subject to such licences, users may not use material obtained from ORA for any profit-making activities\n    or any commercial gain.\n  source: https://ora.ox.ac.uk/terms_of_use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/university-of-oxford/eligibility/university-of-oxford-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from University of Oxford's own page on 2026-11-10.
synthetic: false
tags:
- University
- Higher Education
- Education
- Research
- United Kingdom
- Russell Group
- Research Repository
- Library
- Digital Collections
- IIIF
- OAI-PMH
- Identity Federation
- Open Access
- Research Computing
---
