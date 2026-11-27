---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: This Site is intended solely for users who are thirteen (13) years of age or older.
    value: '13'
  restricted_uses:
  - summary: Users under 13
    text: Any registration by, use of or access to the Site by anyone who is under 13 is unauthorized, unlicensed and in violation of these Terms of Use.
  - summary: Registering accounts for others
    text: register for a User account on behalf of an individual other than yourself, or register for a User account on behalf of any group or entity
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
name: Bloomboard
provenance_date: '2026-11-09'
provider_name: Bloomboard
provider_slug: bloomboard
slug: bloomboard-eligibility
source_date: '2026-11-09'
source_filename: bloomboard-eligibility.yml
source_heading: Eligibility
source_page: https://bloomboard.com/terms/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloomboard\naid: bloomboard\nurl: https://bloomboard.com/terms/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Users under 13\n  text: Any registration by, use of or access to the Site by anyone who is under 13 is unauthorized, unlicensed\n    and in violation of these Terms of Use.\n- summary: Registering accounts for others\n  text: register for a User account on behalf of an individual other than yourself, or register for a User account\n    on behalf of any group or entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '13'\n  text: This Site is intended solely for users who are thirteen (13) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/bloomboard/eligibility/bloomboard-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bloomboard's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Talent Development
- K-12
- Higher Education
- Workforce
---
