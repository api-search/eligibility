---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may not export or allow export to Embargoed Countries or Designated Nationals; no served country list is given.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: Customer may not provide to any person or export or re-export or allow the export or re-export of the Services
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
name: Neo.Tax
provenance_date: '2026-11-10'
provider_name: Neo.Tax
provider_slug: neotax
slug: neotax-eligibility
source_date: '2026-11-10'
source_filename: neotax-eligibility.yml
source_heading: Eligibility
source_page: https://www.neo.tax/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Neo.Tax\naid: neotax\nurl: https://www.neo.tax/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer may not export or allow export to Embargoed Countries or Designated Nationals; no served country\n    list is given.\nentity_types: []\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: Customer may not provide to any person or export or re-export or allow the export or re-export of the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/neotax/eligibility/neotax-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Neo.Tax's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Tax
- R&D Tax Credit
- Accounting
- Fintech
- Compliance
- Artificial Intelligence
- Automation
---
