---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Section 22 prohibits use by persons subject to OFAC sanctions or located in Belarus, Russia, or Venezuela, and states the Site is not permitted for commercial use in Mainland China.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: No software or any other Materials associated with this Site may be downloaded or otherwise exported or re-exported to countries or persons prohibited under relevant export control laws
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
name: BitSight
provenance_date: '2026-11-09'
provider_name: BitSight
provider_slug: bitsight
slug: bitsight-eligibility
source_date: '2026-11-09'
source_filename: bitsight-eligibility.yml
source_heading: Eligibility
source_page: https://www.bitsight.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BitSight\naid: bitsight\nurl: https://www.bitsight.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Section 22 prohibits use by persons subject to OFAC sanctions or located in Belarus, Russia, or Venezuela,\n    and states the Site is not permitted for commercial use in Mainland China.\nentity_types: []\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: No software or any other Materials associated with this Site may be downloaded or otherwise exported or\n    re-exported to countries or persons prohibited under relevant export control laws\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bitsight/eligibility/bitsight-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from BitSight's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cyber Risk
- Security Ratings
- Third-Party Risk Management
- Attack Surface Management
- Threat Intelligence
- Vendor Risk
- Risk Management
---
