---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Website and the Services, you attest that you are at least 18 years old.
    type: individual
  minimum_age:
    text: By using the Website and the Services, you attest that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You may not access, download, use or export the Website or Services in violation of United States export laws or regulations
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
name: Cnote
provenance_date: '2026-11-09'
provider_name: Cnote
provider_slug: cnote
slug: cnote-eligibility
source_date: '2026-11-09'
source_filename: cnote-eligibility.yml
source_heading: Eligibility
source_page: https://www.mycnote.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cnote\naid: cnote\nurl: https://www.mycnote.com/legal/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Website and the Services, you attest that you are at least 18 years old.\nrestricted_uses:\n- summary: Export restrictions\n  text: You may not access, download, use or export the Website or Services in violation of United States export\n    laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Website and the Services,\
  \ you attest that you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/cnote/eligibility/cnote-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cnote's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Impact Investing
- Cash Management
- Fixed Income
- Community Development
---
