---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Labdoor is intended for users in the United States. Those who choose to access the Site from locations outside of the United States of America do so on their own initiative and risk and are responsible for compliance with applicable local laws.
  entity_types:
  - text: The content on Labdoor is for your personal, individual use only, and not for commercial or external use.
    type: individual
  minimum_age:
    text: The Site is not intended for use by people who are younger than age 13. Do not use the Site if you are under 13.
    value: '13'
  restricted_uses:
  - summary: Export law violations
    text: You may not use or export any Content in violation of U.S. export laws and regulations.
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
name: LabDoor
provenance_date: '2026-11-09'
provider_name: LabDoor
provider_slug: labdoor
slug: labdoor-eligibility
source_date: '2026-11-09'
source_filename: labdoor-eligibility.yml
source_heading: Eligibility
source_page: https://labdoor.com/about/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LabDoor\naid: labdoor\nurl: https://labdoor.com/about/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Labdoor is intended for users in the United States. Those who choose to access the Site from locations outside\n    of the United States of America do so on their own initiative and risk and are responsible for compliance with\n    applicable local laws.\nentity_types:\n- type: individual\n  text: The content on Labdoor is for your personal, individual use only, and not for commercial or external use.\nrestricted_uses:\n- summary: Export law violations\n \
  \ text: You may not use or export any Content in violation of U.S. export laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is not intended for use by people who are younger than age 13. Do not use the Site if you are under\n    13.\n"
source_yaml_url: https://artifacts.apis.io/labdoor/eligibility/labdoor-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from LabDoor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Supplements
- Health
- Nutrition
- Product Testing
- Laboratory Testing
- Consumer Safety
- Certification
- Ratings
---
