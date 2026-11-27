---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company makes no representation that the Sites is appropriate or available in other locations other than where it is operated by Company.
  entity_types:
  - text: API.market is a professional business-to-business (B2B) marketplace designed exclusively for commercial and professional use.
    type: business
  minimum_age:
    text: The Sites is intended for users who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No NSFW or minors data
    text: Process, transmit, or store any content that is illegal, harmful, threatening, abusive, harassing, tortious, defamatory, vulgar, obscene, pornographic, or sexually explicit
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: During the sign-up process, API.market requires verification of your email address through a one-time password (OTP) sent to your provided email.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: API.market
provenance_date: '2026-11-09'
provider_name: API.market
provider_slug: api-market
slug: api-market-eligibility
source_date: '2026-11-09'
source_filename: api-market-eligibility.yml
source_heading: Eligibility
source_page: https://api.market/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: API.market\naid: api-market\nurl: https://api.market/terms_of_service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Company makes no representation that the Sites is appropriate or available in other locations other than\n    where it is operated by Company.\nentity_types:\n- type: business\n  text: API.market is a professional business-to-business (B2B) marketplace designed exclusively for commercial\n    and professional use.\nrestricted_uses:\n- summary: No NSFW or minors data\n  text: Process, transmit, or store any content that is illegal, harmful, threatening, abusive, harassing,\
  \ tortious,\n    defamatory, vulgar, obscene, pornographic, or sexually explicit\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: During the sign-up process, API.market requires verification of your email address through a one-time password\n    (OTP) sent to your provided email.\nminimum_age:\n  value: '18'\n  text: The Sites is intended for users who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/api-market/eligibility/api-market-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from API.market's own page on 2026-11-09.
synthetic: false
tags:
- API Marketplace
- MCP
- AI Agents
- API Monetization
- Subscription
- Usage Metering
- OAuth
- Authentication
---
