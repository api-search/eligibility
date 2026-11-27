---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual that is authorized by the Customer to create an Account to use the Services on Customer’s behalf, provided that such Authorized User is over 18 years old.
    type: individual
  minimum_age:
    text: provided that such Authorized User is over 18 years old.
    value: '18'
  restricted_uses:
  - summary: Prohibited content types
    text: creating content which is offensive, profane, hateful, threatening, harmful, defamatory, libelous, harassing or promote discrimination, violence, gambling, or child pornography
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
name: Anyword
provenance_date: '2026-11-09'
provider_name: Anyword
provider_slug: anyword
slug: anyword-eligibility
source_date: '2026-11-09'
source_filename: anyword-eligibility.yml
source_heading: Eligibility
source_page: https://www.anyword.com/anyword-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anyword\naid: anyword\nurl: https://www.anyword.com/anyword-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual that is authorized by the Customer to create an Account to use the Services on Customer’s\n    behalf, provided that such Authorized User is over 18 years old.\nrestricted_uses:\n- summary: Prohibited content types\n  text: creating content which is offensive, profane, hateful, threatening, harmful, defamatory, libelous, harassing\n    or promote discrimination, violence, gambling, or child pornography\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: provided that such Authorized User is over 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/anyword/eligibility/anyword-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Anyword's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Content Generation
- Marketing
- Software-as-a-Service
---
