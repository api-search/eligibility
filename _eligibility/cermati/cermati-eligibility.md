---
api_specs:
- filename: cermati-protect-openapi.json
  format: json
  label: Cermati Protect Generic Insurance API
  slug: cermati-protect-generic-insurance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cermati/openapi/cermati-protect-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Anda menyatakan dan menjamin bahwa Anda adalah orang yang berhak dan cakap untuk mengadakan perjanjian yang mengikat
    type: individual
  - text: Situs ini hanya boleh diakses dan digunakan secara langsung oleh individu atau bisnis yang sedang mencari produk atau layanan untuk individu atau bisnis tersebut.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal non-commercial use only
    text: Anda hanya diperkenankan untuk mengakses dan/atau menggunakan Situs ini untuk keperluan pribadi dan non-komersil
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
name: Cermati
provenance_date: '2026-11-09'
provider_name: Cermati
provider_slug: cermati
slug: cermati-eligibility
source_date: '2026-11-09'
source_filename: cermati-eligibility.yml
source_heading: Eligibility
source_page: https://www.cermati.com/pages/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cermati\naid: cermati\nurl: https://www.cermati.com/pages/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Anda menyatakan dan menjamin bahwa Anda adalah orang yang berhak dan cakap untuk mengadakan perjanjian yang\n    mengikat\n- type: business\n  text: Situs ini hanya boleh diakses dan digunakan secara langsung oleh individu atau bisnis yang sedang mencari\n    produk atau layanan untuk individu atau bisnis tersebut.\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: Anda hanya diperkenankan\
  \ untuk mengakses dan/atau menggunakan Situs ini untuk keperluan pribadi dan non-komersil\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cermati/eligibility/cermati-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Cermati's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Loans
- Credit Cards
- Insurance
- Investment
- Indonesia
---
