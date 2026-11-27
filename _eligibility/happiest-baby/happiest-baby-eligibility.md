---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Although the Website and Apps may be accessible worldwide, our Products and Services are not designed for use in all countries
  entity_types:
  - text: You represent and warrant that you are of sufficient legal age in your place of residence to use or access the Services
    type: individual
  - text: you have the right, authority, and capacity to accept and agree to these Terms on behalf of yourself or the entity you represent
    type: business
  minimum_age:
    text: You represent and warrant that you are of sufficient legal age in your place of residence to use or access the Services
    value: null
  restricted_uses:
  - summary: Personal non-commercial use only
    text: The Services are provided by HBI for your personal, non-commercial use only.
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
name: Happiest Baby
provenance_date: '2026-11-09'
provider_name: Happiest Baby
provider_slug: happiest-baby
slug: happiest-baby-eligibility
source_date: '2026-11-09'
source_filename: happiest-baby-eligibility.yml
source_heading: Eligibility
source_page: https://legal.happiestbaby.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Happiest Baby\naid: happiest-baby\nurl: https://legal.happiestbaby.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Although the Website and Apps may be accessible worldwide, our Products and Services are not designed for\n    use in all countries\nentity_types:\n- type: individual\n  text: You represent and warrant that you are of sufficient legal age in your place of residence to use or access\n    the Services\n- type: business\n  text: you have the right, authority, and capacity to accept and agree to these Terms on behalf of yourself or\n\
  \    the entity you represent\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: The Services are provided by HBI for your personal, non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent and warrant that you are of sufficient legal age in your place of residence to use or access\n    the Services\n"
source_yaml_url: https://artifacts.apis.io/happiest-baby/eligibility/happiest-baby-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Happiest Baby's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Baby
- Sleep Technology
- Smart Home
- IoT
- Health
- Hardware
---
