---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you create an account on behalf of business, you confirm that you have the authority to bind such entity to these Terms.
    type: business
  minimum_age:
    text: Our Services are restricted for people under 18 years old and by creating an account you confirm you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Laws of user's country
    text: you represent and warrant that you will not use the Services if the laws of your country prohibit you from doing so in accordance with these Terms.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: To become a Creator, you must apply via hello@rexby.com. Acceptance from us to become an Creator does in no way obligate us to make your User Content available through our Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rexby
provenance_date: '2026-11-10'
provider_name: Rexby
provider_slug: rexby
slug: rexby-eligibility
source_date: '2026-11-10'
source_filename: rexby-eligibility.yml
source_heading: Eligibility
source_page: https://www.rexby.com/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rexby\naid: rexby\nurl: https://www.rexby.com/termsofuse\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you create an account on behalf of business, you confirm that you have the authority to bind such entity\n    to these Terms.\nrestricted_uses:\n- summary: Laws of user's country\n  text: you represent and warrant that you will not use the Services if the laws of your country prohibit you from\n    doing so in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: To become a Creator,\
  \ you must apply via hello@rexby.com. Acceptance from us to become an Creator does in\n    no way obligate us to make your User Content available through our Services.\nminimum_age:\n  value: '18'\n  text: Our Services are restricted for people under 18 years old and by creating an account you confirm you are\n    at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/rexby/eligibility/rexby-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Rexby's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Travel
- Travel Guides
- Maps
- Trip Planning
- Creator Economy
- Consumer App
- Mobile
---
