---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: our Platform is intended for use solely by individuals who are at least 18 years of age (or age of majority if higher in your place of residence)
    type: individual
  minimum_age:
    text: you are 18 years of age or older (or age of majority or older if higher in your place of residence)
    value: '18'
  restricted_uses:
  - summary: Commercial activity restricted
    text: engage in commercial activity except as expressly permitted under the applicable Agreements
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
name: Angel Studios
provenance_date: '2026-11-09'
provider_name: Angel Studios
provider_slug: angel-studios
slug: angel-studios-eligibility
source_date: '2026-11-09'
source_filename: angel-studios-eligibility.yml
source_heading: Eligibility
source_page: https://www.angel.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Angel Studios\naid: angel-studios\nurl: https://www.angel.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo or that has been designated\n    by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: our Platform is intended for use solely by individuals who are at least 18 years of age (or age of majority\n    if higher in your place of residence)\nrestricted_uses:\n- summary: Commercial activity restricted\n  text: engage\
  \ in commercial activity except as expressly permitted under the applicable Agreements\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are 18 years of age or older (or age of majority or older if higher in your place of residence)\n"
source_yaml_url: https://artifacts.apis.io/angel-studios/eligibility/angel-studios-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Angel Studios's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Streaming
- Media
- Community
- Faith
---
