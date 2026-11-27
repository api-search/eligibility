---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Sites are for U.S. residents only, unless indicated otherwise.
  entity_types:
  - text: intended for your personal or internal business use
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automated queries and metasearching
    text: Automated queries may never be sent by you to our Services unless InterOperate LLC has provided you with express written permission.
  - summary: Commercial solicitation
    text: use the Services to advertise or perform any commercial solicitation
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
name: InterOperate
provenance_date: '2026-11-09'
provider_name: InterOperate
provider_slug: inter-operate
slug: inter-operate-eligibility
source_date: '2026-11-09'
source_filename: inter-operate-eligibility.yml
source_heading: Eligibility
source_page: https://inter-operate.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: InterOperate\naid: inter-operate\nurl: https://inter-operate.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Sites are for U.S. residents only, unless indicated otherwise.\nentity_types:\n- type: business\n  text: intended for your personal or internal business use\nrestricted_uses:\n- summary: Automated queries and metasearching\n  text: Automated queries may never be sent by you to our Services unless InterOperate LLC has provided you with\n    express written permission.\n- summary: Commercial solicitation\n  text: use the Services to advertise or perform\
  \ any commercial solicitation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/inter-operate/eligibility/inter-operate-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from InterOperate's own page on 2026-11-09.
synthetic: false
tags:
- Integration
- Automation
- iPaaS
- Enterprise
- Workflows
---
