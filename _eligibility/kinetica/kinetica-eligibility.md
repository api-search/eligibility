---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website is controlled and operated from facilities in the United States. You may not use the Website if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
  entity_types:
  - text: You may use the Website only if you can form a binding contract with Kinetica
    type: individual
  - text: Unless otherwise explicitly stated, all materials found on the Website are solely directed to individuals, companies, or other entities located in the United States.
    type: business
  minimum_age:
    text: Any use or access to the Website by anyone under 13 is strictly prohibited and in violation of this Agreement.
    value: '13'
  restricted_uses:
  - summary: Commercial solicitation
    text: using the Website for any commercial solicitation purposes
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
name: Kinetica
provenance_date: '2026-11-09'
provider_name: Kinetica
provider_slug: kinetica
slug: kinetica-eligibility
source_date: '2026-11-09'
source_filename: kinetica-eligibility.yml
source_heading: Eligibility
source_page: https://www.kinetica.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kinetica\naid: kinetica\nurl: https://www.kinetica.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website is controlled and operated from facilities in the United States. You may not use the Website\n    if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked\n    or denied by the United States government.\nentity_types:\n- type: individual\n  text: You may use the Website only if you can form a binding contract with Kinetica\n- type: business\n  text: Unless otherwise explicitly stated, all materials\
  \ found on the Website are solely directed to individuals,\n    companies, or other entities located in the United States.\nrestricted_uses:\n- summary: Commercial solicitation\n  text: using the Website for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any use or access to the Website by anyone under 13 is strictly prohibited and in violation of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/kinetica/eligibility/kinetica-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Kinetica's own page on 2026-11-09.
synthetic: false
tags:
- Database
- Analytics
- gpu-acceleration
- Real-Time Analytics
- Vector Search
- Graph Analytics
- Geospatial
- Time Series
- SQL
- Streaming
- Data Infrastructure
- MCP
- Agent-Native
- RAG
- A2A
---
