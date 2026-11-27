---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms for use of the Services by an organization, you are agreeing on behalf of that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: AI features misuse
    text: must not use AI features to violate law or third-party rights
  - summary: Export restrictions
    text: Customer must not permit users to access or use the Services in violation of any U.S. export embargo, prohibition or restriction.
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
name: Peony
provenance_date: '2026-11-10'
provider_name: Peony
provider_slug: peony
slug: peony-eligibility
source_date: '2026-11-10'
source_filename: peony-eligibility.yml
source_heading: Eligibility
source_page: https://www.peony.ink/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Peony\naid: peony\nurl: https://www.peony.ink/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms for use of the Services by an organization, you are agreeing on behalf\n    of that organization.\nrestricted_uses:\n- summary: AI features misuse\n  text: must not use AI features to violate law or third-party rights\n- summary: Export restrictions\n  text: Customer must not permit users to access or use the Services in violation of any U.S. export embargo, prohibition\n    or restriction.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/peony/eligibility/peony-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Peony's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Virtual Data Room
- Document Sharing
- Due Diligence
- Mergers and Acquisitions
- Document Security
- E-Signature
- Software-as-a-Service
---
