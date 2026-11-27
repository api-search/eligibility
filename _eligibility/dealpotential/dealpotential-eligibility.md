---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Certain Service of the Website is not available to minors under the age of 13
    value: '13'
  restricted_uses:
  - summary: Use contrary to law
    text: Using this Website contrary to applicable laws and regulations, or in a way that causes, or may cause, harm to the Website, or any person or business entity
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
name: DealPotential
provenance_date: '2026-11-09'
provider_name: DealPotential
provider_slug: dealpotential
slug: dealpotential-eligibility
source_date: '2026-11-09'
source_filename: dealpotential-eligibility.yml
source_heading: Eligibility
source_page: https://dealpotential.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DealPotential\naid: dealpotential\nurl: https://dealpotential.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Use contrary to law\n  text: Using this Website contrary to applicable laws and regulations, or in a way that causes, or may cause, harm\n    to the Website, or any person or business entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Certain Service of the Website is not available to minors under the age of 13\n"
source_yaml_url: https://artifacts.apis.io/dealpotential/eligibility/dealpotential-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from DealPotential's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Aggregator
- Private Equity
- Venture Capital
---
