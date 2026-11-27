---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You will not use or access our Services if you are located in any jurisdiction in which the provision of our Services is prohibited under Canadian, U.S. or other applicable laws
  entity_types:
  - text: if you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - source: https://vrify.com/legal/acceptable-use-policy
    summary: Unlawful or harmful content
    text: use the Services to store or transmit any content, including Client Content, that may be infringing, defamatory, libellous, threatening, harmful, fraudulent, abusive, lewd, obscene, pornographic, tortious or unlawful
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
name: VRIFY
provenance_date: '2026-11-10'
provider_name: VRIFY
provider_slug: vrify
slug: vrify-eligibility
source_date: '2026-11-10'
source_filename: vrify-eligibility.yml
source_heading: Eligibility
source_page: https://vrify.com/legal/client-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VRIFY\naid: vrify\nurl: https://vrify.com/legal/client-terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://vrify.com/legal/acceptable-use-policy\n  - https://vrify.com/legal/client-terms-of-service\ncountries:\n  served: []\n  excluded: []\n  text: You will not use or access our Services if you are located in any jurisdiction in which the provision of\n    our Services is prohibited under Canadian, U.S. or other applicable laws\nentity_types:\n- type: business\n  text: if you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity\nrestricted_uses:\n\
  - summary: Unlawful or harmful content\n  text: use the Services to store or transmit any content, including Client Content, that may be infringing, defamatory,\n    libellous, threatening, harmful, fraudulent, abusive, lewd, obscene, pornographic, tortious or unlawful\n  source: https://vrify.com/legal/acceptable-use-policy\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vrify/eligibility/vrify-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from VRIFY's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mining
- Mineral Exploration
- Geoscience
- Artificial Intelligence
- Machine Learning
- 3D Visualization
- Data Visualization
- Investor Relations
- Software-as-a-Service
- Canada
---
