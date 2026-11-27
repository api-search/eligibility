---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: THE CUSTOMER, EITHER AS AN INDIVIDUAL OR, IF PURCHASED OR OTHERWISE ACQUIRED BY OR FOR AN ENTITY, AS AN ENTITY
    type: individual
  - text: IF PURCHASED OR OTHERWISE ACQUIRED BY OR FOR AN ENTITY, AS AN ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Similar-functionality products or services
    text: UNDER NO CIRCUMSTANCES MAY YOU USE THE SOFTWARE AS PART OF A PRODUCT OR SERVICE THAT PROVIDES SIMILAR FUNCTIONALITY TO THE SOFTWARE ITSELF.
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
name: GoReplay
provenance_date: '2026-11-09'
provider_name: GoReplay
provider_slug: goreplay
slug: goreplay-eligibility
source_date: '2026-11-09'
source_filename: goreplay-eligibility.yml
source_heading: Eligibility
source_page: https://github.com/probelabs/goreplay/blob/master/COMM-LICENSE
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GoReplay\naid: goreplay\nurl: https://github.com/probelabs/goreplay/blob/master/COMM-LICENSE\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: THE CUSTOMER, EITHER AS AN INDIVIDUAL OR, IF PURCHASED OR OTHERWISE ACQUIRED BY OR FOR AN ENTITY, AS AN\n    ENTITY\n- type: business\n  text: IF PURCHASED OR OTHERWISE ACQUIRED BY OR FOR AN ENTITY, AS AN ENTITY\nrestricted_uses:\n- summary: Similar-functionality products or services\n  text: UNDER NO CIRCUMSTANCES MAY YOU USE THE SOFTWARE AS PART OF A PRODUCT OR SERVICE THAT PROVIDES SIMILAR\
  \ FUNCTIONALITY\n    TO THE SOFTWARE ITSELF.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/goreplay/eligibility/goreplay-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from GoReplay's own page on 2026-11-09.
synthetic: false
tags:
- API Testing
- HTTP Traffic
- Load Testing
- Network Capture
- Open Source
- Traffic Replay
---
