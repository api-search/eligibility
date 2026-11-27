---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be 18 years of age or older and located in the United States to use the Website.
  entity_types:
  - text: Vouch is a business insurance provider intended for use by businesses and organizations and not for consumer purposes.
    type: business
  minimum_age:
    text: You must be 18 years of age or older and located in the United States to use the Website.
    value: '18'
  restricted_uses:
  - summary: Sanctioned payments
    text: To send payments directly or indirectly to, or for the benefit of, any person or entity that is (a) located in any country or jurisdiction that is subject to U.S. economic sanctions
  - summary: Commercial solicitation of users
    text: To solicit, for commercial purposes, any users of the Website.
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
name: Vouch
provenance_date: '2026-11-10'
provider_name: Vouch
provider_slug: vouch-co
slug: vouch-co-eligibility
source_date: '2026-11-10'
source_filename: vouch-co-eligibility.yml
source_heading: Eligibility
source_page: https://www.vouch.us/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vouch\naid: vouch-co\nurl: https://www.vouch.us/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be 18 years of age or older and located in the United States to use the Website.\nentity_types:\n- type: business\n  text: Vouch is a business insurance provider intended for use by businesses and organizations and not for consumer\n    purposes.\nrestricted_uses:\n- summary: Sanctioned payments\n  text: To send payments directly or indirectly to, or for the benefit of, any person or entity that is (a) located\n    in any country or jurisdiction that is\
  \ subject to U.S. economic sanctions\n- summary: Commercial solicitation of users\n  text: To solicit, for commercial purposes, any users of the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older and located in the United States to use the Website.\n"
source_yaml_url: https://artifacts.apis.io/vouch-co/eligibility/vouch-co-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Vouch's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Business Insurance
- Commercial Insurance
- Insurtech
- Startup Insurance
- Directors and Officers
- Errors And Omissions
- Cyber Insurance
- Employment Practices Liability
- General Liability
- Embedded Insurance
- Risk Management
- Brokerage
- Underwriting
- Venture Ecosystem
---
