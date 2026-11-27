---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: Customers in Prohibited Jurisdictions, such as Cuba, Iran, North Korea, Syria, Crimea, Donetsk People's Republic (DNR), or Luhansk People's Republic regions of Ukraine, are not allowed to access or use the Services.
  entity_types:
  - text: If you are using the Service as an employee, agent, or contractor of a corporation or similar entity, you are representing and warranting that you have the authority to accept these terms on behalf of the entity.
    type: business
  - text: If the customer is a U.S. federal government department or agency, or contracting on behalf of such a department or agency, the Service is considered a Commercial Item
    type: government
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lumber
provenance_date: '2026-11-09'
provider_name: Lumber
provider_slug: lumber
slug: lumber-eligibility
source_date: '2026-11-09'
source_filename: lumber-eligibility.yml
source_heading: Eligibility
source_page: https://www.lumberfi.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lumber\naid: lumber\nurl: https://www.lumberfi.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: Customers in Prohibited Jurisdictions, such as Cuba, Iran, North Korea, Syria, Crimea, Donetsk People's\n    Republic (DNR), or Luhansk People's Republic regions of Ukraine, are not allowed to access or use the Services.\nentity_types:\n- type: business\n  text: If you are using the Service as an employee, agent, or contractor of a corporation or similar entity, you\n    are representing and warranting that you have the authority to accept these terms\
  \ on behalf of the entity.\n- type: government\n  text: If the customer is a U.S. federal government department or agency, or contracting on behalf of such a department\n    or agency, the Service is considered a Commercial Item\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lumber/eligibility/lumber-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 3 quoted statements, read from Lumber's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Payroll
- Workforce Management
- Software-as-a-Service
---
