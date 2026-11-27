---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this agreement on behalf of a legal entity, you represent that you have the authority to bind such entity, in which case the terms "you" or "your" shall refer to such entity.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must register with us first.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Excel Price Feed
provenance_date: '2026-11-09'
provider_name: Excel Price Feed
provider_slug: excelpricefeed
slug: excelpricefeed-eligibility
source_date: '2026-11-09'
source_filename: excelpricefeed-eligibility.yml
source_heading: Eligibility
source_page: https://www.excelpricefeed.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Excel Price Feed\naid: excelpricefeed\nurl: https://www.excelpricefeed.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this agreement on behalf of a legal entity, you represent that you have the authority\n    to bind such entity, in which case the terms \"you\" or \"your\" shall refer to such entity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must register with us first.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/excelpricefeed/eligibility/excelpricefeed-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Excel Price Feed's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Excel
- Real-Time Data
---
