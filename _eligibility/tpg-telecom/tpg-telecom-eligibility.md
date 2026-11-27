---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: The contents of this website, the services available for use and any products and services available for purchase using the TPG Telecom website are meant for Australian residents only.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Social media content restrictions
    text: contains no spam or other commercial, advertising, marketing or promotional content or links or information which would facilitate the sale or purchase of products or services
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
name: TPG Telecom
provenance_date: '2026-11-10'
provider_name: TPG Telecom
provider_slug: tpg-telecom
slug: tpg-telecom-eligibility
source_date: '2026-11-10'
source_filename: tpg-telecom-eligibility.yml
source_heading: Eligibility
source_page: https://www.tpgtelecom.com.au/website-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TPG Telecom\naid: tpg-telecom\nurl: https://www.tpgtelecom.com.au/website-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: The contents of this website, the services available for use and any products and services available for\n    purchase using the TPG Telecom website are meant for Australian residents only.\nentity_types: []\nrestricted_uses:\n- summary: Social media content restrictions\n  text: contains no spam or other commercial, advertising, marketing or promotional content or links or information\n    which would facilitate the sale or purchase of products or\
  \ services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tpg-telecom/eligibility/tpg-telecom-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from TPG Telecom's own page on 2026-11-10.
synthetic: false
tags:
- Telecommunications
- Australia
- Mobile Network Operator
- Broadband
- Messaging
- SMS
- IoT
- 5G
---
