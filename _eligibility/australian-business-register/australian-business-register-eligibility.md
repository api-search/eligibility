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
    kyc: null
    text: By registering for this service you will become legally bound by ABN Lookup Web Services Agreement.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Australian Business Register
provenance_date: '2026-11-09'
provider_name: Australian Business Register
provider_slug: australian-business-register
slug: australian-business-register-eligibility
source_date: '2026-11-09'
source_filename: australian-business-register-eligibility.yml
source_heading: Eligibility
source_page: https://abr.business.gov.au/Tools/WebServicesAgreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Australian Business Register\naid: australian-business-register\nurl: https://abr.business.gov.au/Tools/WebServicesAgreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By registering for this service you will become legally bound by ABN Lookup Web Services Agreement.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/australian-business-register/eligibility/australian-business-register-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Australian Business Register's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Government
- Australia
- Business Registry
- ABN
- Tax
- Public Sector
- Open Data
---
