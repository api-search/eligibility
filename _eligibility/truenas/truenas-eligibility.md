---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: all Hardware shall be shipped FOB Destination, Freight Prepaid & Add , worldwide.
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All orders are subject to credit approval by TrueNAS.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TrueNAS
provenance_date: '2026-11-10'
provider_name: TrueNAS
provider_slug: truenas
slug: truenas-eligibility
source_date: '2026-11-10'
source_filename: truenas-eligibility.yml
source_heading: Eligibility
source_page: https://www.truenas.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TrueNAS\naid: truenas\nurl: https://www.truenas.com/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: all Hardware shall be shipped FOB Destination, Freight Prepaid & Add , worldwide.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All orders are subject to credit approval by TrueNAS.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/truenas/eligibility/truenas-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from TrueNAS's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Storage
- Open Source
- Enterprise
- Data Protection
---
