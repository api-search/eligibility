---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: These Terms apply to United States and Canadian individuals that use Our Place websites, applications, and related software and features
  entity_types:
  - text: You must be over the age of majority in your jurisdiction to use the Services and if not, you represent and warrant that your parent or legal guardian agrees to these Terms on your behalf
    type: individual
  minimum_age:
    text: You must be over the age of majority in your jurisdiction to use the Services
    value: age of majority
  restricted_uses:
  - summary: Resale and commercial purchases
    text: we sell and ship Products to end-user customers only for personal use only
  - summary: Export and sanctions restrictions
    text: Your purchase may not be sold, leased or transferred to restricted countries; to restricted end users; or for restricted end uses according to applicable export and sanctions laws of the United States.
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
name: Our Place
provenance_date: '2026-11-10'
provider_name: Our Place
provider_slug: our-place
slug: our-place-eligibility
source_date: '2026-11-10'
source_filename: our-place-eligibility.yml
source_heading: Eligibility
source_page: https://fromourplace.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Our Place\naid: our-place\nurl: https://fromourplace.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: These Terms apply to United States and Canadian individuals that use Our Place websites, applications, and\n    related software and features\nentity_types:\n- type: individual\n  text: You must be over the age of majority in your jurisdiction to use the Services and if not, you represent\n    and warrant that your parent or legal guardian agrees to these Terms on your behalf\nrestricted_uses:\n- summary: Resale and commercial\
  \ purchases\n  text: we sell and ship Products to end-user customers only for personal use only\n- summary: Export and sanctions restrictions\n  text: Your purchase may not be sold, leased or transferred to restricted countries; to restricted end users; or\n    for restricted end uses according to applicable export and sanctions laws of the United States.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You must be over the age of majority in your jurisdiction to use the Services\n"
source_yaml_url: https://artifacts.apis.io/our-place/eligibility/our-place-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Our Place's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Cookware
- Consumer
- Agentic Commerce
- Shopify
---
