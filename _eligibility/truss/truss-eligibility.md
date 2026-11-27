---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: All Linked Accounts must be with financial institutions in the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned transactions
    text: Customer shall comply with U.S. sanctions and anti‑money‑laundering laws and shall not use the Services for transactions involving prohibited countries, persons, or activities.
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: Truss and its bank partners and financial service providers may perform initial and ongoing business and beneficial‑owner due diligence, including KYC/KYB, sanctions screening, adverse media checks, and creditworthiness assessments
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Truss
provenance_date: '2026-11-10'
provider_name: Truss
provider_slug: truss
slug: truss-eligibility
source_date: '2026-11-10'
source_filename: truss-eligibility.yml
source_heading: Eligibility
source_page: https://trusspayments.com/legal/terms-of-service-11-13-2026
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Truss\naid: truss\nurl: https://trusspayments.com/legal/terms-of-service-11-13-2026\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: All Linked Accounts must be with financial institutions in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned transactions\n  text: Customer shall comply with U.S. sanctions and anti‑money‑laundering laws and shall not use the Services\n    for transactions involving prohibited countries, persons, or activities.\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: Truss and its bank\
  \ partners and financial service providers may perform initial and ongoing business and\n    beneficial‑owner due diligence, including KYC/KYB, sanctions screening, adverse media checks, and creditworthiness\n    assessments\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/truss/eligibility/truss-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Truss's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Banking
- Construction
- Payments
- Fintech
---
