---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING IN TO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal Unlimited plan use
    text: Personal Unlimited plans are priced for and intended for normal personal use only.
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
name: OpenDrive
provenance_date: '2026-11-10'
provider_name: OpenDrive
provider_slug: opendrive
slug: opendrive-eligibility
source_date: '2026-11-10'
source_filename: opendrive-eligibility.yml
source_heading: Eligibility
source_page: https://www.opendrive.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenDrive\naid: opendrive\nurl: https://www.opendrive.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING IN TO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: Personal Unlimited plan use\n  text: Personal Unlimited plans are priced for and intended for normal personal use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/opendrive/eligibility/opendrive-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from OpenDrive's own page on 2026-11-10.
synthetic: false
tags:
- Cloud Storage
- Backup
- File Sync
- Collaboration
---
