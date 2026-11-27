---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are directed to those individuals and entities located in the United States.
  entity_types:
  - text: YOU AGREE THAT BY USING THE SERVICES YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD AND THAT YOU ARE LEGALLY ABLE TO ENTER INTO THIS AGREEMENT.
    type: individual
  minimum_age:
    text: YOU AGREE THAT BY USING THE SERVICES YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD AND THAT YOU ARE LEGALLY ABLE TO ENTER INTO THIS AGREEMENT.
    value: '18'
  restricted_uses:
  - summary: Not a credit repair organization
    text: Credit Sesame is not a credit repair organization and is not offering to sell, provide, or perform any service to you for the express or implied purpose of either improving your credit record
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
name: Credit Sesame
provenance_date: '2026-11-09'
provider_name: Credit Sesame
provider_slug: credit-sesame
slug: credit-sesame-eligibility
source_date: '2026-11-09'
source_filename: credit-sesame-eligibility.yml
source_heading: Eligibility
source_page: https://www.creditsesame.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Credit Sesame\naid: credit-sesame\nurl: https://www.creditsesame.com/legal/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are directed to those individuals and entities located in the United States.\nentity_types:\n- type: individual\n  text: YOU AGREE THAT BY USING THE SERVICES YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD AND THAT YOU ARE LEGALLY\n    ABLE TO ENTER INTO THIS AGREEMENT.\nrestricted_uses:\n- summary: Not a credit repair organization\n  text: Credit Sesame is not a credit repair organization and is not offering to sell, provide,\
  \ or perform any service\n    to you for the express or implied purpose of either improving your credit record\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU AGREE THAT BY USING THE SERVICES YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD AND THAT YOU ARE LEGALLY\n    ABLE TO ENTER INTO THIS AGREEMENT.\n"
source_yaml_url: https://artifacts.apis.io/credit-sesame/eligibility/credit-sesame-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Credit Sesame's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer Finance
- Credit Score
- Credit Monitoring
- Personal Finance
- Fintech
- Identity Protection
- Financial Services
---
