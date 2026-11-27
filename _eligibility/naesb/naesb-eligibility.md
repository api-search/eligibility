---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Members of NAESB and persons purchasing NAESB Standards are permitted to make reasonable use of these materials internally for certain limited purposes.
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Quoting material requires waiver
    text: Non-members that have not purchased NAESB copyright protected material and wish to quote such material in a regulatory filing or other publication must contact the NAESB office and request a copyright waiver.
  - source: https://www.naesb.org/pdf4/terms&conditions.pdf
    summary: Illegal or wrongful use
    text: The User agrees that it will not use NAESB's website, including its forums, for any illegal or wrongful purpose.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Upon request for access and approval by the NAESB Office, the requestor would have access to the NAESB copyright protected material for a limited time period.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NAESB
provenance_date: '2026-11-10'
provider_name: NAESB
provider_slug: naesb
slug: naesb-eligibility
source_date: '2026-11-10'
source_filename: naesb-eligibility.yml
source_heading: Eligibility
source_page: https://www.naesb.org/copyright.asp
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NAESB\naid: naesb\nurl: https://www.naesb.org/copyright.asp\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.naesb.org/copyright.asp\n  - https://www.naesb.org/pdf4/terms&conditions.pdf\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: Members of NAESB and persons purchasing NAESB Standards are permitted to make reasonable use of these materials\n    internally for certain limited purposes.\nrestricted_uses:\n- summary: Quoting material requires waiver\n  text: Non-members that have not purchased NAESB copyright protected material and wish to quote such material\
  \ in\n    a regulatory filing or other publication must contact the NAESB office and request a copyright waiver.\n- summary: Illegal or wrongful use\n  text: The User agrees that it will not use NAESB's website, including its forums, for any illegal or wrongful\n    purpose.\n  source: https://www.naesb.org/pdf4/terms&conditions.pdf\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Upon request for access and approval by the NAESB Office, the requestor would have access to the NAESB copyright\n    protected material for a limited time period.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/naesb/eligibility/naesb-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from NAESB's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United States
- Standards
- Utilities
- Electricity
- Gas
- Green Button
- Smart Metering
- Energy Markets
- Grid
---
