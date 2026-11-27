---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By using this web site represent that you are of legal age to form a binding contract
    value: null
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
name: Connective Health
provenance_date: '2026-11-09'
provider_name: Connective Health
provider_slug: connective-health
slug: connective-health-eligibility
source_date: '2026-11-09'
source_filename: connective-health-eligibility.yml
source_heading: Eligibility
source_page: https://connectivehealth.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Connective Health\naid: connective-health\nurl: https://connectivehealth.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: By using this web site represent that you are of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/connective-health/eligibility/connective-health-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Connective Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Interoperability
- Risk Adjustment
---
