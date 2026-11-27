---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Commercial accounts are eligible for net-30 terms subject to credit review; credit card payment is available immediately.
    type: business
  - text: Public agency purchase orders are accepted on net-30 terms with no credit application.
    type: government
  minimum_age:
    text: null
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
name: Cintra Supply
provenance_date: '2026-11-09'
provider_name: Cintra Supply
provider_slug: cintrasupply-com
slug: cintrasupply-com-eligibility
source_date: '2026-11-09'
source_filename: cintrasupply-com-eligibility.yml
source_heading: Eligibility
source_page: https://cintrasupply.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cintra Supply\naid: cintrasupply-com\nurl: https://cintrasupply.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Commercial accounts are eligible for net-30 terms subject to credit review; credit card payment is available\n    immediately.\n- type: government\n  text: Public agency purchase orders are accepted on net-30 terms with no credit application.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cintrasupply-com/eligibility/cintrasupply-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Cintra Supply's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wholesale
- Industrial Supplies
- B2B
- Quote Service
---
