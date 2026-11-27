---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these TOS on behalf of a company or other legal entity as indicated in your log-in or registration information, you represent that you have the authority to bind such entity to these TOS
    type: business
  minimum_age:
    text: you are not of legal age to form a binding contract with Company
    value: null
  restricted_uses:
  - summary: Users prohibited by law
    text: (b) you are prohibited by law from receiving or using the Services
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
name: EINO
provenance_date: '2026-11-09'
provider_name: EINO
provider_slug: eino
slug: eino-eligibility
source_date: '2026-11-09'
source_filename: eino-eligibility.yml
source_heading: Eligibility
source_page: https://www.eino.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EINO\naid: eino\nurl: https://www.eino.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these TOS on behalf of a company or other legal entity as indicated in your log-in\n    or registration information, you represent that you have the authority to bind such entity to these TOS\nrestricted_uses:\n- summary: Users prohibited by law\n  text: (b) you are prohibited by law from receiving or using the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: you are not of legal age to form a binding contract with Company\n"
source_yaml_url: https://artifacts.apis.io/eino/eligibility/eino-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from EINO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wireless
- Networking
- Digital Twin
- Network Design
- Network Monitoring
- Connectivity
- Artificial Intelligence
- 5G
- IoT
- Telecommunications
---
