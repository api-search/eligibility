---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for use by persons over the age of 18 who are legal residents of the United States.
  minimum_age:
    text: The Site is intended for use by persons over the age of 18 who are legal residents of the United States.
    value: '18'
  restricted_uses:
  - summary: Unlawful export or use outside US law
    text: You may not use or export or re-export any portion of the Site in violation of any applicable laws or regulations, including United States export laws and regulations.
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
name: Mission Lane
provenance_date: '2026-11-10'
provider_name: Mission Lane
provider_slug: mission-lane
slug: mission-lane-eligibility
source_date: '2026-11-10'
source_filename: mission-lane-eligibility.yml
source_heading: Eligibility
source_page: https://www.missionlane.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mission Lane\naid: mission-lane\nurl: https://www.missionlane.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for use by persons over the age of 18 who are legal residents of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful export or use outside US law\n  text: You may not use or export or re-export any portion of the Site in violation of any applicable laws or regulations,\n    including United States export laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: The Site is intended for use by persons over the age of 18 who are legal residents of the United States.\n"
source_yaml_url: https://artifacts.apis.io/mission-lane/eligibility/mission-lane-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Mission Lane's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Credit
- Credit Cards
- Fintech
- Consumer Finance
- Financial Services
- Lending
- Payments
---
