---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You may use the Services only if you can form a binding contract with us and are not a person barred from receiving services under the laws of the United States or other applicable jurisdiction.
  entity_types:
  - text: IF YOU ARE ACCEPTING THESE TERMS OF USE ON BEHALF OF A COMPANY, ORGANIZATION, GOVERNMENT, OR OTHER LEGAL ENTITY, YOU REPRESENT AND WARRANT THAT YOU ARE AUTHORIZED TO DO SO.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitors accessing content
    text: access or use any portion of the Content if you are a direct or indirect competitor of the Company
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
name: Acorns
provenance_date: '2026-11-09'
provider_name: Acorns
provider_slug: acorns
slug: acorns-eligibility
source_date: '2026-11-09'
source_filename: acorns-eligibility.yml
source_heading: Eligibility
source_page: https://www.acorns.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Acorns\naid: acorns\nurl: https://www.acorns.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You may use the Services only if you can form a binding contract with us and are not a person barred from\n    receiving services under the laws of the United States or other applicable jurisdiction.\nentity_types:\n- type: business\n  text: IF YOU ARE ACCEPTING THESE TERMS OF USE ON BEHALF OF A COMPANY, ORGANIZATION, GOVERNMENT, OR OTHER LEGAL\n    ENTITY, YOU REPRESENT AND WARRANT THAT YOU ARE AUTHORIZED TO DO SO.\nrestricted_uses:\n- summary: Competitors accessing content\n\
  \  text: access or use any portion of the Content if you are a direct or indirect competitor of the Company\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/acorns/eligibility/acorns-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Acorns's own page on 2026-11-09.
synthetic: false
tags:
- Micro-Investing
- Personal Finance
- Fintech
- Round-Ups
- Robo-Investing
- Retirement
- Savings
- Banking
- Financial Wellness
- Consumer Finance
---
