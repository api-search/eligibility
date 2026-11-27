---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: They are of legal age and possess legal competence.
    value: null
  restricted_uses:
  - summary: Export control compliance
    text: Neither party will export, re-export, transfer, or make available, directly or indirectly, any regulated item or information in violation of applicable export control laws or regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Pangea offers streamlined client onboarding services, including comprehensive Know Your Customer (KYC) and Anti-Money Laundering (AML) processes to ensure compliance and security.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pangea
provenance_date: '2026-11-10'
provider_name: Pangea
provider_slug: pangea-io
slug: pangea-io-eligibility
source_date: '2026-11-10'
source_filename: pangea-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.pangea.io/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pangea\naid: pangea-io\nurl: https://www.pangea.io/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export control compliance\n  text: Neither party will export, re-export, transfer, or make available, directly or indirectly, any regulated\n    item or information in violation of applicable export control laws or regulations.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Pangea offers streamlined client onboarding services, including comprehensive Know Your Customer (KYC) and\n   \
  \ Anti-Money Laundering (AML) processes to ensure compliance and security.\nminimum_age:\n  value: null\n  text: They are of legal age and possess legal competence.\n"
source_yaml_url: https://artifacts.apis.io/pangea-io/eligibility/pangea-io-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Pangea's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Risk Management
- FX Hedging
- Artificial Intelligence
---
