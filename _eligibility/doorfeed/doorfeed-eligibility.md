---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accepting these T&Cs, the individual represents and warrants that he/she (i) is a real estate professional, or (ii) is duly authorized to act on behalf of a real estate professional, as applicable.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Real estate professionals only
    text: Access to the Platform is restricted to real estate professionals, such as investors, asset managers, developers, brokers, valuers, property managers.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Users will be required to create an account to access the Platform, and each authorised individual of the User will have to create a sub-account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DoorFeed
provenance_date: '2026-11-09'
provider_name: DoorFeed
provider_slug: doorfeed
slug: doorfeed-eligibility
source_date: '2026-11-09'
source_filename: doorfeed-eligibility.yml
source_heading: Eligibility
source_page: https://www.doorfeed.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DoorFeed\naid: doorfeed\nurl: https://www.doorfeed.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By accepting these T&Cs, the individual represents and warrants that he/she (i) is a real estate professional,\n    or (ii) is duly authorized to act on behalf of a real estate professional, as applicable.\nrestricted_uses:\n- summary: Real estate professionals only\n  text: Access to the Platform is restricted to real estate professionals, such as investors, asset managers, developers,\n    brokers, valuers,\
  \ property managers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Users will be required to create an account to access the Platform, and each authorised individual of the\n    User will have to create a sub-account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/doorfeed/eligibility/doorfeed-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from DoorFeed's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- PropTech
- Real Estate
- Investment
- Residential
- Property Data
- France
- United Kingdom
---
