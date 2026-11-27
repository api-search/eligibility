---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To the extent Client is an agency of or otherwise represents the United Stated federal government, (i) it hereby agrees that the Service qualifies as a “commercial product”
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: (b) is not located in (or a national of) a country that either is subject to a U.S. government embargo or has been designated by the U.S. government as a “state sponsor of terrorism”
  - summary: No PHI without HIPAA-compliant service
    text: Should Client input PHI into the Service without purchasing MasterControl’s HIPAA compliant Service, they shall be solely liable
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
name: MasterControl
provenance_date: '2026-11-10'
provider_name: MasterControl
provider_slug: mastercontrol
slug: mastercontrol-eligibility
source_date: '2026-11-10'
source_filename: mastercontrol-eligibility.yml
source_heading: Eligibility
source_page: https://www.mastercontrol.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MasterControl\naid: mastercontrol\nurl: https://www.mastercontrol.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: To the extent Client is an agency of or otherwise represents the United Stated federal government, (i) it\n    hereby agrees that the Service qualifies as a “commercial product”\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: (b) is not located in (or a national of) a country that either is subject to a U.S. government embargo or\n    has been designated by the U.S. government as\
  \ a “state sponsor of terrorism”\n- summary: No PHI without HIPAA-compliant service\n  text: Should Client input PHI into the Service without purchasing MasterControl’s HIPAA compliant Service, they\n    shall be solely liable\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mastercontrol/eligibility/mastercontrol-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from MasterControl's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Quality Management
- Manufacturing
- Life Sciences
- Compliance
- Document Management
- Regulatory
- Enterprise Software
---
