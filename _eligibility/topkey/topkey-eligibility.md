---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are intended only for and may only be used by businesses domiciled in the United States.
  entity_types:
  - text: The Services are intended only for and may only be used by businesses domiciled in the United States.
    type: business
  minimum_age:
    text: Your use of the Site and/or Services is intended only for persons aged eighteen (18) years or older.
    value: '18'
  restricted_uses:
  - summary: Commercial use only
    text: the Services, including any provision of any financial products, are for commercial use only and not intended for personal, family, or household use.
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
name: TopKey
provenance_date: '2026-11-10'
provider_name: TopKey
provider_slug: topkey
slug: topkey-eligibility
source_date: '2026-11-10'
source_filename: topkey-eligibility.yml
source_heading: Eligibility
source_page: https://topkey.io/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TopKey\naid: topkey\nurl: https://topkey.io/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are intended only for and may only be used by businesses domiciled in the United States.\nentity_types:\n- type: business\n  text: The Services are intended only for and may only be used by businesses domiciled in the United States.\nrestricted_uses:\n- summary: Commercial use only\n  text: the Services, including any provision of any financial products, are for commercial use only and not intended\n    for personal, family, or household use.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Your use of the Site and/or Services is intended only for persons aged eighteen (18) years or older.\n"
source_yaml_url: https://artifacts.apis.io/topkey/eligibility/topkey-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from TopKey's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Expense Management
- Property Management
- Accounting
- Short-Term Rental
- Vacation Rentals
- Banking
- Bill Pay
- Corporate Cards
---
