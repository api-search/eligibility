---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    served: []
    text: any country or territory subject to comprehensive U.S. sanctions (currently, Cuba, Iran, North Korea
  entity_types:
  - text: If you use the Services on behalf of a company or other entity then "you" includes you and that entity
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Sanctioned jurisdictions and persons
    text: You will not access or use, or permit access to or use of, the Services in or for the benefit of any Sanctioned Jurisdiction
  - summary: Export restrictions
    text: you will not export or re-export, directly or indirectly, the Services
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: To withdraw funds, you must create a Stripe Connect Express account, which requires identity verification (KYC) as required by Stripe and applicable law.
excluded_countries:
- CU
- IR
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Polsia
provenance_date: '2026-11-10'
provider_name: Polsia
provider_slug: polsia
slug: polsia-eligibility
source_date: '2026-11-10'
source_filename: polsia-eligibility.yml
source_heading: Eligibility
source_page: https://polsia.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Polsia\naid: polsia\nurl: https://polsia.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  text: any country or territory subject to comprehensive U.S. sanctions (currently, Cuba, Iran, North Korea\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other entity then \"you\" includes you and that entity\nrestricted_uses:\n- summary: Sanctioned jurisdictions and persons\n  text: You will not access or use, or permit access to or use of, the Services in or for the benefit of any Sanctioned\n    Jurisdiction\n- summary:\
  \ Export restrictions\n  text: you will not export or re-export, directly or indirectly, the Services\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: To withdraw funds, you must create a Stripe Connect Express account, which requires identity verification\n    (KYC) as required by Stripe and applicable law.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/polsia/eligibility/polsia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Polsia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software
- Artificial Intelligence
- AI Agents
- Automation
- Business Automation
- Software-as-a-Service
- Autonomous Agents
---
