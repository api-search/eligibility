---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Pexip Cloud Service may not be available in certain locations and to certain Persons in order to comply with applicable laws and regulations.
  entity_types:
  - text: Pexip Inc., a corporation incorporated under the laws of the State of Delaware, shall be the contracting Party
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and embargo restrictions
    text: None of the underlying information or technology derived from or related to the Pexip Deliverables shall be downloaded or otherwise exported or re-exported
  - summary: Unlawful or prohibited Content
    text: 'The Customer will not, and warrants that its Representatives will not publish, post, upload, record, link to, or otherwise distribute or transmit any Content that:'
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
name: Pexip
provenance_date: '2026-11-10'
provider_name: Pexip
provider_slug: pexip
slug: pexip-eligibility
source_date: '2026-11-10'
source_filename: pexip-eligibility.yml
source_heading: Eligibility
source_page: https://www.pexip.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pexip\naid: pexip\nurl: https://www.pexip.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Pexip Cloud Service may not be available in certain locations and to certain Persons in order to comply\n    with applicable laws and regulations.\nentity_types:\n- type: business\n  text: Pexip Inc., a corporation incorporated under the laws of the State of Delaware, shall be the contracting\n    Party\nrestricted_uses:\n- summary: Export and embargo restrictions\n  text: None of the underlying information or technology derived from or related to the Pexip Deliverables shall\n\
  \    be downloaded or otherwise exported or re-exported\n- summary: Unlawful or prohibited Content\n  text: 'The Customer will not, and warrants that its Representatives will not publish, post, upload, record, link\n    to, or otherwise distribute or transmit any Content that:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pexip/eligibility/pexip-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Pexip's own page on 2026-11-10.
synthetic: false
tags:
- Video
- Communications
- Cloud
- Security
- Enterprise
---
