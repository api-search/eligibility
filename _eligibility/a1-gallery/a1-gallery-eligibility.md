---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An account is for one person.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Abuse or unlawful use
    text: Don’t try to break it, hammer the API past its limits, or use it for anything unlawful.
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
name: A1 Gallery
provenance_date: '2026-11-09'
provider_name: A1 Gallery
provider_slug: a1-gallery
slug: a1-gallery-eligibility
source_date: '2026-11-09'
source_filename: a1-gallery-eligibility.yml
source_heading: Eligibility
source_page: https://www.a1.gallery/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: A1 Gallery\naid: a1-gallery\nurl: https://www.a1.gallery/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An account is for one person.\nrestricted_uses:\n- summary: Abuse or unlawful use\n  text: Don’t try to break it, hammer the API past its limits, or use it for anything unlawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/a1-gallery/eligibility/a1-gallery-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from A1 Gallery's own page on 2026-11-09.
synthetic: false
tags:
- Design
- Gallery
- Web
- Creative
---
