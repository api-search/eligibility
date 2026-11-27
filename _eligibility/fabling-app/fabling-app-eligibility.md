---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be old enough to have a Google account and to agree to these terms.
    type: individual
  minimum_age:
    text: Fabling is not directed at children under 13.
    value: null
  restricted_uses:
  - summary: Illegal content or passing off as human-written professional work
    text: use Fabling to generate content that is illegal or that you intend to pass off as human-written professional work
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
name: Fabling
provenance_date: '2026-11-09'
provider_name: Fabling
provider_slug: fabling-app
slug: fabling-app-eligibility
source_date: '2026-11-09'
source_filename: fabling-app-eligibility.yml
source_heading: Eligibility
source_page: https://fabling.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fabling\naid: fabling-app\nurl: https://fabling.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be old enough to have a Google account and to agree to these terms.\nrestricted_uses:\n- summary: Illegal content or passing off as human-written professional work\n  text: use Fabling to generate content that is illegal or that you intend to pass off as human-written professional\n    work\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Fabling is\
  \ not directed at children under 13.\n"
source_yaml_url: https://artifacts.apis.io/fabling-app/eligibility/fabling-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fabling's own page on 2026-11-09.
synthetic: false
tags:
- Language Learning
- Education
- Artificial Intelligence
- Personalized
- Stories
---
