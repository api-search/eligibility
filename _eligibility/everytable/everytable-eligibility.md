---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CA
    served:
    - US
    text: This Website is offered and available to users who ... reside in the United States or any of its territories or possessions, and are legal U.S. citizens. We currently do not offer goods and services to Canada, the EU or EEA.
  minimum_age:
    text: are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Lawful use of products
    text: By placing an order, you represent that the Everytable Products ordered will be used only in a lawful manner.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Verification of information may be required prior to the acknowledgment or completion of any Transaction.
excluded_countries:
- CA
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Everytable
provenance_date: '2026-11-09'
provider_name: Everytable
provider_slug: everytable
slug: everytable-eligibility
source_date: '2026-11-09'
source_filename: everytable-eligibility.yml
source_heading: Eligibility
source_page: https://everytable.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Everytable\naid: everytable\nurl: https://everytable.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded:\n  - CA\n  text: This Website is offered and available to users who ... reside in the United States or any of its territories\n    or possessions, and are legal U.S. citizens. We currently do not offer goods and services to Canada, the EU\n    or EEA.\nentity_types: []\nrestricted_uses:\n- summary: Lawful use of products\n  text: By placing an order, you represent that the Everytable Products ordered will be used only in a lawful manner.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Verification of information may be required prior to the acknowledgment or completion of any Transaction.\nminimum_age:\n  value: '18'\n  text: are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/everytable/eligibility/everytable-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Everytable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food
- Restaurant
- Meal Delivery
- E-Commerce
- Agentic Commerce
- Shopify
- Social Enterprise
- Nutrition
- Subscription
---
