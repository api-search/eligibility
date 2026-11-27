---
claim_count: 2
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
  - summary: Unlawful or malicious content
    text: directly or indirectly input, upload, transmit or otherwise provide to or through the Uncountable Web Services, any information or materials that are unlawful or injurious
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Only authorized users of User Organizations given express permission by Uncountable Inc. shall be allowed access to the Uncountable Web Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Uncountable
provenance_date: '2026-11-10'
provider_name: Uncountable
provider_slug: uncountable
slug: uncountable-eligibility
source_date: '2026-11-10'
source_filename: uncountable-eligibility.yml
source_heading: Eligibility
source_page: https://www.uncountable.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Uncountable\naid: uncountable\nurl: https://www.uncountable.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or malicious content\n  text: directly or indirectly input, upload, transmit or otherwise provide to or through the Uncountable Web Services,\n    any information or materials that are unlawful or injurious\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Only authorized users of User Organizations given express permission by Uncountable Inc. shall be allowed\n    access\
  \ to the Uncountable Web Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/uncountable/eligibility/uncountable-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Uncountable's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Laboratory Informatics
- LIMS
- Electronic Lab Notebook
- R&D Data Management
- PLM
- Quality Management
- Materials Science
- Chemicals
- Artificial Intelligence
- MCP
---
