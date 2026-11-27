---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access from territories where its contents are illegal is prohibited.
  entity_types:
  - text: If you are using or opening an account on the Service on behalf of a company, entity, or organization (a 'Subscribing Organization'), then you represent and warrant that you are an authorized representative of that Subscribing Organization
    type: business
  minimum_age:
    text: The Service is not available to persons under the age of 13
    value: '13'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: you will not use the Service for any purpose that is unlawful or prohibited by the Terms.
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
name: 1World Online
provenance_date: '2026-11-09'
provider_name: 1World Online
provider_slug: 1worldonline
slug: 1worldonline-eligibility
source_date: '2026-11-09'
source_filename: 1worldonline-eligibility.yml
source_heading: Eligibility
source_page: https://welcome.1worldonline.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 1World Online\naid: 1worldonline\nurl: https://welcome.1worldonline.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access from territories where its contents are illegal is prohibited.\nentity_types:\n- type: business\n  text: If you are using or opening an account on the Service on behalf of a company, entity, or organization (a\n    'Subscribing Organization'), then you represent and warrant that you are an authorized representative of that\n    Subscribing Organization\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: you will not use the Service for\
  \ any purpose that is unlawful or prohibited by the Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Service is not available to persons under the age of 13\n"
source_yaml_url: https://artifacts.apis.io/1worldonline/eligibility/1worldonline-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from 1World Online's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Audience Engagement
- Polls
- Surveys
- Quizzes
- Loyalty
- Media
- Publishing
- Widgets
- Web3
---
