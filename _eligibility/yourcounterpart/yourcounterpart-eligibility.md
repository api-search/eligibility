---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Platform and all Content and other Offerings are for use by individuals 18 years of age and older for their own personal use.
    type: individual
  - text: If You are entering into this Agreement on behalf of an entity or organization, you represent and warrant to CPI You are authorized to bind that entity or organization to this Agreement
    type: business
  minimum_age:
    text: individuals 18 years of age and older
    value: '18'
  restricted_uses:
  - summary: No unsolicited communications or harvesting emails
    text: to harvest or collect e-mail addresses or other contact information of other users by electronic or other means for the purposes of sending unsolicited e-mails or other unsolicited communications
  - source: https://yourcounterpart.com/api-terms
    summary: Commercial insurance business only
    text: You may only use and access the API Software to conduct or otherwise transact commercial insurance business.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All Accounts are issued at the sole discretion of CPI.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Yourcounterpart
provenance_date: '2026-11-10'
provider_name: Yourcounterpart
provider_slug: yourcounterpart
slug: yourcounterpart-eligibility
source_date: '2026-11-10'
source_filename: yourcounterpart-eligibility.yml
source_heading: Eligibility
source_page: https://yourcounterpart.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yourcounterpart\naid: yourcounterpart\nurl: https://yourcounterpart.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://yourcounterpart.com/api-terms\n  - https://yourcounterpart.com/terms\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Platform and all Content and other Offerings are for use by individuals 18 years of age and older for\n    their own personal use.\n- type: business\n  text: If You are entering into this Agreement on behalf of an entity or organization, you represent and warrant\n    to CPI You are authorized to bind that entity\
  \ or organization to this Agreement\nrestricted_uses:\n- summary: No unsolicited communications or harvesting emails\n  text: to harvest or collect e-mail addresses or other contact information of other users by electronic or other\n    means for the purposes of sending unsolicited e-mails or other unsolicited communications\n- summary: Commercial insurance business only\n  text: You may only use and access the API Software to conduct or otherwise transact commercial insurance business.\n  source: https://yourcounterpart.com/api-terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All Accounts are issued at the sole discretion of CPI.\nminimum_age:\n  value: '18'\n  text: individuals 18 years of age and older\n"
source_yaml_url: https://artifacts.apis.io/yourcounterpart/eligibility/yourcounterpart-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Yourcounterpart's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Insurtech
- Management Liability
- Professional Liability
- Underwriting
- Quote and Bind
- Small Business
- API Partner
- Brokerage
- Financial Services
---
