---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AE
    text: This Platform is intended for use only by UAE residents. If you choose to use the Platform from locations outside the UAE, you do so at your sole risk.
  minimum_age:
    text: being 21 years of age or older in order to access our Platform as a Buyer.
    value: '21'
  restricted_uses:
  - summary: No unlawful or harassing use
    text: You agree to use our Platform and/or Services solely for legal purposes
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We reserve the right to reject or approve any request to create an account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Prypco
provenance_date: '2026-11-10'
provider_name: Prypco
provider_slug: prypco
slug: prypco-eligibility
source_date: '2026-11-10'
source_filename: prypco-eligibility.yml
source_heading: Eligibility
source_page: https://prypco.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prypco\naid: prypco\nurl: https://prypco.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AE\n  excluded: []\n  text: This Platform is intended for use only by UAE residents. If you choose to use the Platform from locations\n    outside the UAE, you do so at your sole risk.\nentity_types: []\nrestricted_uses:\n- summary: No unlawful or harassing use\n  text: You agree to use our Platform and/or Services solely for legal purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We reserve the right to reject or approve any request to create an account\n\
  minimum_age:\n  value: '21'\n  text: being 21 years of age or older in order to access our Platform as a Buyer.\n"
source_yaml_url: https://artifacts.apis.io/prypco/eligibility/prypco-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Prypco's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PropTech
- Real Estate
- Tokenization
- Fractional Investment
- Blockchain
- Mortgage
- Dubai
- United Arab Emirates
---
