---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this website for use only by persons located in the United States.
  entity_types:
  - text: These Terms of Use permit you to use this website for your personal and internal business purposes only.
    type: business
  minimum_age:
    text: you are at least 18 years of age or older
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
name: Kenect
provenance_date: '2026-11-09'
provider_name: Kenect
provider_slug: kenect
slug: kenect-eligibility
source_date: '2026-11-09'
source_filename: kenect-eligibility.yml
source_heading: Eligibility
source_page: https://kenect.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kenect\naid: kenect\nurl: https://kenect.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this website for use only by persons located in the United States.\nentity_types:\n- type: business\n  text: These Terms of Use permit you to use this website for your personal and internal business purposes only.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/kenect/eligibility/kenect-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Kenect's own page on 2026-11-09.
synthetic: false
tags:
- Automotive
- Messaging
- Artificial Intelligence
- Customer Engagement
- Reputation Management
---
