---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and legally able to enter into a contract to use the service.
    type: individual
  - text: If you act for a business, you must have authority to agree for it.
    type: business
  minimum_age:
    text: You must be at least 18 and legally able to enter into a contract to use the service.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require email verification and apply reasonable security checks, rate limits and abuse controls.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Words into Music
provenance_date: '2026-11-10'
provider_name: Words into Music
provider_slug: wordsintomusic
slug: wordsintomusic-eligibility
source_date: '2026-11-10'
source_filename: wordsintomusic-eligibility.yml
source_heading: Eligibility
source_page: https://wordsintomusic.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Words into Music\naid: wordsintomusic\nurl: https://wordsintomusic.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and legally able to enter into a contract to use the service.\n- type: business\n  text: If you act for a business, you must have authority to agree for it.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require email verification and apply reasonable security checks, rate limits and abuse controls.\nminimum_age:\n  value: '18'\n\
  \  text: You must be at least 18 and legally able to enter into a contract to use the service.\n"
source_yaml_url: https://artifacts.apis.io/wordsintomusic/eligibility/wordsintomusic-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Words into Music's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Music
- Audio
- Generation
---
