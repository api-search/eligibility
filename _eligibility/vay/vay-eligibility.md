---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: hold a valid driver’s license issued by a state in the United States, or, at Vay’s sole discretion, a valid driver’s license issued by another jurisdiction approved by Vay from time to time
  entity_types:
  - text: The person applying to register or registered on Vay’s website(s) or mobile app(s) as the User
    type: individual
  minimum_age:
    text: be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No rideshare or taxi use
    text: for the primary business purpose of transporting people or operating a rideshare or taxi service
  - summary: No delivery use
    text: for the primary business purpose of transporting goods including food delivery
  - summary: No driving under influence
    text: by any person who is under the influence of (i) alcohol or (ii) any drug or medication under the effects of which the operation of a vehicle is prohibited or not recommended
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We may or may not approve your Sign Up Process at our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vay
provenance_date: '2026-11-10'
provider_name: Vay
provider_slug: vay
slug: vay-eligibility
source_date: '2026-11-10'
source_filename: vay-eligibility.yml
source_heading: Eligibility
source_page: https://vay.io/legal/terms-and-conditions-for-customers-web/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vay\naid: vay\nurl: https://vay.io/legal/terms-and-conditions-for-customers-web/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: hold a valid driver’s license issued by a state in the United States, or, at Vay’s sole discretion, a valid\n    driver’s license issued by another jurisdiction approved by Vay from time to time\nentity_types:\n- type: individual\n  text: The person applying to register or registered on Vay’s website(s) or mobile app(s) as the User\nrestricted_uses:\n- summary: No rideshare or taxi use\n  text: for the primary business purpose of transporting\
  \ people or operating a rideshare or taxi service\n- summary: No delivery use\n  text: for the primary business purpose of transporting goods including food delivery\n- summary: No driving under influence\n  text: by any person who is under the influence of (i) alcohol or (ii) any drug or medication under the effects\n    of which the operation of a vehicle is prohibited or not recommended\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We may or may not approve your Sign Up Process at our sole discretion.\nminimum_age:\n  value: '18'\n  text: be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/vay/eligibility/vay-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Vay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mobility
- Teledriving
- Remote Driving
- Car Rental
- Automotive
- Transportation
---
