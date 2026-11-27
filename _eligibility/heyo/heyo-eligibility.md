---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Availability of heyo.com does not mean that every integration or feature is available in every country.
  minimum_age:
    text: You must be at least 18 years old and legally able to enter this agreement.
    value: '18'
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
name: Heyo
provenance_date: '2026-11-09'
provider_name: Heyo
provider_slug: heyo
slug: heyo-eligibility
source_date: '2026-11-09'
source_filename: heyo-eligibility.yml
source_heading: Eligibility
source_page: https://www.heyo.com:443/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Heyo\naid: heyo\nurl: https://www.heyo.com:443/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Availability of heyo.com does not mean that every integration or feature is available in every country.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter this agreement.\n"
source_yaml_url: https://artifacts.apis.io/heyo/eligibility/heyo-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Heyo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketing
- Social Media
- Promotions
- Contests
- Sweepstakes
- Giveaways
- Lead Generation
- Email Marketing
- Campaigns
---
