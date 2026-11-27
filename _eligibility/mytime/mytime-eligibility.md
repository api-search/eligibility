---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: MyTime makes no representations that the MyTime Service is appropriate or available for use in other locations. Those who access or use the MyTime Service from other jurisdictions do so at their own volition and are responsible for compliance with local law.
  entity_types:
  - text: Consumers interested in these services may book appointments for the Services
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraud or false information
    text: Submitting any inaccurate information, committing fraud or falsifying information in connection with your MyTime account;
  - summary: Competing or soliciting for competitors
    text: Using the MyTime Service or any of its contents to advertise or solicit, for any other commercial, political or religious purpose, or to compete, directly or indirectly with MyTime;
  verification:
    approval_required: null
    kyb: false
    kyc: false
    text: MyTime does not currently conduct criminal background checks or screenings of its users or Merchants. MyTime does not inquire into the backgrounds of its users or Merchants or attempt to verify the information provided by users or Merchants.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MyTime
provenance_date: '2026-11-10'
provider_name: MyTime
provider_slug: mytime
slug: mytime-eligibility
source_date: '2026-11-10'
source_filename: mytime-eligibility.yml
source_heading: Eligibility
source_page: https://www.mytime.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MyTime\naid: mytime\nurl: https://www.mytime.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: MyTime makes no representations that the MyTime Service is appropriate or available for use in other locations.\n    Those who access or use the MyTime Service from other jurisdictions do so at their own volition and are responsible\n    for compliance with local law.\nentity_types:\n- type: individual\n  text: Consumers interested in these services may book appointments for the Services\nrestricted_uses:\n- summary: Fraud or false information\n  text: Submitting any inaccurate\
  \ information, committing fraud or falsifying information in connection with your\n    MyTime account;\n- summary: Competing or soliciting for competitors\n  text: Using the MyTime Service or any of its contents to advertise or solicit, for any other commercial, political\n    or religious purpose, or to compete, directly or indirectly with MyTime;\nverification:\n  kyc: false\n  kyb: false\n  approval_required: null\n  text: MyTime does not currently conduct criminal background checks or screenings of its users or Merchants. MyTime\n    does not inquire into the backgrounds of its users or Merchants or attempt to verify the information provided\n    by users or Merchants.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mytime/eligibility/mytime-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from MyTime's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Scheduling
- Appointments
- Booking
- Point-of-Sale
- Payments
- Retail
- Franchise
- Business Management
- Salon Software
---
