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
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: A2 does not verify payer identity or provide KYC.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: intesta-io
provenance_date: '2026-11-09'
provider_name: intesta-io
provider_slug: intesta-io
slug: intesta-io-eligibility
source_date: '2026-11-09'
source_filename: intesta-io-eligibility.yml
source_heading: Eligibility
source_page: https://intesta.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: intesta-io\naid: intesta-io\nurl: https://intesta.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: A2 does not verify payer identity or provide KYC.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/intesta-io/eligibility/intesta-io-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from intesta-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
