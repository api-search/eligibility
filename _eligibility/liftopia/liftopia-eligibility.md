---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are not a resident of the United States, please note that the personal information you submit to the Site will be transferred to the United States and processed by Liftopia in order to provide its services to you.
  entity_types:
  - text: You represent that you are of sufficient legal age to create binding legal obligations for any liability you may incur as a result of your use of this Site.
    type: individual
  minimum_age:
    text: You represent that you are of sufficient legal age to create binding legal obligations for any liability you may incur as a result of your use of this Site.
    value: null
  restricted_uses:
  - summary: No automated access
    text: You may not use any automated means to access this Site, unless specifically permitted by Liftopia.
  - summary: No fraudulent purchases
    text: shall not use this Site to make any speculative, false or fraudulent Purchases
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
name: Liftopia
provenance_date: '2026-11-09'
provider_name: Liftopia
provider_slug: liftopia
slug: liftopia-eligibility
source_date: '2026-11-09'
source_filename: liftopia-eligibility.yml
source_heading: Eligibility
source_page: https://www.liftopia.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Liftopia\naid: liftopia\nurl: https://www.liftopia.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are not a resident of the United States, please note that the personal information you submit to\n    the Site will be transferred to the United States and processed by Liftopia in order to provide its services\n    to you.\nentity_types:\n- type: individual\n  text: You represent that you are of sufficient legal age to create binding legal obligations for any liability\n    you may incur as a result of your use of this Site.\nrestricted_uses:\n- summary: No\
  \ automated access\n  text: You may not use any automated means to access this Site, unless specifically permitted by Liftopia.\n- summary: No fraudulent purchases\n  text: shall not use this Site to make any speculative, false or fraudulent Purchases\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent that you are of sufficient legal age to create binding legal obligations for any liability\n    you may incur as a result of your use of this Site.\n"
source_yaml_url: https://artifacts.apis.io/liftopia/eligibility/liftopia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Liftopia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- E-Commerce
- Marketplace
- Ticketing
- Skiing
- Reservations
- Recreation
---
