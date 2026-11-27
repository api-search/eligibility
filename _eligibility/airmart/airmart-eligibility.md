---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Only credit cards issued by the United States and Canada financial institutions are accepted; the use of international credit cards for transactions on Airmart is prohibited.
  entity_types:
  - text: If you are signing up for the Services on behalf of your employer, your employer shall be the Store Owner.
    type: business
  minimum_age:
    text: 'You must be the older of: (i) 18 years, or (ii) at least the age of majority in the jurisdiction where you reside and from which you use the Services to open an Account.'
    value: 18 years or age of majority
  restricted_uses:
  - summary: Compliance with laws
    text: You agree that you will not violate any laws in connection with your use of the Services.
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
name: Airmart
provenance_date: '2026-11-09'
provider_name: Airmart
provider_slug: airmart
slug: airmart-eligibility
source_date: '2026-11-09'
source_filename: airmart-eligibility.yml
source_heading: Eligibility
source_page: https://shop.goairmart.com/en/s/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airmart\naid: airmart\nurl: https://shop.goairmart.com/en/s/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Only credit cards issued by the United States and Canada financial institutions are accepted; the use of\n    international credit cards for transactions on Airmart is prohibited.\nentity_types:\n- type: business\n  text: If you are signing up for the Services on behalf of your employer, your employer shall be the Store Owner.\nrestricted_uses:\n- summary: Compliance with laws\n  text: You agree that you will not violate any laws in connection with your use of the Services.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 18 years or age of majority\n  text: 'You must be the older of: (i) 18 years, or (ii) at least the age of majority in the jurisdiction where\n    you reside and from which you use the Services to open an Account.'\n"
source_yaml_url: https://artifacts.apis.io/airmart/eligibility/airmart-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Airmart's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- Commerce
- Online Storefront
- Social Commerce
- Payments
- Delivery
- Small Business
- Food
- United States
- Company
---
