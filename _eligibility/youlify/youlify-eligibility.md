---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Site is available for use only by individuals who are located in the United States or its territories or possessions
  entity_types:
  - text: This Material is intended for the use of individuals and businesses that are researching medical billing solutions.
    type: business
  minimum_age:
    text: You are at least 18 years of age;
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: Use the Site other than for private, non-commercial use without our prior written consent
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
name: Youlify
provenance_date: '2026-11-10'
provider_name: Youlify
provider_slug: youlify
slug: youlify-eligibility
source_date: '2026-11-10'
source_filename: youlify-eligibility.yml
source_heading: Eligibility
source_page: https://www.youlify.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Youlify\naid: youlify\nurl: https://www.youlify.ai/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Site is available for use only by individuals who are located in the United States or its territories\n    or possessions\nentity_types:\n- type: business\n  text: This Material is intended for the use of individuals and businesses that are researching medical billing\n    solutions.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: Use the Site other than for private, non-commercial use without our prior written consent\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age;\n"
source_yaml_url: https://artifacts.apis.io/youlify/eligibility/youlify-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Youlify's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Fintech
- Artificial Intelligence
- Revenue Cycle
---
