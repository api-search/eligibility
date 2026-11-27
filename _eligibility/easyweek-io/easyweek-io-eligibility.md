---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Where the Customer is a business or self-employed person acting in trade (sole traders, freelancers registered as businesses, companies, partnerships, associations, public bodies), Fees paid are non-refundable except as expressly stated in these Terms or in an Order Form.
    type: business
  minimum_age:
    text: null
    value: null
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
name: easyweek-io
provenance_date: '2026-11-09'
provider_name: easyweek-io
provider_slug: easyweek-io
slug: easyweek-io-eligibility
source_date: '2026-11-09'
source_filename: easyweek-io-eligibility.yml
source_heading: Eligibility
source_page: https://easyweek.io/business/terms-and-policies
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: easyweek-io\naid: easyweek-io\nurl: https://easyweek.io/business/terms-and-policies\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Where the Customer is a business or self-employed person acting in trade (sole traders, freelancers registered\n    as businesses, companies, partnerships, associations, public bodies), Fees paid are non-refundable except as\n    expressly stated in these Terms or in an Order Form.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/easyweek-io/eligibility/easyweek-io-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from easyweek-io's own page on 2026-11-09.
synthetic: false
tags:
- Marketplace
- Booking
- Services
- US
- Consumer
---
