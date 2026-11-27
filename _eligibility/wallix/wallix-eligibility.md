---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any User of the Website, regardless of their status (professional or individual)
    type: individual
  - text: Any User of the Website, regardless of their status (professional or individual)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Hyperlinking restrictions
    text: Any hyperlink directing to the Website must only point to the homepage and must open in a new window.
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
name: WALLIX
provenance_date: '2026-11-10'
provider_name: WALLIX
provider_slug: wallix
slug: wallix-eligibility
source_date: '2026-11-10'
source_filename: wallix-eligibility.yml
source_heading: Eligibility
source_page: https://www.wallix.com/legal-notice/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WALLIX\naid: wallix\nurl: https://www.wallix.com/legal-notice/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any User of the Website, regardless of their status (professional or individual)\n- type: business\n  text: Any User of the Website, regardless of their status (professional or individual)\nrestricted_uses:\n- summary: Hyperlinking restrictions\n  text: Any hyperlink directing to the Website must only point to the homepage and must open in a new window.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wallix/eligibility/wallix-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from WALLIX's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Privileged Access Management
- Identity
- Cybersecurity
- Enterprise
- Cloud
---
