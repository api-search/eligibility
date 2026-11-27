---
api_specs:
- filename: lse-lti-api-openapi.yml
  format: yaml
  label: London School of Economics and Political Science LTI API
  slug: lse-lti-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lse/openapi/lse-lti-api-openapi.yml
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
  - summary: no misuse or unauthorised access
    text: You must not attempt to gain unauthorised access to the Website, the server on which the Website is stored or any server, computer or database connected to the Website.
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
name: London School of Economics and Political Science
provenance_date: '2026-11-09'
provider_name: London School of Economics and Political Science
provider_slug: lse
slug: lse-eligibility
source_date: '2026-11-09'
source_filename: lse-eligibility.yml
source_heading: Eligibility
source_page: https://www.lse.ac.uk/lse-information/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: London School of Economics and Political Science\naid: lse\nurl: https://www.lse.ac.uk/lse-information/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: no misuse or unauthorised access\n  text: You must not attempt to gain unauthorised access to the Website, the server on which the Website is stored\n    or any server, computer or database connected to the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lse/eligibility/lse-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from London School of Economics and Political Science's own page on 2026-11-09.
synthetic: false
tags:
- University
- Higher Education
- Education
- United Kingdom
- Russell Group
- Social Sciences
- Identity Federation
- LMS
- Research Repository
- Library
- Open Research
- OAI-PMH
- SAML
- LTI
- IIIF
---
