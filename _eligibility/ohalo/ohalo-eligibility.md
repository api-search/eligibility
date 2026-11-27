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
  - summary: Unlawful or security-risk use
    text: in connection with unlawful material, in a manner that would cause material risk to the security and operations of Ohalo or any of its customers
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
name: Ohalo
provenance_date: '2026-11-10'
provider_name: Ohalo
provider_slug: ohalo
slug: ohalo-eligibility
source_date: '2026-11-10'
source_filename: ohalo-eligibility.yml
source_heading: Eligibility
source_page: https://www.dataxray.io/eula/?from=ohalo
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ohalo\naid: ohalo\nurl: https://www.dataxray.io/eula/?from=ohalo\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or security-risk use\n  text: in connection with unlawful material, in a manner that would cause material risk to the security and operations\n    of Ohalo or any of its customers\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ohalo/eligibility/ohalo-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Ohalo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Governance
- Unstructured Data
- Data Discovery
- Data Classification
- Privacy
- Compliance
- Security
- Artificial Intelligence
---
