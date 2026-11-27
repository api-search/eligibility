---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are available to individuals and entities worldwide.
  entity_types:
  - text: The Services are available to individuals and entities worldwide.
    type: individual
  - text: If you are using the Services on behalf of a business entity, you represent that you have authority to bind that entity.
    type: business
  minimum_age:
    text: null
    value: null
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
name: SyncTools
provenance_date: '2026-11-10'
provider_name: SyncTools
provider_slug: synctools
slug: synctools-eligibility
source_date: '2026-11-10'
source_filename: synctools-eligibility.yml
source_heading: Eligibility
source_page: https://synctools.ai/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SyncTools\naid: synctools\nurl: https://synctools.ai/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are available to individuals and entities worldwide.\nentity_types:\n- type: individual\n  text: The Services are available to individuals and entities worldwide.\n- type: business\n  text: If you are using the Services on behalf of a business entity, you represent that you have authority to bind\n    that entity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/synctools/eligibility/synctools-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 3 quoted statements, read from SyncTools's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Automation
- Artificial Intelligence
- Accounting
---
