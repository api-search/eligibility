---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Website is intended for use by users located in the United States.
  minimum_age:
    text: You must be at least 18 years old to use the Websites.
    value: '18'
  restricted_uses:
  - summary: Jurisdictions where restricted by law
    text: You may not use the Website in any jurisdiction where its contents or use is restricted or prohibited by law.
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
name: Eligible
provenance_date: '2026-11-09'
provider_name: Eligible
provider_slug: eligible
slug: eligible-eligibility
source_date: '2026-11-09'
source_filename: eligible-eligibility.yml
source_heading: Eligibility
source_page: https://account.eligible.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eligible\naid: eligible\nurl: https://account.eligible.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Website is intended for use by users located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Jurisdictions where restricted by law\n  text: You may not use the Website in any jurisdiction where its contents or use is restricted or prohibited by\n    law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Websites.\n"
source_yaml_url: https://artifacts.apis.io/eligible/eligibility/eligible-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Eligible's own page on 2026-11-09.
synthetic: false
tags:
- Billing
- Eligibility
- Healthcare
- Insurance
- Claims
- Health Insurance
---
