---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: means a natural person, who is not subscribing to or using the Services for commercial purposes.
    type: individual
  - text: The Paid Service Plans are permitted for use in professional and commercial settings, such as training, surveys and events, both for internal and external audiences.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Free plans are non-commercial only
    text: In our Free Service Plans, the License permits use for non-commercial purposes only.
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
name: Kahoot!
provenance_date: '2026-11-09'
provider_name: Kahoot!
provider_slug: kahoot
slug: kahoot-eligibility
source_date: '2026-11-09'
source_filename: kahoot-eligibility.yml
source_heading: Eligibility
source_page: https://trust.kahoot.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kahoot!\naid: kahoot\nurl: https://trust.kahoot.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: means a natural person, who is not subscribing to or using the Services for commercial purposes.\n- type: business\n  text: The Paid Service Plans are permitted for use in professional and commercial settings, such as training,\n    surveys and events, both for internal and external audiences.\nrestricted_uses:\n- summary: Free plans are non-commercial only\n  text: In our Free Service Plans, the License permits\
  \ use for non-commercial purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kahoot/eligibility/kahoot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Kahoot!'s own page on 2026-11-09.
synthetic: false
tags:
- Game-Based Learning
- Education
- Quiz
- Engagement
- Enterprise Learning
- Reporting
- OAuth
- Authentication
---
