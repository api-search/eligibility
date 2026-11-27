---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is available only to individuals who are at least 18 years old, who are acting for themselves
    type: individual
  - text: or in their capacity as an employee or representative of a business entity or other organization (in which case you represent and warrant that you are authorized to agree to the Terms of Use on behalf of yourself and such entity or organization)
    type: business
  minimum_age:
    text: The Service is available only to individuals who are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Abusive or unlawful content
    text: Customer shall not, directly or indirectly, send, submit, post, receive or otherwise facilitate, or in any way use, or permit to be used, the Yuhu Solution to send, submit, post, receive or otherwise facilitate the transmission of any materials that are abusive, obscene, profane, sexually explicit, threatening
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
name: Yuhu
provenance_date: '2026-11-10'
provider_name: Yuhu
provider_slug: yuhu
slug: yuhu-eligibility
source_date: '2026-11-10'
source_filename: yuhu-eligibility.yml
source_heading: Eligibility
source_page: https://support.happy.co/hc/en-us/articles/24882424053396-Terms-of-Service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yuhu\naid: yuhu\nurl: https://support.happy.co/hc/en-us/articles/24882424053396-Terms-of-Service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is available only to individuals who are at least 18 years old, who are acting for themselves\n- type: business\n  text: or in their capacity as an employee or representative of a business entity or other organization (in which\n    case you represent and warrant that you are authorized to agree to the Terms of Use on behalf of yourself and\n    such entity or organization)\nrestricted_uses:\n\
  - summary: Abusive or unlawful content\n  text: Customer shall not, directly or indirectly, send, submit, post, receive or otherwise facilitate, or in any\n    way use, or permit to be used, the Yuhu Solution to send, submit, post, receive or otherwise facilitate the\n    transmission of any materials that are abusive, obscene, profane, sexually explicit, threatening\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is available only to individuals who are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/yuhu/eligibility/yuhu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Yuhu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Property Management
- PropTech
- Real Estate
- Multifamily
- Rentals
- Leasing
- Payments
- Partners API
---
