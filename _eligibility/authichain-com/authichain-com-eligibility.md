---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 or older to start checkout or to create an account.
    type: individual
  minimum_age:
    text: You must be 18 or older to start checkout or to create an account.
    value: '18'
  restricted_uses:
  - summary: No illegal use
    text: Do not use the service to break the law.
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
name: AuthiChain
provenance_date: '2026-11-09'
provider_name: AuthiChain
provider_slug: authichain-com
slug: authichain-com-eligibility
source_date: '2026-11-09'
source_filename: authichain-com-eligibility.yml
source_heading: Eligibility
source_page: https://authichain.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AuthiChain\naid: authichain-com\nurl: https://authichain.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 or older to start checkout or to create an account.\nrestricted_uses:\n- summary: No illegal use\n  text: Do not use the service to break the law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older to start checkout or to create an account.\n"
source_yaml_url: https://artifacts.apis.io/authichain-com/eligibility/authichain-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AuthiChain's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Verification
- QR
- Digital Product Passport
- Supply Chain
---
