---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE USING THE WEBSITE AS AN EMPLOYEE OF A CORPORATION, PARTNERSHIP OR SIMILAR ENTITY, THEN YOU MUST BE AUTHORIZED TO SIGN FOR AND BIND SUCH ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sandbox limited to testing and evaluation
    text: You agree to use the sandbox exclusively for its intended purposes and not for any commercial, unlawful, or unauthorized activities
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
name: Balance
provenance_date: '2026-11-09'
provider_name: Balance
provider_slug: getbalance
slug: getbalance-eligibility
source_date: '2026-11-09'
source_filename: getbalance-eligibility.yml
source_heading: Eligibility
source_page: https://www.getbalance.com/legal/balance-website-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Balance\naid: getbalance\nurl: https://www.getbalance.com/legal/balance-website-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE USING THE WEBSITE AS AN EMPLOYEE OF A CORPORATION, PARTNERSHIP OR SIMILAR ENTITY, THEN YOU MUST\n    BE AUTHORIZED TO SIGN FOR AND BIND SUCH ENTITY\nrestricted_uses:\n- summary: Sandbox limited to testing and evaluation\n  text: You agree to use the sandbox exclusively for its intended purposes and not for any commercial, unlawful,\n    or unauthorized activities\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/getbalance/eligibility/getbalance-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Balance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- B2B Payments
- Trade Credit
- Buy Now Pay Later
- Accounts Receivable
- Financial Infrastructure
- Fintech
- Order-to-Cash
- Embedded Finance
- Marketplace
---
