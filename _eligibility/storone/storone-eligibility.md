---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: TO THE EXTENT YOU ENTER INTO THIS AGREEMENT ON BEHALF OF A LEGAL ENTITY, YOU REPRESENT THAT YOU ARE AUTHORIZED TO BIND SUCH LEGAL ENTITY.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: use the Software in any illegal manner or for unlawful purposes
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
name: StorONE
provenance_date: '2026-11-10'
provider_name: StorONE
provider_slug: storone
slug: storone-eligibility
source_date: '2026-11-10'
source_filename: storone-eligibility.yml
source_heading: Eligibility
source_page: https://www.storone.com/eula/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StorONE\naid: storone\nurl: https://www.storone.com/eula/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: TO THE EXTENT YOU ENTER INTO THIS AGREEMENT ON BEHALF OF A LEGAL ENTITY, YOU REPRESENT THAT YOU ARE AUTHORIZED\n    TO BIND SUCH LEGAL ENTITY.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: use the Software in any illegal manner or for unlawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/storone/eligibility/storone-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from StorONE's own page on 2026-11-10.
synthetic: false
tags:
- Storage
- Enterprise Storage
- Software-Defined Storage
- Data Management
- Infrastructure
- Block Storage
- File Storage
- Object Storage
- Backup
- Replication
- Snapshots
- Company
---
