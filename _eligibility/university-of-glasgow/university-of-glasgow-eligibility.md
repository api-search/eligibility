---
api_specs:
- filename: university-of-glasgow-repository-api-openapi.yml
  format: yaml
  label: University of Glasgow Repository API
  slug: university-of-glasgow-repository-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-glasgow/openapi/university-of-glasgow-repository-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These terms of use set out the terms for use of the website and applies to all users of and visitors to the website ('you').
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sections restricted to certain users
    text: Sections of the website may be restricted to certain users at any time.
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
name: University of Glasgow
provenance_date: '2026-11-10'
provider_name: University of Glasgow
provider_slug: university-of-glasgow
slug: university-of-glasgow-eligibility
source_date: '2026-11-10'
source_filename: university-of-glasgow-eligibility.yml
source_heading: Eligibility
source_page: https://www.gla.ac.uk/legal/termsofuse/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: University of Glasgow\naid: university-of-glasgow\nurl: https://www.gla.ac.uk/legal/termsofuse/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: These terms of use set out the terms for use of the website and applies to all users of and visitors to\n    the website ('you').\nrestricted_uses:\n- summary: Sections restricted to certain users\n  text: Sections of the website may be restricted to certain users at any time.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/university-of-glasgow/eligibility/university-of-glasgow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from University of Glasgow's own page on 2026-11-10.
synthetic: false
tags:
- University
- Higher Education
- Education
- United Kingdom
- Scotland
- Russell Group
- Research Data
- Repository
- OAI-PMH
- Open Access
- Identity Federation
- Digital Library
---
