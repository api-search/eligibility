---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are not under the age of 13
    value: '13'
  restricted_uses:
  - summary: Unlawful or inappropriate AI inputs
    text: you agree not to submit information, inputs, that are unlawful, infringing, harmful, misleading, or otherwise inappropriate
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
name: Panaya
provenance_date: '2026-11-10'
provider_name: Panaya
provider_slug: panaya
slug: panaya-eligibility
source_date: '2026-11-10'
source_filename: panaya-eligibility.yml
source_heading: Eligibility
source_page: https://www.panaya.com/legal/panaya-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Panaya\naid: panaya\nurl: https://www.panaya.com/legal/panaya-terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or inappropriate AI inputs\n  text: you agree not to submit information, inputs, that are unlawful, infringing, harmful, misleading, or otherwise\n    inappropriate\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you are not under the age of 13\n"
source_yaml_url: https://artifacts.apis.io/panaya/eligibility/panaya-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Panaya's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Testing
- Test Automation
- Test Management
- Change Management
- Change Impact Analysis
- ERP
- SAP
- Oracle
- Salesforce
- Quality Assurance
- DevOps
---
