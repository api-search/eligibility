---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Ground News makes no representations that the Site, Application and Services are appropriate or available for use in other locations.
  entity_types:
  - text: YOU ARE 18 YEARS OF AGE OR OLDER/OF LEGAL AGE TO ENTER INTO AND FORM A BINDING AGREEMENT WITH GROUND NEWS
    type: individual
  minimum_age:
    text: YOU ARE 18 YEARS OF AGE OR OLDER/OF LEGAL AGE TO ENTER INTO AND FORM A BINDING AGREEMENT WITH GROUND NEWS
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Company Properties only for lawful purposes and in accordance with these Terms of Service and the Privacy Policy.
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
name: Ground
provenance_date: '2026-11-09'
provider_name: Ground
provider_slug: ground
slug: ground-eligibility
source_date: '2026-11-09'
source_filename: ground-eligibility.yml
source_heading: Eligibility
source_page: https://about.ground.news/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ground\naid: ground\nurl: https://about.ground.news/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Ground News makes no representations that the Site, Application and Services are appropriate or available\n    for use in other locations.\nentity_types:\n- type: individual\n  text: YOU ARE 18 YEARS OF AGE OR OLDER/OF LEGAL AGE TO ENTER INTO AND FORM A BINDING AGREEMENT WITH GROUND NEWS\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Company Properties only for lawful purposes and in accordance with these Terms of Service\n    and the\
  \ Privacy Policy.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU ARE 18 YEARS OF AGE OR OLDER/OF LEGAL AGE TO ENTER INTO AND FORM A BINDING AGREEMENT WITH GROUND NEWS\n"
source_yaml_url: https://artifacts.apis.io/ground/eligibility/ground-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ground's own page on 2026-11-09.
synthetic: false
tags:
- Company
- News
- Media
- Media Bias
- News Aggregation
- Journalism
- Media Monitoring
- Consumer App
---
