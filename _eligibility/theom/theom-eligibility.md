---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export to sanctioned parties
    text: export the Subscription Services or technical data or any copy, portions, or direct product thereof to anyone on the U.S. Treasury Department’s list of Specially Designated Nationals or the U.S. Commerce Department’s Table of Denial Orders
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
name: Theom
provenance_date: '2026-11-10'
provider_name: Theom
provider_slug: theom
slug: theom-eligibility
source_date: '2026-11-10'
source_filename: theom-eligibility.yml
source_heading: Eligibility
source_page: https://theom.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Theom\naid: theom\nurl: https://theom.ai/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export to sanctioned parties\n  text: export the Subscription Services or technical data or any copy, portions, or direct product thereof to anyone\n    on the U.S. Treasury Department’s list of Specially Designated Nationals or the U.S. Commerce Department’s Table\n    of Denial Orders\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/theom/eligibility/theom-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Theom's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Security
- Data Governance
- Compliance
- DSPM
- Artificial Intelligence
- Cloud Security
- Privacy
---
