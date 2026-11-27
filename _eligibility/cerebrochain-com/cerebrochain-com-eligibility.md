---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept them for a company or other organization, you confirm that you have authority to bind it, and "you" means that organization.
    type: business
  minimum_age:
    text: You must be at least 18 to use the Service.
    value: '18'
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
name: CerebroChain
provenance_date: '2026-11-09'
provider_name: CerebroChain
provider_slug: cerebrochain-com
slug: cerebrochain-com-eligibility
source_date: '2026-11-09'
source_filename: cerebrochain-com-eligibility.yml
source_heading: Eligibility
source_page: https://cerebrochain.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CerebroChain\naid: cerebrochain-com\nurl: https://cerebrochain.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept them for a company or other organization, you confirm that you have authority to bind it,\n    and \"you\" means that organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cerebrochain-com/eligibility/cerebrochain-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from CerebroChain's own page on 2026-11-09.
synthetic: false
tags:
- Warehouse
- Logistics
- Artificial Intelligence
- Software-as-a-Service
- Warehouse Management
---
