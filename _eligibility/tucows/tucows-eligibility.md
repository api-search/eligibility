---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: ACH payments are only accepted for banks in North America and from US$ accounts.
  entity_types:
  - text: Prior to registering domains, purchasing digital certificates or email boxes using OpenSRS, the Reseller must deposit funds into their reseller account.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: ACH geographic and currency limit
    text: ACH payments are only accepted for banks in North America and from US$ accounts.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Upon receipt, Tucows will assess your application and either authorize or decline your request.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tucows
provenance_date: '2026-11-10'
provider_name: Tucows
provider_slug: tucows
slug: tucows-eligibility
source_date: '2026-11-10'
source_filename: tucows-eligibility.yml
source_heading: Eligibility
source_page: https://opensrs.com/payment-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tucows\naid: tucows\nurl: https://opensrs.com/payment-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: ACH payments are only accepted for banks in North America and from US$ accounts.\nentity_types:\n- type: business\n  text: Prior to registering domains, purchasing digital certificates or email boxes using OpenSRS, the Reseller\n    must deposit funds into their reseller account.\nrestricted_uses:\n- summary: ACH geographic and currency limit\n  text: ACH payments are only accepted for banks in North America and from US$ accounts.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: true\n  text: Upon receipt, Tucows will assess your application and either authorize or decline your request.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tucows/eligibility/tucows-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Tucows's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Infrastructure
- Domains
- DNS
- SSL
- Email
- Registrar
- Telecommunications
---
