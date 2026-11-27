---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for the business purposes of Customer
    type: business
  - text: If you are a financial professional and any documents, information, or data is provided to you then it is for financial professional use only
    type: individual
  minimum_age:
    text: you must be at least 18 years of age to use the Services on this website or the portal
    value: '18'
  restricted_uses:
  - summary: Financial professional use only
    text: it is for financial professional use only, unless it explicitly and unambiguously in writing states otherwise
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
name: Signal Advisors
provenance_date: '2026-11-10'
provider_name: Signal Advisors
provider_slug: signal-advisors
slug: signal-advisors-eligibility
source_date: '2026-11-10'
source_filename: signal-advisors-eligibility.yml
source_heading: Eligibility
source_page: https://www.signaladvisors.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Signal Advisors\naid: signal-advisors\nurl: https://www.signaladvisors.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: for the business purposes of Customer\n- type: individual\n  text: If you are a financial professional and any documents, information, or data is provided to you then it is\n    for financial professional use only\nrestricted_uses:\n- summary: Financial professional use only\n  text: it is for financial professional use only, unless it explicitly and unambiguously in writing\
  \ states otherwise\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years of age to use the Services on this website or the portal\n"
source_yaml_url: https://artifacts.apis.io/signal-advisors/eligibility/signal-advisors-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Signal Advisors's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Insurance
- Wealth Management
- Annuities
- Financial Advisors
- Software-as-a-Service
---
