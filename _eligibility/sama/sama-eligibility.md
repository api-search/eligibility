---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: it is a corporation duly organized, validly existing and in good standing under applicable law
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export law compliance
    text: Customer shall not permit Users to access or use Service in a U.S.-embargoed country or in violation of any U.S. export law or regulation.
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
name: Sama
provenance_date: '2026-11-10'
provider_name: Sama
provider_slug: sama
slug: sama-eligibility
source_date: '2026-11-10'
source_filename: sama-eligibility.yml
source_heading: Eligibility
source_page: https://www.sama.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sama\naid: sama\nurl: https://www.sama.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: it is a corporation duly organized, validly existing and in good standing under applicable law\nrestricted_uses:\n- summary: Export law compliance\n  text: Customer shall not permit Users to access or use Service in a U.S.-embargoed country or in violation of\n    any U.S. export law or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sama/eligibility/sama-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Sama's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Annotation
- Artificial Intelligence
- B Corp
- Training Data
---
