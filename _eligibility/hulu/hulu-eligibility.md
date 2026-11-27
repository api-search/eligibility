---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The ESPN and Hulu Services are only available in the United States and certain of its territories.
  entity_types:
  - text: The Services are provided to individuals for their personal, noncommercial use only.
    type: individual
  - text: Companies, commercial establishments, associations and other groups may not purchase or use the Services.
    type: business
  minimum_age:
    text: You must be 18 years of age, or the age of majority in your state or territory of residence, to purchase the Services.
    value: '18'
  restricted_uses:
  - summary: commercial or business use
    text: use the Services for any commercial or business related use or in any commercial establishment or area open to the public
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You agree that we may take steps to verify the accuracy of information you provide.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hulu
provenance_date: '2026-11-09'
provider_name: Hulu
provider_slug: hulu
slug: hulu-eligibility
source_date: '2026-11-09'
source_filename: hulu-eligibility.yml
source_heading: Eligibility
source_page: https://www.hulu.com/subscriber_agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hulu\naid: hulu\nurl: https://www.hulu.com/subscriber_agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The ESPN and Hulu Services are only available in the United States and certain of its territories.\nentity_types:\n- type: individual\n  text: The Services are provided to individuals for their personal, noncommercial use only.\n- type: business\n  text: Companies, commercial establishments, associations and other groups may not purchase or use the Services.\nrestricted_uses:\n- summary: commercial or business use\n  text: use the Services for any commercial or business\
  \ related use or in any commercial establishment or area open\n    to the public\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You agree that we may take steps to verify the accuracy of information you provide.\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age, or the age of majority in your state or territory of residence, to purchase\n    the Services.\n"
source_yaml_url: https://artifacts.apis.io/hulu/eligibility/hulu-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Hulu's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Streaming
- Video
- Entertainment
- Subscription
---
