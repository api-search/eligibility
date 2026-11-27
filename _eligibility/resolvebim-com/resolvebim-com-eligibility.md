---
claim_count: 2
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: Customer shall not permit Authorized Users to access or use the Services in a U.S.-embargoed country (currently Cuba, Iran, North Korea, Sudan, Syria, or Crimea)
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing content
    text: Customer represents and warrants that any Customer Content hosted by Resolve as part of the Services will not (a) infringe or violate the rights of any third party; or (b) be deceptive, defamatory, obscene, or unlawful.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Resolve
provenance_date: '2026-11-10'
provider_name: Resolve
provider_slug: resolvebim-com
slug: resolvebim-com-eligibility
source_date: '2026-11-10'
source_filename: resolvebim-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.resolvebim.com/legal/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Resolve\naid: resolvebim-com\nurl: https://www.resolvebim.com/legal/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Customer shall not permit Authorized Users to access or use the Services in a U.S.-embargoed country (currently\n    Cuba, Iran, North Korea, Sudan, Syria, or Crimea)\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: Customer represents and warrants that any Customer Content hosted by Resolve as part of the Services will\n    not (a) infringe or violate the rights of any third\
  \ party; or (b) be deceptive, defamatory, obscene, or unlawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/resolvebim-com/eligibility/resolvebim-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Resolve's own page on 2026-11-10.
synthetic: false
tags:
- BIM
- VR Collaboration
- Integration
- Procore
- Autodesk
---
