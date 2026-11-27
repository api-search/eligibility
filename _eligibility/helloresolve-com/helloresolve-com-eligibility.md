---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are of legal age to form a binding contract
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By using this Website, you represent that you are of legal age to form a binding contract and that you are not a person barred from receiving services under the laws of the United States or other applicable jurisdiction.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Resolve
provenance_date: '2026-11-09'
provider_name: Resolve
provider_slug: helloresolve-com
slug: helloresolve-com-eligibility
source_date: '2026-11-09'
source_filename: helloresolve-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.helloresolve.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Resolve\naid: helloresolve-com\nurl: https://www.helloresolve.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By using this Website, you represent that you are of legal age to form a binding contract and that you are\n    not a person barred from receiving services under the laws of the United States or other applicable jurisdiction.\nminimum_age:\n  value: null\n  text: you are of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/helloresolve-com/eligibility/helloresolve-com-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from Resolve's own page on 2026-11-09.
synthetic: false
tags:
- Debt Relief
- Financial Health
- Bankruptcy
---
