---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Supplier and their Affiliates agree to be bound by the terms of this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Embargoed or export-restricted use
    text: Supplier shall not permit any third party to access or use Services in a U.S.-embargoed country or in violation of any U.S. export law or regulation.
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
name: PureSpectrum
provenance_date: '2026-11-10'
provider_name: PureSpectrum
provider_slug: purespectrum
slug: purespectrum-eligibility
source_date: '2026-11-10'
source_filename: purespectrum-eligibility.yml
source_heading: Eligibility
source_page: https://www.purespectrum.com/general-supplier-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PureSpectrum\naid: purespectrum\nurl: https://www.purespectrum.com/general-supplier-terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Supplier and their Affiliates agree to be bound by the terms of this Agreement\nrestricted_uses:\n- summary: Embargoed or export-restricted use\n  text: Supplier shall not permit any third party to access or use Services in a U.S.-embargoed country or in violation\n    of any U.S. export law or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/purespectrum/eligibility/purespectrum-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from PureSpectrum's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Research
- Data
- Market Research
---
