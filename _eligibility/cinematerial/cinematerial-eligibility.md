---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This site is for non-profit/educational use only.
    type: nonprofit
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use of images
    text: All images on CineMaterial.com are intended for non-commercial entertainment and education use only
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
name: CineMaterial
provenance_date: '2026-11-09'
provider_name: CineMaterial
provider_slug: cinematerial
slug: cinematerial-eligibility
source_date: '2026-11-09'
source_filename: cinematerial-eligibility.yml
source_heading: Eligibility
source_page: https://www.cinematerial.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CineMaterial\naid: cinematerial\nurl: https://www.cinematerial.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: nonprofit\n  text: This site is for non-profit/educational use only.\nrestricted_uses:\n- summary: Commercial use of images\n  text: All images on CineMaterial.com are intended for non-commercial entertainment and education use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cinematerial/eligibility/cinematerial-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CineMaterial's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Media
- Archives
- Movies
- Community
---
