---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: certain features may be restricted or unavailable in specific jurisdictions due to local laws or regulatory constraints
  entity_types:
  - text: You may use the Services for your personal and business use
    type: individual
  - text: or for internal business purposes in the entity that you represent
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraudulent or illegal activity
    text: to promote, conduct, or contribute to fraudulent, obscene, pornographic, inappropriate or illegal activities
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
name: Craftt
provenance_date: '2026-11-09'
provider_name: Craftt
provider_slug: craftt
slug: craftt-eligibility
source_date: '2026-11-09'
source_filename: craftt-eligibility.yml
source_heading: Eligibility
source_page: https://www.craftt.xyz/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Craftt\naid: craftt\nurl: https://www.craftt.xyz/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: certain features may be restricted or unavailable in specific jurisdictions due to local laws or regulatory\n    constraints\nentity_types:\n- type: individual\n  text: You may use the Services for your personal and business use\n- type: business\n  text: or for internal business purposes in the entity that you represent\nrestricted_uses:\n- summary: Fraudulent or illegal activity\n  text: to promote, conduct, or contribute to fraudulent, obscene, pornographic,\
  \ inappropriate or illegal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/craftt/eligibility/craftt-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Craftt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Tokenization
- Lending
- Fintech
---
