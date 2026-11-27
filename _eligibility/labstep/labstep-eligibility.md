---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: (If a Territory is not specified in the Order, then Territory shall be the Customer’s country.)
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitors excluded
    text: (vii) use the Labstep Service if Customer is a competitor of Labstep;
  - summary: Export control restrictions
    text: Customer may not use the Labstep Services to transmit or host data controlled for export under Export Control Laws without prior written consent from Labstep.
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
name: Labstep
provenance_date: '2026-11-09'
provider_name: Labstep
provider_slug: labstep
slug: labstep-eligibility
source_date: '2026-11-09'
source_filename: labstep-eligibility.yml
source_heading: Eligibility
source_page: https://www.labstep.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Labstep\naid: labstep\nurl: https://www.labstep.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: (If a Territory is not specified in the Order, then Territory shall be the Customer’s country.)\nentity_types: []\nrestricted_uses:\n- summary: Competitors excluded\n  text: (vii) use the Labstep Service if Customer is a competitor of Labstep;\n- summary: Export control restrictions\n  text: Customer may not use the Labstep Services to transmit or host data controlled for export under Export Control\n    Laws without prior written consent from Labstep.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/labstep/eligibility/labstep-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Labstep's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Electronic Lab Notebook
- Life Sciences
- Laboratory
- Research Data Management
- Scientific Software
- Inventory
- Biotechnology
- Chemistry
- Compliance
---
