---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - MY
    - SG
    - TH
    - PH
    text: Applicable Governing Laws and Courts are set out for Malaysia, Singapore, Thailand and the Philippines; other countries default to Singapore.
  entity_types:
  - text: The Merchant must be of 18 years or older or at least the age of majority in the jurisdiction where the Merchant resides or from which the Merchant uses the Service.
    type: individual
  - text: where the person is a body corporate or entity other than an individual, the person accessing or using the Service on behalf of the body corporate or entity is an authorised representative
    type: business
  minimum_age:
    text: The Merchant must be of 18 years or older or at least the age of majority in the jurisdiction where the Merchant resides or from which the Merchant uses the Service.
    value: '18'
  restricted_uses:
  - summary: Prohibited or restricted items
    text: You must not post, sell or transact any item or service that is prohibited or restricted by a federal, state or local law in your jurisdiction through the Service
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
name: StoreHub
provenance_date: '2026-11-10'
provider_name: StoreHub
provider_slug: storehub
slug: storehub-eligibility
source_date: '2026-11-10'
source_filename: storehub-eligibility.yml
source_heading: Eligibility
source_page: https://www.storehub.com/my/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StoreHub\naid: storehub\nurl: https://www.storehub.com/my/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - MY\n  - SG\n  - TH\n  - PH\n  excluded: []\n  text: Applicable Governing Laws and Courts are set out for Malaysia, Singapore, Thailand and the Philippines;\n    other countries default to Singapore.\nentity_types:\n- type: individual\n  text: The Merchant must be of 18 years or older or at least the age of majority in the jurisdiction where the\n    Merchant resides or from which the Merchant uses the Service.\n- type: business\n  text: where the person is a body\
  \ corporate or entity other than an individual, the person accessing or using the\n    Service on behalf of the body corporate or entity is an authorised representative\nrestricted_uses:\n- summary: Prohibited or restricted items\n  text: You must not post, sell or transact any item or service that is prohibited or restricted by a federal, state\n    or local law in your jurisdiction through the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Merchant must be of 18 years or older or at least the age of majority in the jurisdiction where the\n    Merchant resides or from which the Merchant uses the Service.\n"
source_yaml_url: https://artifacts.apis.io/storehub/eligibility/storehub-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from StoreHub's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Point-of-Sale
- Retail
- Restaurant
- Inventory
- Payments
- E-Commerce
- Loyalty
- Southeast Asia
- Small Business
---
