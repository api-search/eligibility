---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least eighteen (18) years of age to register or otherwise use the Services.
    value: '18'
  restricted_uses:
  - summary: No alcohol ordering under 21
    text: You will not use OfficeLuv to order alcohol products unless you are 21 years of age or older
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
name: Office Luv
provenance_date: '2026-11-10'
provider_name: Office Luv
provider_slug: office-luv
slug: office-luv-eligibility
source_date: '2026-11-10'
source_filename: office-luv-eligibility.yml
source_heading: Eligibility
source_page: https://www.officeluv.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Office Luv\naid: office-luv\nurl: https://www.officeluv.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No alcohol ordering under 21\n  text: You will not use OfficeLuv to order alcohol products unless you are 21 years of age or older\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age to register or otherwise use the Services.\n"
source_yaml_url: https://artifacts.apis.io/office-luv/eligibility/office-luv-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Office Luv's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Office Management
- Procurement
- Purchasing
- Workplace
- Marketplace
- Spend Management
- Software-as-a-Service
---
