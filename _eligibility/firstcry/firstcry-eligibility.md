---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: FirstCry.com will deliver the products only within India
  entity_types:
  - text: Use of the Site is available only to persons who can form legally binding contracts under applicable law.
    type: individual
  - text: In case of a business entity, you represent that you have the necessary authority to bind the entity to this User Agreement.
    type: business
  minimum_age:
    text: You may use this site only if your age is over 18 years.
    value: '18'
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
name: FirstCry
provenance_date: '2026-11-09'
provider_name: FirstCry
provider_slug: firstcry
slug: firstcry-eligibility
source_date: '2026-11-09'
source_filename: firstcry-eligibility.yml
source_heading: Eligibility
source_page: https://www.firstcry.com/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FirstCry\naid: firstcry\nurl: https://www.firstcry.com/termsofuse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: FirstCry.com will deliver the products only within India\nentity_types:\n- type: individual\n  text: Use of the Site is available only to persons who can form legally binding contracts under applicable law.\n- type: business\n  text: In case of a business entity, you represent that you have the necessary authority to bind the entity to\n    this User Agreement.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use this site only if your age is over 18 years.\n"
source_yaml_url: https://artifacts.apis.io/firstcry/eligibility/firstcry-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from FirstCry's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Retail
- E-Commerce
- Baby
- Kids
- Maternity
- Omnichannel
- India
---
