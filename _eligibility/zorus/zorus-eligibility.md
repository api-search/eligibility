---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether as an individual user or on behalf of an organization ("you"), and/or your affiliated company or organization
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: you will not use the Services for any illegal or unauthorized purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zorus
provenance_date: '2026-11-10'
provider_name: Zorus
provider_slug: zorus
slug: zorus-eligibility
source_date: '2026-11-10'
source_filename: zorus-eligibility.yml
source_heading: Eligibility
source_page: https://www.zorustech.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zorus\naid: zorus\nurl: https://www.zorustech.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: whether as an individual user or on behalf of an organization (\"you\"), and/or your affiliated company or\n    organization\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: you will\
  \ not use the Services for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register to use the Services.\nminimum_age:\n  value: '13'\n  text: The Services are intended for users who are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/zorus/eligibility/zorus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Zorus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cybersecurity
- DNS Filtering
- Web Protection
- MSP
- MSSP
- Network Security
- Zero Trust
- Analytics
---
