---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU (EITHER AN IDIVIDUAL OR AN ENTITY)
    type: individual
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF ANY LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
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
name: Novidea
provenance_date: '2026-11-10'
provider_name: Novidea
provider_slug: novidea
slug: novidea-eligibility
source_date: '2026-11-10'
source_filename: novidea-eligibility.yml
source_heading: Eligibility
source_page: https://novidea.com/en-us/subscription-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Novidea\naid: novidea\nurl: https://novidea.com/en-us/subscription-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU (EITHER AN IDIVIDUAL OR AN ENTITY)\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF ANY LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY\n    TO BIND SUCH ENTITY\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/novidea/eligibility/novidea-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Novidea's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Insurance Distribution
- Insurance Software
- Brokerage
- MGA
- Salesforce
- Claims
- Underwriting
---
