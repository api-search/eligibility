---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: you are not a citizen of, resident of, or located in any country or territory that is subject to any such laws (including, without limitation, Cuba, Iran, North Korea, or Syria)
  entity_types:
  - text: You must be at least 18 years old to use the Site or the Services.
    type: individual
  - text: Where you use the Site or Services in the course of a business
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Site or the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive content and conduct
    text: transmit anything that is illegal, abusive, defamatory, harassing, harmful to reputation, pornographic, indecent, profane, obscene, hateful, racist, or otherwise objectionable
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Registration is subject to approval by us in all cases, and we reserve the right, in our sole and absolute discretion, to decline any application for registration, without giving a reason.
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
name: pCloud
provenance_date: '2026-11-10'
provider_name: pCloud
provider_slug: pcloud
slug: pcloud-eligibility
source_date: '2026-11-10'
source_filename: pcloud-eligibility.yml
source_heading: Eligibility
source_page: https://www.pcloud.com/terms_and_conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pCloud\naid: pcloud\nurl: https://www.pcloud.com/terms_and_conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: you are not a citizen of, resident of, or located in any country or territory that is subject to any such\n    laws (including, without limitation, Cuba, Iran, North Korea, or Syria)\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Site or the Services.\n- type: business\n  text: Where you use the Site or Services in the course of a business\nrestricted_uses:\n- summary: Unlawful or abusive content\
  \ and conduct\n  text: transmit anything that is illegal, abusive, defamatory, harassing, harmful to reputation, pornographic,\n    indecent, profane, obscene, hateful, racist, or otherwise objectionable\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Registration is subject to approval by us in all cases, and we reserve the right, in our sole and absolute\n    discretion, to decline any application for registration, without giving a reason.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Site or the Services.\n"
source_yaml_url: https://artifacts.apis.io/pcloud/eligibility/pcloud-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from pCloud's own page on 2026-11-10.
synthetic: false
tags:
- Cloud Storage
- File Sync
- Backup
- Security
- Collaboration
---
