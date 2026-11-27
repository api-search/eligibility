---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All Advertisements are subject to Firefly’s approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Firefly
provenance_date: '2026-11-09'
provider_name: Firefly
provider_slug: firefly
slug: firefly-eligibility
source_date: '2026-11-09'
source_filename: firefly-eligibility.yml
source_heading: Eligibility
source_page: https://www.fireflyon.com/advertising-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Firefly\naid: firefly\nurl: https://www.fireflyon.com/advertising-terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All Advertisements are subject to Firefly’s approval.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/firefly/eligibility/firefly-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Firefly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- Digital Out Of Home
- Mobility
- AdTech
- Marketing
- Measurements
- Programmatic Advertising
---
