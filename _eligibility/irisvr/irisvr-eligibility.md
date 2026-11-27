---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: If you use the Software on behalf of a company, organization, or other entity, then "you" includes you and that entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Government and military use
    text: The Software, Services and Documentation may not be used by the U.S. Government or by any governmental entity or military organization in any jurisdiction without express prior written consent from Licensor.
  - summary: Export and prohibited purposes
    text: You agree to comply fully with all laws and regulations of the United States and other countries to assure that none of the Software, Services nor Documentation are (1) exported, directly or indirectly, in violation of applicable law
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
name: IrisVR
provenance_date: '2026-11-09'
provider_name: IrisVR
provider_slug: irisvr
slug: irisvr-eligibility
source_date: '2026-11-09'
source_filename: irisvr-eligibility.yml
source_heading: Eligibility
source_page: https://irisvr.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: IrisVR\naid: irisvr\nurl: https://irisvr.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo\nentity_types:\n- type: business\n  text: If you use the Software on behalf of a company, organization, or other entity, then \"you\" includes you and\n    that entity.\nrestricted_uses:\n- summary: Government and military use\n  text: The Software, Services and Documentation may not be used by the U.S. Government or by any governmental entity\n    or military organization in any jurisdiction without express\
  \ prior written consent from Licensor.\n- summary: Export and prohibited purposes\n  text: You agree to comply fully with all laws and regulations of the United States and other countries to assure\n    that none of the Software, Services nor Documentation are (1) exported, directly or indirectly, in violation\n    of applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/irisvr/eligibility/irisvr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from IrisVR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise Software
- Virtual Reality
- Augmented Reality
- Architecture Engineering Construction
- BIM
- 3D Visualization
- Collaboration
---
