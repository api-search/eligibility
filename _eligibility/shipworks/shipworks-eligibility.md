---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If a Provider account is established for a business or other entity, the person establishing the account represents that he or she has all necessary authority to establish an account with Provider on behalf of the business or other entity who is the responsible account holder.
    type: business
  minimum_age:
    text: 'You must be the older of: (i) 18 years, or (ii) at least the age of majority in the jurisdiction where you reside and from which you use the Services to open an account.'
    value: 18 years
  restricted_uses:
  - summary: Ineligible shipping items
    text: Ineligible items include (i) any goods which are prohibited by law or regulation, or any hazardous materials, dangerous goods or other items which are subject to regulation by Title 49 of the U.S. Code of Federal Regulations
  - summary: Prohibited activities
    text: 'You may not use the Site, Services, or Software for activities that: violate any law, statute, ordinance or regulation'
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
name: ShipWorks
provenance_date: '2026-11-10'
provider_name: ShipWorks
provider_slug: shipworks
slug: shipworks-eligibility
source_date: '2026-11-10'
source_filename: shipworks-eligibility.yml
source_heading: Eligibility
source_page: https://www.shipworks.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ShipWorks\naid: shipworks\nurl: https://www.shipworks.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If a Provider account is established for a business or other entity, the person establishing the account\n    represents that he or she has all necessary authority to establish an account with Provider on behalf of the\n    business or other entity who is the responsible account holder.\nrestricted_uses:\n- summary: Ineligible shipping items\n  text: Ineligible items include (i) any goods which\
  \ are prohibited by law or regulation, or any hazardous materials,\n    dangerous goods or other items which are subject to regulation by Title 49 of the U.S. Code of Federal Regulations\n- summary: Prohibited activities\n  text: 'You may not use the Site, Services, or Software for activities that: violate any law, statute, ordinance\n    or regulation'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 18 years\n  text: 'You must be the older of: (i) 18 years, or (ii) at least the age of majority in the jurisdiction where\n    you reside and from which you use the Services to open an account.'\n"
source_yaml_url: https://artifacts.apis.io/shipworks/eligibility/shipworks-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ShipWorks's own page on 2026-11-10.
synthetic: false
tags:
- Shipping
- E-Commerce
- Logistics
- Software
- Integration
---
