---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - BY
    - CU
    - IR
    - KP
    - RU
    - SY
    served: []
    text: is not organized under the laws of, resides in, or is controlled by any country or region subject to comprehensive sanctions or embargoes (currently, Belarus, Cuba, Iran, North Korea, Russia, Syria, and the Crimea, Donetsk, Kherson, Luhansk, and Zaporizhzhia regions of Ukraine)
  entity_types:
  - text: the end user (as an individual or entity, “End User”)
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Assistant use limited
    text: End User may not use the Assistant for any purpose other than to seek information about the Software’s functionality.
  - summary: Export restrictions
    text: Veeam reserves the right to block access to the Software for violations of this clause without prior notice.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- BY
- CU
- IR
- KP
- RU
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kasten
provenance_date: '2026-11-09'
provider_name: Kasten
provider_slug: kasten
slug: kasten-eligibility
source_date: '2026-11-09'
source_filename: kasten-eligibility.yml
source_heading: Eligibility
source_page: https://www.veeam.com/legal/eula.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kasten\naid: kasten\nurl: https://www.veeam.com/legal/eula.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - BY\n  - CU\n  - IR\n  - KP\n  - RU\n  - SY\n  text: is not organized under the laws of, resides in, or is controlled by any country or region subject to comprehensive\n    sanctions or embargoes (currently, Belarus, Cuba, Iran, North Korea, Russia, Syria, and the Crimea, Donetsk,\n    Kherson, Luhansk, and Zaporizhzhia regions of Ukraine)\nentity_types:\n- type: individual\n  text: the end user (as an individual or entity, “End User”)\nrestricted_uses:\n- summary: Assistant use\
  \ limited\n  text: End User may not use the Assistant for any purpose other than to seek information about the Software’s functionality.\n- summary: Export restrictions\n  text: Veeam reserves the right to block access to the Software for violations of this clause without prior notice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kasten/eligibility/kasten-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Kasten's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Kubernetes
- Backup
- Disaster Recovery
- Data Protection
- Cloud-Native
- DevOps
---
