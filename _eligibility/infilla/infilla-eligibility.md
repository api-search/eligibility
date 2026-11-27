---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are at least the age of majority in your jurisdiction or otherwise legally able to enter into a binding agreement.
    type: individual
  - text: provides government technology solutions to cities, counties, and other public entities
    type: government
  minimum_age:
    text: You represent that you are at least the age of majority in your jurisdiction or otherwise legally able to enter into a binding agreement.
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited conduct
    text: use the Services for any unlawful, fraudulent, deceptive, or harmful purpose
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
name: Infilla
provenance_date: '2026-11-09'
provider_name: Infilla
provider_slug: infilla
slug: infilla-eligibility
source_date: '2026-11-09'
source_filename: infilla-eligibility.yml
source_heading: Eligibility
source_page: https://www.infilla.com/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Infilla\naid: infilla\nurl: https://www.infilla.com/termsofuse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are at least the age of majority in your jurisdiction or otherwise legally able to\n    enter into a binding agreement.\n- type: government\n  text: provides government technology solutions to cities, counties, and other public entities\nrestricted_uses:\n- summary: Unlawful or prohibited conduct\n  text: use the Services for any unlawful, fraudulent, deceptive, or harmful purpose\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent that you are at least the age of majority in your jurisdiction or otherwise legally able to\n    enter into a binding agreement.\n"
source_yaml_url: https://artifacts.apis.io/infilla/eligibility/infilla-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Infilla's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Government
- GovTech
- Permitting
- Housing
- Urban Planning
- Municipal Software
- Civic Technology
---
