---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accessing the Website you are accepting these terms on you behalf and on behalf of the entity you represent, if any.
    type: business
  minimum_age:
    text: Our Website is not intended for use by children under the age of 13, and children under the age of 13 are not eligible to participate in any Projects.
    value: '13'
  restricted_uses:
  - summary: Direct competitors and benchmarking
    text: You may not access our website or be a member of our community if you are our direct competitor, except with our prior written consent.
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
name: Tongal
provenance_date: '2026-11-10'
provider_name: Tongal
provider_slug: tongal
slug: tongal-eligibility
source_date: '2026-11-10'
source_filename: tongal-eligibility.yml
source_heading: Eligibility
source_page: https://tongal.com/about/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tongal\naid: tongal\nurl: https://tongal.com/about/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By accessing the Website you are accepting these terms on you behalf and on behalf of the entity you represent,\n    if any.\nrestricted_uses:\n- summary: Direct competitors and benchmarking\n  text: You may not access our website or be a member of our community if you are our direct competitor, except\n    with our prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: Our Website is not intended for use by children under the age of 13, and children under the age of 13 are\n    not eligible to participate in any Projects.\n"
source_yaml_url: https://artifacts.apis.io/tongal/eligibility/tongal-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Tongal's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Video
- Creative
- Crowdsourcing
- Content Production
- Marketing
---
