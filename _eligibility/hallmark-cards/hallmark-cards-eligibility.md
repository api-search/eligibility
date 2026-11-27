---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Hallmark makes no representations that the Hallmark Properties or our Services are appropriate or available for use in other countries.
  entity_types:
  - text: Some features of the Hallmark Properties, including certain account‑based features, are intended for individuals who are 18 years of age or older.
    type: individual
  minimum_age:
    text: By creating an account or otherwise using the Hallmark Properties in a manner that involves the submission of personal information, you represent that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Commercial activity and sales
    text: Involves commercial activities and/or sales, such as contests, sweepstakes, or barter
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
name: Hallmark Cards
provenance_date: '2026-11-09'
provider_name: Hallmark Cards
provider_slug: hallmark-cards
slug: hallmark-cards-eligibility
source_date: '2026-11-09'
source_filename: hallmark-cards-eligibility.yml
source_heading: Eligibility
source_page: https://www.hallmark.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hallmark Cards\naid: hallmark-cards\nurl: https://www.hallmark.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Hallmark makes no representations that the Hallmark Properties or our Services are appropriate or available\n    for use in other countries.\nentity_types:\n- type: individual\n  text: Some features of the Hallmark Properties, including certain account‑based features, are intended for individuals\n    who are 18 years of age or older.\nrestricted_uses:\n- summary: Commercial activity and sales\n  text: Involves commercial activities and/or\
  \ sales, such as contests, sweepstakes, or barter\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By creating an account or otherwise using the Hallmark Properties in a manner that involves the submission\n    of personal information, you represent that you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/hallmark-cards/eligibility/hallmark-cards-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Hallmark Cards's own page on 2026-11-09.
synthetic: false
tags:
- Greeting Cards
- Gifts
- Retail
- Consumer Goods
- Stationery
- Gift Wrap
- Media
- Business Greetings
- Fortune 1000
---
