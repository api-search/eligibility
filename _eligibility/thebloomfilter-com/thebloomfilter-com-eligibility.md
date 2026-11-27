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
  restricted_uses:
  - summary: No PII or regulated data input
    text: input, upload, transmit, or otherwise provide to or through the Software or Company’s systems any personally identifiable information, personal health information, or other data that is subject to regulation under applicable privacy laws
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
name: Bloomfilter
provenance_date: '2026-11-10'
provider_name: Bloomfilter
provider_slug: thebloomfilter-com
slug: thebloomfilter-com-eligibility
source_date: '2026-11-10'
source_filename: thebloomfilter-com-eligibility.yml
source_heading: Eligibility
source_page: https://bloomfilter.ai/legal/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloomfilter\naid: thebloomfilter-com\nurl: https://bloomfilter.ai/legal/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No PII or regulated data input\n  text: input, upload, transmit, or otherwise provide to or through the Software or Company’s systems any personally\n    identifiable information, personal health information, or other data that is subject to regulation under applicable\n    privacy laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/thebloomfilter-com/eligibility/thebloomfilter-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Bloomfilter's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Enterprise
- Workflows
- Process Intelligence
- Context Layer
---
