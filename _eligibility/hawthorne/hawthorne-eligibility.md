---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You can only use or receive our Services to the extent the laws of your jurisdiction or the United States do not bar you from doing so.
  entity_types:
  - text: We only permit individuals who are at least 18 years old and can form legally binding contracts with us to use our Services.
    type: individual
  minimum_age:
    text: We only permit individuals who are at least 18 years old and can form legally binding contracts with us to use our Services. If you are under 18 years old and would like to use our Services, you can, but only if a parent or legal guardian who is at least 18 years old supervises you.
    value: '18'
  restricted_uses:
  - summary: Personal, noncommercial use only
    text: We offer our Services only for personal, noncommercial use, and not for the use or benefit of any third party
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
name: Hawthorne
provenance_date: '2026-11-09'
provider_name: Hawthorne
provider_slug: hawthorne
slug: hawthorne-eligibility
source_date: '2026-11-09'
source_filename: hawthorne-eligibility.yml
source_heading: Eligibility
source_page: https://hawthorne.co/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hawthorne\naid: hawthorne\nurl: https://hawthorne.co/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You can only use or receive our Services to the extent the laws of your jurisdiction or the United States\n    do not bar you from doing so.\nentity_types:\n- type: individual\n  text: We only permit individuals who are at least 18 years old and can form legally binding contracts with us\n    to use our Services.\nrestricted_uses:\n- summary: Personal, noncommercial use only\n  text: We offer our Services only for personal, noncommercial use, and not\
  \ for the use or benefit of any third\n    party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: We only permit individuals who are at least 18 years old and can form legally binding contracts with us\n    to use our Services. If you are under 18 years old and would like to use our Services, you can, but only if\n    a parent or legal guardian who is at least 18 years old supervises you.\n"
source_yaml_url: https://artifacts.apis.io/hawthorne/eligibility/hawthorne-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Hawthorne's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Consumer Goods
- Personal Care
- Grooming
- Agentic Commerce
- Shopify
---
