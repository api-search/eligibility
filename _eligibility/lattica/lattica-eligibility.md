---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ACCEPTING THESE TERMS ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT AND WARRANT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY.
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
name: Lattica
provenance_date: '2026-11-09'
provider_name: Lattica
provider_slug: lattica
slug: lattica-eligibility
source_date: '2026-11-09'
source_filename: lattica-eligibility.yml
source_heading: Eligibility
source_page: https://www.lattica.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lattica\naid: lattica\nurl: https://www.lattica.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ACCEPTING THESE TERMS ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT AND WARRANT\n    THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lattica/eligibility/lattica-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Lattica's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Privacy
- Fully Homomorphic Encryption
- Encryption
- Confidential Computing
- Artificial Intelligence
- Machine Learning
- Inference
- Vector Search
- Security
---
