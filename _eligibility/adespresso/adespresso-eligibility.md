---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: OUR SERVICES ARE NOT FOR CONSUMERS OR PRIVATE OR HOUSEHOLD PURPOSES, ONLY FOR BUSINESSES AND PROFESSIONAL USERS.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sensitive personal information processing
    text: our Services shall not be used to process any sensitive personal information as defined in the Data Protection Directive 95/46.
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
name: AdEspresso
provenance_date: '2026-11-09'
provider_name: AdEspresso
provider_slug: adespresso
slug: adespresso-eligibility
source_date: '2026-11-09'
source_filename: adespresso-eligibility.yml
source_heading: Eligibility
source_page: https://adespresso.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdEspresso\naid: adespresso\nurl: https://adespresso.com/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: OUR SERVICES ARE NOT FOR CONSUMERS OR PRIVATE OR HOUSEHOLD PURPOSES, ONLY FOR BUSINESSES AND PROFESSIONAL\n    USERS.\nrestricted_uses:\n- summary: No sensitive personal information processing\n  text: our Services shall not be used to process any sensitive personal information as defined in the Data Protection\n    Directive 95/46.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adespresso/eligibility/adespresso-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from AdEspresso's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- Facebook Ads
- Instagram Ads
- Social Media Marketing
- Ad Optimization
- Software-as-a-Service
- Marketing
---
