---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: you are, and will remain, established in the United Kingdom and provide your services in the United Kingdom only
  entity_types:
  - text: any business, partnership or sole trader who registers on the MyBuilder Platform in order to connect with Customers
    type: business
  - text: You may only use the MyBuilder Platform if you are aged 18 or over.
    type: individual
  minimum_age:
    text: You may only use the MyBuilder Platform if you are aged 18 or over.
    value: '18'
  restricted_uses:
  - summary: No recruiting or advertising use of Jobs (customers)
    text: 'You must not use Jobs, messages or any other part of the MyBuilder Platform for any other purpose, including: (a) recruiting or soliciting Tradespeople for employment'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: 3.1.3. verify your identity;
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MyBuilder
provenance_date: '2026-11-10'
provider_name: MyBuilder
provider_slug: mybuilder
slug: mybuilder-eligibility
source_date: '2026-11-10'
source_filename: mybuilder-eligibility.yml
source_heading: Eligibility
source_page: https://www.mybuilder.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MyBuilder\naid: mybuilder\nurl: https://www.mybuilder.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: you are, and will remain, established in the United Kingdom and provide your services in the United Kingdom\n    only\nentity_types:\n- type: business\n  text: any business, partnership or sole trader who registers on the MyBuilder Platform in order to connect with\n    Customers\n- type: individual\n  text: You may only use the MyBuilder Platform if you are aged 18 or over.\nrestricted_uses:\n- summary: No recruiting or advertising use\
  \ of Jobs (customers)\n  text: 'You must not use Jobs, messages or any other part of the MyBuilder Platform for any other purpose, including:\n    (a) recruiting or soliciting Tradespeople for employment'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: 3.1.3. verify your identity;\nminimum_age:\n  value: '18'\n  text: You may only use the MyBuilder Platform if you are aged 18 or over.\n"
source_yaml_url: https://artifacts.apis.io/mybuilder/eligibility/mybuilder-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from MyBuilder's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Home Services
- Marketplace
- Tradespeople
- Home Improvement
- Local Services
- United Kingdom
- Consumer
---
