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
  restricted_uses:
  - summary: Sensitive documents via forms
    text: send Social Security numbers, identification documents, financial records, or rental application materials through our forms.
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
name: Clever Real Estate
provenance_date: '2026-11-09'
provider_name: Clever Real Estate
provider_slug: clever-real-estate
slug: clever-real-estate-eligibility
source_date: '2026-11-09'
source_filename: clever-real-estate-eligibility.yml
source_heading: Eligibility
source_page: https://cleverrealtors.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clever Real Estate\naid: clever-real-estate\nurl: https://cleverrealtors.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sensitive documents via forms\n  text: send Social Security numbers, identification documents, financial records, or rental application materials\n    through our forms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clever-real-estate/eligibility/clever-real-estate-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Clever Real Estate's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Brokerage
- Dallas
- Low Commission
---
