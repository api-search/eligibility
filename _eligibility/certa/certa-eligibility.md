---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer will not (a) use the Services in countries subject to comprehensive U.S. sanctions
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Trade sanctions and export controls
    text: Customer agrees to comply with all applicable trade sanctions and export control laws in its use of the Services.
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
name: Certa
provenance_date: '2026-11-09'
provider_name: Certa
provider_slug: certa
slug: certa-eligibility
source_date: '2026-11-09'
source_filename: certa-eligibility.yml
source_heading: Eligibility
source_page: https://www.certa.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Certa\naid: certa\nurl: https://www.certa.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer will not (a) use the Services in countries subject to comprehensive U.S. sanctions\nentity_types: []\nrestricted_uses:\n- summary: Trade sanctions and export controls\n  text: Customer agrees to comply with all applicable trade sanctions and export control laws in its use of the\n    Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/certa/eligibility/certa-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Certa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Third-Party Risk Management
- Compliance
- Procurement
- Vendor Management
- Risk Management
- ESG
- KYC
- Supplier Onboarding
- Identity
- Verification
- Fraud Prevention
---
