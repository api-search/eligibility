---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use our Service, and You may only open an account or use our Service, if you can form legally-binding contracts under applicable law.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or abusive content
    text: Send or promote any message that is unlawful, libelous, defamatory, abusive, sexually explicit, threatening, vulgar, obscene, profane
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
name: Emporia Energy
provenance_date: '2026-11-09'
provider_name: Emporia Energy
provider_slug: emporia-energy
slug: emporia-energy-eligibility
source_date: '2026-11-09'
source_filename: emporia-energy-eligibility.yml
source_heading: Eligibility
source_page: https://www.emporiaenergy.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Emporia Energy\naid: emporia-energy\nurl: https://www.emporiaenergy.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use our Service, and You may only open an account or use our Service, if you can form legally-binding\n    contracts under applicable law.\nrestricted_uses:\n- summary: Unlawful or abusive content\n  text: Send or promote any message that is unlawful, libelous, defamatory, abusive, sexually explicit, threatening,\n    vulgar, obscene, profane\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/emporia-energy/eligibility/emporia-energy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Emporia Energy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Smart Home
- IoT
- Monitoring
---
