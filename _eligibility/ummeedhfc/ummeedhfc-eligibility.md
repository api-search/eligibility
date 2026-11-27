---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You means the individual accessing or using the Service
    type: individual
  - text: or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: US sanctions and restricted parties
    text: You represent and warrant that (i) You are not located in a country that is subject to the United States government embargo
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
name: Ummeed Housing Finance
provenance_date: '2026-11-10'
provider_name: Ummeed Housing Finance
provider_slug: ummeedhfc
slug: ummeedhfc-eligibility
source_date: '2026-11-10'
source_filename: ummeedhfc-eligibility.yml
source_heading: Eligibility
source_page: https://www.ummeedhfc.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ummeed Housing Finance\naid: ummeedhfc\nurl: https://www.ummeedhfc.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service\n- type: business\n  text: or the company, or other legal entity on behalf of which such individual is accessing or using the Service\nrestricted_uses:\n- summary: US sanctions and restricted parties\n  text: You represent and warrant that (i) You are not located in a country that is subject to the United States\n    government embargo\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ummeedhfc/eligibility/ummeedhfc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Ummeed Housing Finance's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Housing Finance
- Home Loans
- Lending
- Financial Services
- MSME
- India
---
