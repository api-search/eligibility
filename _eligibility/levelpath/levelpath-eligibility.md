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
  - summary: Sanctioned countries/parties
    text: you are not located in a country that is subject to a U.S. Government embargo
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
name: Levelpath
provenance_date: '2026-11-09'
provider_name: Levelpath
provider_slug: levelpath
slug: levelpath-eligibility
source_date: '2026-11-09'
source_filename: levelpath-eligibility.yml
source_heading: Eligibility
source_page: https://www.levelpath.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Levelpath\naid: levelpath\nurl: https://www.levelpath.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned countries/parties\n  text: you are not located in a country that is subject to a U.S. Government embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/levelpath/eligibility/levelpath-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Levelpath's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Procurement
- Source-to-Pay
- Spend Management
- Contract Management
- Supplier Management
- Strategic Sourcing
- Risk Management
- Invoice Automation
- Artificial Intelligence
- Enterprise Software
---
