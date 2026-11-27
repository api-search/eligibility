---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If Marketer is an individual, Marketer must be over the age of majority in Marketer’s jurisdiction of residence who can form legally binding contracts
    type: individual
  - text: If Marketer is a corporation, partnership, association or other business entity, Marketer agrees that Marketer has the authority to bind the corporation, partnership, association or other business entity to these Terms of Service.
    type: business
  minimum_age:
    text: Marketer must be over the age of majority in Marketer’s jurisdiction of residence
    value: age of majority
  restricted_uses:
  - summary: Use prohibited where unlawful
    text: 'If such use is not so permitted by applicable law, #paid prohibits all use and access to the Platform and Services.'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Managed Campaigns are not available for all Marketers.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hashtag Paid
provenance_date: '2026-11-09'
provider_name: Hashtag Paid
provider_slug: hashtag-paid
slug: hashtag-paid-eligibility
source_date: '2026-11-09'
source_filename: hashtag-paid-eligibility.yml
source_heading: Eligibility
source_page: https://hashtagpaid.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hashtag Paid\naid: hashtag-paid\nurl: https://hashtagpaid.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If Marketer is an individual, Marketer must be over the age of majority in Marketer’s jurisdiction of residence\n    who can form legally binding contracts\n- type: business\n  text: If Marketer is a corporation, partnership, association or other business entity, Marketer agrees that Marketer\n    has the authority to bind the corporation, partnership, association or other business entity to these Terms\n\
  \    of Service.\nrestricted_uses:\n- summary: Use prohibited where unlawful\n  text: 'If such use is not so permitted by applicable law, #paid prohibits all use and access to the Platform and\n    Services.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Managed Campaigns are not available for all Marketers.\nminimum_age:\n  value: age of majority\n  text: Marketer must be over the age of majority in Marketer’s jurisdiction of residence\n"
source_yaml_url: https://artifacts.apis.io/hashtag-paid/eligibility/hashtag-paid-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Hashtag Paid's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Creator Marketing
- Influencer Marketing
- Marketing
- Advertising
- Social Media
- Content
- Marketplace
- Creator Economy
---
