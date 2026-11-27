---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting on behalf of a corporation, governmental organization, or other legal entity, you represent that you have the power and authority to enter into this agreement on behalf of that entity
    type: business
  minimum_age:
    text: Our Services are not directed to children younger than 13, and access and use of our Services is only offered to users 13 years of age or older.
    value: '13'
  restricted_uses:
  - summary: US sanctions compliance
    text: you expressly represent and warrant that your use of our Services and or associated services and products is not contrary to applicable U.S. Sanctions.
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
name: Makrwatch
provenance_date: '2026-11-10'
provider_name: Makrwatch
provider_slug: makrwatch
slug: makrwatch-eligibility
source_date: '2026-11-10'
source_filename: makrwatch-eligibility.yml
source_heading: Eligibility
source_page: https://makrwatch.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Makrwatch\naid: makrwatch\nurl: https://makrwatch.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting on behalf of a corporation, governmental organization, or other legal entity, you represent\n    that you have the power and authority to enter into this agreement on behalf of that entity\nrestricted_uses:\n- summary: US sanctions compliance\n  text: you expressly represent and warrant that your use of our Services and or associated services and products\n    is not contrary to applicable U.S.\
  \ Sanctions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Our Services are not directed to children younger than 13, and access and use of our Services is only offered\n    to users 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/makrwatch/eligibility/makrwatch-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Makrwatch's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Creator Economy
- Influencer Marketing
- Sponsorship
- Marketplace
- Advertising
- Content Creators
- Brand Deals
---
