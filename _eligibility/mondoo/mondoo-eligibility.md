---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (a) you are not located in, or a resident or a national of, a restricted country
  entity_types:
  - text: the individual (“You”) accessing the Mondoo services described
    type: individual
  - text: Where an individual accesses or uses the Service on behalf of a business, such individual represents and warrants having the power and authority to access and use the Service and to bind the business to these Terms
    type: business
  - text: if You are a U.S. Government agency or instrumentality or if You are providing all or any part of the Service or any derivatives thereof to the U.S. Government
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export-controlled and prohibited end uses
    text: use the Service in any restricted countries or for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, missile or biological weapons related end uses
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
name: Mondoo
provenance_date: '2026-11-10'
provider_name: Mondoo
provider_slug: mondoo
slug: mondoo-eligibility
source_date: '2026-11-10'
source_filename: mondoo-eligibility.yml
source_heading: Eligibility
source_page: https://mondoo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mondoo\naid: mondoo\nurl: https://mondoo.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (a) you are not located in, or a resident or a national of, a restricted\n    country\nentity_types:\n- type: individual\n  text: the individual (“You”) accessing the Mondoo services described\n- type: business\n  text: Where an individual accesses or uses the Service on behalf of a business, such individual represents and\n    warrants having the power and authority to access and use the Service and to bind the business to these Terms\n- type: government\n\
  \  text: if You are a U.S. Government agency or instrumentality or if You are providing all or any part of the Service\n    or any derivatives thereof to the U.S. Government\nrestricted_uses:\n- summary: Export-controlled and prohibited end uses\n  text: use the Service in any restricted countries or for any purposes prohibited by the Export Laws, including,\n    but not limited to, nuclear, chemical, missile or biological weapons related end uses\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mondoo/eligibility/mondoo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Mondoo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cybersecurity
- Security
- Vulnerability Management
- Compliance
- Cloud Security
- Policy as Code
- DevSecOps
- GraphQL
- SAST
---
