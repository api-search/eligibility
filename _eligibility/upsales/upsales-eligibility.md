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
  - summary: Restricted use purpose
    text: The Service may not be used in violation of the purpose of the Service, which is to serve as a platform for managing contact information, commercial relationships and/or business processes within B2B sales, marketing, customer care and/or related revenue-generating activities
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
name: Upsales
provenance_date: '2026-11-10'
provider_name: Upsales
provider_slug: upsales
slug: upsales-eligibility
source_date: '2026-11-10'
source_filename: upsales-eligibility.yml
source_heading: Eligibility
source_page: https://www.upsales.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Upsales\naid: upsales\nurl: https://www.upsales.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Restricted use purpose\n  text: The Service may not be used in violation of the purpose of the Service, which is to serve as a platform\n    for managing contact information, commercial relationships and/or business processes within B2B sales, marketing,\n    customer care and/or related revenue-generating activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/upsales/eligibility/upsales-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Upsales's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales
- Artificial Intelligence
- CRM
- Software-as-a-Service
---
