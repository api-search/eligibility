---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The page does not list countries served. It says Client shall not export or re-export the Services to embargoed countries or restricted entities.
  entity_types:
  - text: '"Services" means use of the features and functionality of the ResQ Platform by businesses'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No illegal or harmful use
    text: Client shall not (a) use, or permit the use of, the Services for an illegal purpose, criminal offense, infringement of any intellectual property rights, harassment
  - summary: No sharing of login credentials
    text: Login credentials are for the sole use of the specific individual to whom they are assigned ("Named User") and may not be shared with or used by any other person.
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
name: Res
provenance_date: '2026-11-10'
provider_name: Res
provider_slug: res
slug: res-eligibility
source_date: '2026-11-10'
source_filename: res-eligibility.yml
source_heading: Eligibility
source_page: https://www.getresq.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Res\naid: res\nurl: https://www.getresq.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The page does not list countries served. It says Client shall not export or re-export the Services to embargoed\n    countries or restricted entities.\nentity_types:\n- type: business\n  text: '\"Services\" means use of the features and functionality of the ResQ Platform by businesses'\nrestricted_uses:\n- summary: No illegal or harmful use\n  text: Client shall not (a) use, or permit the use of, the Services for an illegal purpose, criminal offense, infringement\n    of any\
  \ intellectual property rights, harassment\n- summary: No sharing of login credentials\n  text: Login credentials are for the sole use of the specific individual to whom they are assigned (\"Named User\")\n    and may not be shared with or used by any other person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/res/eligibility/res-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Res's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Facilities Management
- Field Service Management
- Work Orders
- Trade
- Maintenance
- Hospitality
- Restaurant
- Software-as-a-Service
- Vendor Management
---
