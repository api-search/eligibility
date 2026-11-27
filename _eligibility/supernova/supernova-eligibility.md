---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if ... you are a person or entity barred from receiving the Service under the laws of the State of Delaware or other applicable laws, including the laws of the country in which you reside or from which you use the Service.
  entity_types:
  - text: You may not use the Service if (a) you are contracting on behalf of an entity and are not authorized to legally bind it
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Embargoed countries
    text: will not sell, export, re-export, transfer, use, or enable the use of the Service, related technology and services, or other items provided by Supernova for end-use in or by embargoed countries or their citizens/nationals/permanent residents.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access the Service, you may be required to provide information about yourself (such as identification or contact details) as part of the registration process or continued use.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Supernova
provenance_date: '2026-11-10'
provider_name: Supernova
provider_slug: supernova
slug: supernova-eligibility
source_date: '2026-11-10'
source_filename: supernova-eligibility.yml
source_heading: Eligibility
source_page: https://www.supernova.io/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Supernova\naid: supernova\nurl: https://www.supernova.io/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if ... you are a person or entity barred from receiving the Service under the\n    laws of the State of Delaware or other applicable laws, including the laws of the country in which you reside\n    or from which you use the Service.\nentity_types:\n- type: business\n  text: You may not use the Service if (a) you are contracting on behalf of an entity and are not authorized to\n    legally bind it\nrestricted_uses:\n- summary:\
  \ Embargoed countries\n  text: will not sell, export, re-export, transfer, use, or enable the use of the Service, related technology and\n    services, or other items provided by Supernova for end-use in or by embargoed countries or their citizens/nationals/permanent\n    residents.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access the Service, you may be required to provide information about yourself (such as identification\n    or contact details) as part of the registration process or continued use.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/supernova/eligibility/supernova-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Supernova's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Design Tech
- Design Systems
- Design Tokens
- Documentation
- Code Automation
- Developer Experience
- AI Agents
- MCP
---
