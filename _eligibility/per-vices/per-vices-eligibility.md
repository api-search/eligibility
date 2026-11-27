---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - BY
    - KP
    served: []
    text: We do not ship to Belarus or Democratic People’s Republic of Korea.
  entity_types:
  - text: 'In any contract with the United States government or in any contract that is a subcontract of any tier under a United States government contract:'
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Life support or critical applications
    text: Commercially available products sold by Per Vices are not designed, intended or approved for use in life support, implantable medical devices, transportation, nuclear, safety or other equipment where malfunction of the Product can reasonably be expected to result in personal injury, death, severe property damage or severe environmental harm.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- BY
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Per Vices
provenance_date: '2026-11-10'
provider_name: Per Vices
provider_slug: per-vices
slug: per-vices-eligibility
source_date: '2026-11-10'
source_filename: per-vices-eligibility.yml
source_heading: Eligibility
source_page: https://www.pervices.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Per Vices\naid: per-vices\nurl: https://www.pervices.com/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - BY\n  - KP\n  text: We do not ship to Belarus or Democratic People’s Republic of Korea.\nentity_types:\n- type: government\n  text: 'In any contract with the United States government or in any contract that is a subcontract of any tier\n    under a United States government contract:'\nrestricted_uses:\n- summary: Life support or critical applications\n  text: Commercially available products sold by Per Vices are not designed, intended or approved for use in life\n \
  \   support, implantable medical devices, transportation, nuclear, safety or other equipment where malfunction of\n    the Product can reasonably be expected to result in personal injury, death, severe property damage or severe\n    environmental harm.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/per-vices/eligibility/per-vices-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Per Vices's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software Defined Radio
- SDR
- Radio Frequency
- Wireless
- Hardware
- FPGA
- Telecommunications
- Embedded Systems
---
