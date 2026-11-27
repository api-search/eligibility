---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: license worldwide (with the exception of (i) jurisdictions that are embargoed or designated as supporting terrorist activities by the United States Government and (ii) jurisdictions whose laws do not permit engaging in business with Magic Patterns or use of the Services)
  entity_types:
  - text: users that are part of a “workspace” pursuant to an Enterprise Plan
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or fraudulent activity
    text: 'You may not utilize the Services to carry out, promote or support: any unlawful or fraudulent activities'
  - summary: Competitive analysis
    text: the use of the Services for competitive analysis or to build competitive products.
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
name: Magic Patterns
provenance_date: '2026-11-10'
provider_name: Magic Patterns
provider_slug: magic-patterns
slug: magic-patterns-eligibility
source_date: '2026-11-10'
source_filename: magic-patterns-eligibility.yml
source_heading: Eligibility
source_page: https://www.magicpatterns.com/docs/documentation/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Magic Patterns\naid: magic-patterns\nurl: https://www.magicpatterns.com/docs/documentation/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: license worldwide (with the exception of (i) jurisdictions that are embargoed or designated as supporting\n    terrorist activities by the United States Government and (ii) jurisdictions whose laws do not permit engaging\n    in business with Magic Patterns or use of the Services)\nentity_types:\n- type: business\n  text: users that are part of a “workspace” pursuant to an Enterprise Plan\nrestricted_uses:\n- summary: Unlawful or fraudulent\
  \ activity\n  text: 'You may not utilize the Services to carry out, promote or support: any unlawful or fraudulent activities'\n- summary: Competitive analysis\n  text: the use of the Services for competitive analysis or to build competitive products.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/magic-patterns/eligibility/magic-patterns-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Magic Patterns's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Platform
- Prompt Engineering
- Collaboration
- Software-as-a-Service
---
