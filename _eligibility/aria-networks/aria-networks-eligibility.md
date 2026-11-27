---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: access or use the Website from a country sanctioned by the United States government
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THIS AGREEMENT
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use from sanctioned countries
    text: access or use the Website from a country sanctioned by the United States government
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
name: Aria Networks
provenance_date: '2026-11-09'
provider_name: Aria Networks
provider_slug: aria-networks
slug: aria-networks-eligibility
source_date: '2026-11-09'
source_filename: aria-networks-eligibility.yml
source_heading: Eligibility
source_page: https://arianetworks.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aria Networks\naid: aria-networks\nurl: https://arianetworks.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: access or use the Website from a country sanctioned by the United States government\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THIS AGREEMENT\nrestricted_uses:\n- summary: Use from sanctioned countries\n  text: access or use the Website from a country sanctioned by the United States government\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aria-networks/eligibility/aria-networks-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Aria Networks's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Networking
- Data Center
- Artificial Intelligence
- Infrastructure
- Telemetry
- Observability
- Ethernet
- Hardware
---
