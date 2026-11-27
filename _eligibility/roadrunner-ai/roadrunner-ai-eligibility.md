---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF AN INDIVIDUAL IS ENTERING INTO THIS AGREEMENT ON BEHALF OF A LEGAL ENTITY, SUCH PERSON REPRESENTS AND WARRANTS THAT IT HAS THE LEGAL AUTHORITY TO BIND SUCH LEGAL ENTITY
    type: business
  minimum_age:
    text: THE SERVICE IS INTENDED FOR THE CUSTOMER AND ITS AUTHORIZED USERS ONLY AND IS NOT FOR USE BY CHILDREN UNDER 13 YEARS OF AGE.
    value: '13'
  restricted_uses:
  - summary: Unlawful use including export violations
    text: use the Service in violation of applicable law (including any export law)
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
name: Roadrunner
provenance_date: '2026-11-10'
provider_name: Roadrunner
provider_slug: roadrunner-ai
slug: roadrunner-ai-eligibility
source_date: '2026-11-10'
source_filename: roadrunner-ai-eligibility.yml
source_heading: Eligibility
source_page: https://roadrunner.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Roadrunner\naid: roadrunner-ai\nurl: https://roadrunner.ai/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF AN INDIVIDUAL IS ENTERING INTO THIS AGREEMENT ON BEHALF OF A LEGAL ENTITY, SUCH PERSON REPRESENTS AND\n    WARRANTS THAT IT HAS THE LEGAL AUTHORITY TO BIND SUCH LEGAL ENTITY\nrestricted_uses:\n- summary: Unlawful use including export violations\n  text: use the Service in violation of applicable law (including any export law)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '13'\n  text: THE SERVICE IS INTENDED FOR THE CUSTOMER AND ITS AUTHORIZED USERS ONLY AND IS NOT FOR USE BY CHILDREN UNDER\n    13 YEARS OF AGE.\n"
source_yaml_url: https://artifacts.apis.io/roadrunner-ai/eligibility/roadrunner-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Roadrunner's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- CPQ
- Software-as-a-Service
- Quoting
---
