---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This website is controlled and operated by TrueCar from its offices within the United States. TrueCar makes no representation that information or materials available on this website are appropriate or available for use in other locations, and access to this website from territories where its contents are illegal is prohibited.
  entity_types:
  - text: if you are a motor vehicle dealer, you may not use these services to obtain a True Cash Offer or True Cash Estimate on behalf of a customer.
    type: business
  minimum_age:
    text: provided that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: solely for your personal, non-commercial use
  - summary: Dealers barred from Sell Your Car/Trade
    text: 'By using these services, you represent, warrant, and covenant that you are not: (i) a motor vehicle dealer or (ii) listing a vehicle for sale in your capacity as an owner, employee, or representative of a motor vehicle dealer.'
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
name: TrueCar
provenance_date: '2026-11-10'
provider_name: TrueCar
provider_slug: truecar
slug: truecar-eligibility
source_date: '2026-11-10'
source_filename: truecar-eligibility.yml
source_heading: Eligibility
source_page: https://www.truecar.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TrueCar\naid: truecar\nurl: https://www.truecar.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This website is controlled and operated by TrueCar from its offices within the United States. TrueCar makes\n    no representation that information or materials available on this website are appropriate or available for use\n    in other locations, and access to this website from territories where its contents are illegal is prohibited.\nentity_types:\n- type: business\n  text: if you are a motor vehicle dealer, you may not use these services to obtain a True Cash Offer or True\
  \ Cash\n    Estimate on behalf of a customer.\nrestricted_uses:\n- summary: No commercial use\n  text: solely for your personal, non-commercial use\n- summary: Dealers barred from Sell Your Car/Trade\n  text: 'By using these services, you represent, warrant, and covenant that you are not: (i) a motor vehicle dealer\n    or (ii) listing a vehicle for sale in your capacity as an owner, employee, or representative of a motor vehicle\n    dealer.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: provided that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/truecar/eligibility/truecar-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from TrueCar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automotive
- Marketplace
- Car Buying
- Vehicle Pricing
- Dealers
- Consumer
- E-Commerce
---
