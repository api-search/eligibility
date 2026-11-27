---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful, harmful or spam uses
    text: Access, store, distribute or transmit any viruses or any material that is unlawful, harmful, threatening, defamatory, obscene, infringing, harassing, discriminatory or offensive
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
name: OnFabric
provenance_date: '2026-11-10'
provider_name: OnFabric
provider_slug: onfabric
slug: onfabric-eligibility
source_date: '2026-11-10'
source_filename: onfabric-eligibility.yml
source_heading: Eligibility
source_page: https://onfabric.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OnFabric\naid: onfabric\nurl: https://onfabric.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful, harmful or spam uses\n  text: Access, store, distribute or transmit any viruses or any material that is unlawful, harmful, threatening,\n    defamatory, obscene, infringing, harassing, discriminatory or offensive\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/onfabric/eligibility/onfabric-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from OnFabric's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Personal Context
- Memory
- MCP
- Developer Tools
- CLI
---
