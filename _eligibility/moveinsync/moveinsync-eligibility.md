---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If your age is below that of 18 years, you will not be eligible to use this site
    value: '18'
  restricted_uses:
  - summary: Fraudulent use
    text: In case of fraudulent use of the site, MIS reserves the right to recover the damages and attorney’s fees from persons using this site fraudulently.
  - summary: Illegal or unauthorized use
    text: Illegal and/or unauthorized uses of this site are not permitted.
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
name: MoveInSync
provenance_date: '2026-11-10'
provider_name: MoveInSync
provider_slug: moveinsync
slug: moveinsync-eligibility
source_date: '2026-11-10'
source_filename: moveinsync-eligibility.yml
source_heading: Eligibility
source_page: https://moveinsync.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MoveInSync\naid: moveinsync\nurl: https://moveinsync.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fraudulent use\n  text: In case of fraudulent use of the site, MIS reserves the right to recover the damages and attorney’s fees\n    from persons using this site fraudulently.\n- summary: Illegal or unauthorized use\n  text: Illegal and/or unauthorized uses of this site are not permitted.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If your\
  \ age is below that of 18 years, you will not be eligible to use this site\n"
source_yaml_url: https://artifacts.apis.io/moveinsync/eligibility/moveinsync-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from MoveInSync's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Vertical Software
- Transportation
- Employee Commute
- Mobility
- Fleet Management
- Parking
- Workplace Management
- Logistics
---
