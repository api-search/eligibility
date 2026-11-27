---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Contract applies where the Premises are in England, Wales or Scotland; the Energy Ombudsman and Ofgem references are to Great Britain.
  entity_types:
  - text: 'By accepting these terms and conditions you are entering into a legally-binding contract with us and represent that: You are at least 18 years old; You have the authority to enter into this Contract; You either own or live at the Premises'
    type: individual
  minimum_age:
    text: You are at least 18 years old;
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may run checks on you (and anyone else also responsible for payment) at Credit Reference and Fraud Prevention agencies, initially and periodically to help us assess your ability to pay for your Energy bills.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fuse
provenance_date: '2026-11-09'
provider_name: Fuse
provider_slug: fuse
slug: fuse-eligibility
source_date: '2026-11-09'
source_filename: fuse-eligibility.yml
source_heading: Eligibility
source_page: https://www.fuseenergy.com/legal/energy-supply-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fuse\naid: fuse\nurl: https://www.fuseenergy.com/legal/energy-supply-terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Contract applies where the Premises are in England, Wales or Scotland; the Energy Ombudsman and Ofgem references\n    are to Great Britain.\nentity_types:\n- type: individual\n  text: 'By accepting these terms and conditions you are entering into a legally-binding contract with us and represent\n    that: You are at least 18 years old; You have the authority to enter into this Contract; You either own or live\n    at the Premises'\nrestricted_uses:\
  \ []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may run checks on you (and anyone else also responsible for payment) at Credit Reference and Fraud Prevention\n    agencies, initially and periodically to help us assess your ability to pay for your Energy bills.\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old;\n"
source_yaml_url: https://artifacts.apis.io/fuse/eligibility/fuse-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Fuse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Utilities
- Electricity
- Gas
- EV Charging
- Solar
- Renewable Energy
- United Kingdom
---
