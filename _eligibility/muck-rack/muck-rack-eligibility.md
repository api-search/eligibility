---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled and offered by us from the United States of America, Canada, the EU/UK and Ireland. We make no representations that the Service is appropriate or available for use in other locations.
  entity_types:
  - text: If you are entering these Terms on behalf of a company or other organization, you hereby represent and warrant that you are authorized to enter into these Terms on behalf of such company or organization
    type: business
  minimum_age:
    text: Our Service is not intended for and may not be used by individuals under 13 years of age.
    value: '13'
  restricted_uses:
  - summary: No health, sensitive personal or government ID data
    text: the Services are not intended for use in the storage, processing, or handling of data that is (i) Protected Health Information subject to the Health Insurance Portability and Accountability Act
  - summary: No bots or automated account registration
    text: Accounts registered by “bots” or other automated methods are not permitted under any circumstances.
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
name: Muck Rack
provenance_date: '2026-11-10'
provider_name: Muck Rack
provider_slug: muck-rack
slug: muck-rack-eligibility
source_date: '2026-11-10'
source_filename: muck-rack-eligibility.yml
source_heading: Eligibility
source_page: https://muckrack.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Muck Rack\naid: muck-rack\nurl: https://muckrack.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled and offered by us from the United States of America, Canada, the EU/UK and Ireland.\n    We make no representations that the Service is appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: If you are entering these Terms on behalf of a company or other organization, you hereby represent and warrant\n    that you are authorized to enter into these Terms on behalf of such company or organization\nrestricted_uses:\n\
  - summary: No health, sensitive personal or government ID data\n  text: the Services are not intended for use in the storage, processing, or handling of data that is (i) Protected\n    Health Information subject to the Health Insurance Portability and Accountability Act\n- summary: No bots or automated account registration\n  text: Accounts registered by “bots” or other automated methods are not permitted under any circumstances.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Our Service is not intended for and may not be used by individuals under 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/muck-rack/eligibility/muck-rack-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Muck Rack's own page on 2026-11-10.
synthetic: false
tags:
- Public Relations
- Media Monitoring
- Media Database
- Journalists
- Communications
- Press Releases
- Earned Media
- Social Listening
- Marketing
- News
- Analytics
- Company
---
