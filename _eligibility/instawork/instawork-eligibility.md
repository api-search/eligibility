---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: the Services are intended for residents of and business in the United States
  entity_types:
  - text: a company or business using our Services
    type: business
  minimum_age:
    text: You further agree that You are at least eighteen (18) years old and have legal authority to accept these Terms.
    value: '18'
  restricted_uses:
  - summary: No use violating laws or others' rights
    text: You agree that You will not use the Services in any way that would violate any laws, infringe on any rights of others (including, without limitation, intellectual property rights and laws pertaining to non-discrimination, equal opportunity, and the Fair Credit Reporting Act)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we may require You to provide information that may be used to confirm Your identity and help ensure the security of Your Account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Instawork
provenance_date: '2026-11-09'
provider_name: Instawork
provider_slug: instawork
slug: instawork-eligibility
source_date: '2026-11-09'
source_filename: instawork-eligibility.yml
source_heading: Eligibility
source_page: https://app.instawork.com/legal/instawork-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Instawork\naid: instawork\nurl: https://app.instawork.com/legal/instawork-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: the Services are intended for residents of and business in the United States\nentity_types:\n- type: business\n  text: a company or business using our Services\nrestricted_uses:\n- summary: No use violating laws or others' rights\n  text: You agree that You will not use the Services in any way that would violate any laws, infringe on any rights\n    of others (including, without limitation, intellectual property rights and\
  \ laws pertaining to non-discrimination,\n    equal opportunity, and the Fair Credit Reporting Act)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we may require You to provide information that may be used to confirm Your identity and help ensure the\n    security of Your Account\nminimum_age:\n  value: '18'\n  text: You further agree that You are at least eighteen (18) years old and have legal authority to accept these\n    Terms.\n"
source_yaml_url: https://artifacts.apis.io/instawork/eligibility/instawork-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Instawork's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Staffing
- Gig Economy
- Hospitality
- Workforce
- Labor
- MCP
- Agents
---
