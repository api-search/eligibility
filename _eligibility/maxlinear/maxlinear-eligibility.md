---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Export section cites United States export control laws but names no countries the site serves or excludes.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: The United States Export Controls laws prohibit the export of certain technical data and software to certain territories.
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
name: MaxLinear
provenance_date: '2026-11-10'
provider_name: MaxLinear
provider_slug: maxlinear
slug: maxlinear-eligibility
source_date: '2026-11-10'
source_filename: maxlinear-eligibility.yml
source_heading: Eligibility
source_page: https://www.maxlinear.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MaxLinear\naid: maxlinear\nurl: https://www.maxlinear.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Export section cites United States export control laws but names no countries the site serves or excludes.\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: The United States Export Controls laws prohibit the export of certain technical data and software to certain\n    territories.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/maxlinear/eligibility/maxlinear-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from MaxLinear's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Semiconductors
- Connectivity
- Broadband
- Infrastructure
- Networking
- Hardware
- SDK
---
