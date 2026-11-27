---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Within the US, we provide Services through Spectinga Inc, and within the Netherlands, through Spectinga BV.
  entity_types:
  - text: only representatives of equipment dealerships are eligible to access and participate in our marketplace
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Resale of machines only
    text: Each eligible participant agrees to only use this Website and the Services for the resale of Machines only.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: After receiving your online application, we will determine if you meet the eligible participants criteria set out above, along with any additional criteria we may apply
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Spectinga
provenance_date: '2026-11-10'
provider_name: Spectinga
provider_slug: spectinga
slug: spectinga-eligibility
source_date: '2026-11-10'
source_filename: spectinga-eligibility.yml
source_heading: Eligibility
source_page: https://spectinga.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spectinga\naid: spectinga\nurl: https://spectinga.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Within the US, we provide Services through Spectinga Inc, and within the Netherlands, through Spectinga\n    BV.\nentity_types:\n- type: business\n  text: only representatives of equipment dealerships are eligible to access and participate in our marketplace\nrestricted_uses:\n- summary: Resale of machines only\n  text: Each eligible participant agrees to only use this Website and the Services for the resale of Machines only.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: true\n  text: After receiving your online application, we will determine if you meet the eligible participants criteria\n    set out above, along with any additional criteria we may apply\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/spectinga/eligibility/spectinga-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Spectinga's own page on 2026-11-10.
synthetic: false
tags:
- Marketplace
- Agriculture
- Construction
- Machinery
- B2B
---
