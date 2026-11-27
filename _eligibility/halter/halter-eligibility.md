---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the parties acknowledge and agree that they are contracting for business purposes
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Cattle only
    text: Halter will not make available the Services where any Authorised User uses, or threatens to use, the Collars or the Services on any person or any animal other than cattle
  - summary: Own property or written permission
    text: use or access the Services and Hardware only on the Customer’s own property, or with the express written permission of the property owner
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
name: Halter
provenance_date: '2026-11-09'
provider_name: Halter
provider_slug: halter
slug: halter-eligibility
source_date: '2026-11-09'
source_filename: halter-eligibility.yml
source_heading: Eligibility
source_page: https://www.halterhq.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Halter\naid: halter\nurl: https://www.halterhq.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the parties acknowledge and agree that they are contracting for business purposes\nrestricted_uses:\n- summary: Cattle only\n  text: Halter will not make available the Services where any Authorised User uses, or threatens to use, the Collars\n    or the Services on any person or any animal other than cattle\n- summary: Own property or written permission\n  text: use or access the Services and Hardware\
  \ only on the Customer’s own property, or with the express written\n    permission of the property owner\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/halter/eligibility/halter-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Halter's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Deep Tech
- AgTech
- Agriculture
- Livestock
- Virtual Fencing
- IoT
- Precision Agriculture
- Pasture Management
- Cattle
---
