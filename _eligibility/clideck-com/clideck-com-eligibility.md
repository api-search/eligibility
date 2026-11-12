---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if you are located in a region subject to comprehensive sanctions or are listed on a restricted-party list.
  entity_types:
  - text: You must be at least 13 years old to use the Service. If you are under the age of majority in your jurisdiction, you represent that you have permission from a parent or legal guardian.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Sanctioned regions or restricted parties
    text: You may not use the Service if you are located in a region subject to comprehensive sanctions or are listed on a restricted-party list.
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
name: CliDeck
provenance_date: '2026-11-09'
provider_name: CliDeck
provider_slug: clideck-com
slug: clideck-com-eligibility
source_date: '2026-11-09'
source_filename: clideck-com-eligibility.yml
source_heading: Eligibility
source_page: https://clideck.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CliDeck\naid: clideck-com\nurl: https://clideck.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if you are located in a region subject to comprehensive sanctions or are listed\n    on a restricted-party list.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Service. If you are under the age of majority in your jurisdiction,\n    you represent that you have permission from a parent or legal guardian.\nrestricted_uses:\n- summary: Sanctioned regions or restricted parties\n  text: You may not use\
  \ the Service if you are located in a region subject to comprehensive sanctions or are listed\n    on a restricted-party list.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/clideck-com/eligibility/clideck-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CliDeck's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Network Automation
- Terminal
- SSH
- Serial Console
- Out-of-Band Management
- Console Server
- MCP
- Infrastructure
- ITAD
---
