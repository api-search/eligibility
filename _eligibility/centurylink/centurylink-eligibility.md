---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the company that you are employed by (“Customer”) agree to the following terms and conditions.
    type: business
  minimum_age:
    text: null
    value: null
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
name: CenturyLink (Lumen Technologies)
provenance_date: '2026-11-09'
provider_name: CenturyLink (Lumen Technologies)
provider_slug: centurylink
slug: centurylink-eligibility
source_date: '2026-11-09'
source_filename: centurylink-eligibility.yml
source_heading: Eligibility
source_page: https://www.lumen.com/en-us/about/legal/api-developer-terms-and-conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CenturyLink (Lumen Technologies)\naid: centurylink\nurl: https://www.lumen.com/en-us/about/legal/api-developer-terms-and-conditions.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the company that you are employed by (“Customer”) agree to the following terms and conditions.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/centurylink/eligibility/centurylink-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from CenturyLink (Lumen Technologies)'s own page on 2026-11-09.
synthetic: false
tags:
- Broadband
- Connectivity
- Edge
- Fiber
- Lumen
- Networks
- OAuth
- Quantum Fiber
- SD-WAN
- Telecommunications
- Fortune 500
- Authentication
---
