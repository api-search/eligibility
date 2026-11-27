---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: CommitChange is operated from the United States and makes no representation that the website is appropriate or available for use in other locations.
  entity_types:
  - text: If you are registering on behalf of a business or entity, you represent and warrant that you have authority to bind that entity.
    type: business
  - text: Payment processing services for nonprofit organizations on CommitChange are provided by Stripe
    type: nonprofit
  minimum_age:
    text: Users must be at least 13 years old to use CommitChange.
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: only for sharing information, donating to charities, and other non-commercial activities designated by our website
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you agree to provide CommitChange accurate and complete information about you and your business
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CommitChange
provenance_date: '2026-11-09'
provider_name: CommitChange
provider_slug: commitchange
slug: commitchange-eligibility
source_date: '2026-11-09'
source_filename: commitchange-eligibility.yml
source_heading: Eligibility
source_page: https://commitchange.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CommitChange\naid: commitchange\nurl: https://commitchange.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: CommitChange is operated from the United States and makes no representation that the website is appropriate\n    or available for use in other locations.\nentity_types:\n- type: business\n  text: If you are registering on behalf of a business or entity, you represent and warrant that you have authority\n    to bind that entity.\n- type: nonprofit\n  text: Payment processing services for nonprofit organizations on CommitChange are provided by Stripe\nrestricted_uses:\n\
  - summary: Non-commercial use only\n  text: only for sharing information, donating to charities, and other non-commercial activities designated by our\n    website\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you agree to provide CommitChange accurate and complete information about you and your business\nminimum_age:\n  value: '13'\n  text: Users must be at least 13 years old to use CommitChange.\n"
source_yaml_url: https://artifacts.apis.io/commitchange/eligibility/commitchange-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from CommitChange's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Non-Profit
- Fundraising
- Donations
- Payments
- Event
- Ticketing
- Donor Management
- Crowdfunding
- Open Source
---
