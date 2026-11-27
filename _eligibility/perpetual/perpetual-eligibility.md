---
claim_count: 2
description: ''
doc:
  countries:
    excluded:
    - US
    served:
    - AU
    - NZ
    - SG
    - GB
    text: The information is provided for Australian residents or citizens who are currently located in Australia, and New Zealand residents or citizens who are currently located in New Zealand only. Singapore and UK/EU sections are intended for residents of those jurisdictions. This website cannot be accessed in the United States of America or its territories nor possessions, nor be accessed by US persons.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: General information only, not advice
    text: The information contained in this website should be used as general information only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Perpetual
provenance_date: '2026-11-10'
provider_name: Perpetual
provider_slug: perpetual
slug: perpetual-eligibility
source_date: '2026-11-10'
source_filename: perpetual-eligibility.yml
source_heading: Eligibility
source_page: https://www.perpetual.com.au/privacy-policy/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Perpetual\naid: perpetual\nurl: https://www.perpetual.com.au/privacy-policy/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  - NZ\n  - SG\n  - GB\n  excluded:\n  - US\n  text: The information is provided for Australian residents or citizens who are currently located in Australia,\n    and New Zealand residents or citizens who are currently located in New Zealand only. Singapore and UK/EU sections\n    are intended for residents of those jurisdictions. This website cannot be accessed in the United States of America\n    or its territories nor possessions, nor be accessed by US\
  \ persons.\nentity_types: []\nrestricted_uses:\n- summary: General information only, not advice\n  text: The information contained in this website should be used as general information only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/perpetual/eligibility/perpetual-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Perpetual's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Asset Management
- Wealth Management
- Corporate Trust
- Trustee Services
- Australia
---
