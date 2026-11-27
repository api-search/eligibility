---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The person who opens an account accepts these terms on behalf of the organization they work for, and confirms they have the authority to bind it. That organization is the customer.
    type: business
  - text: A person working on their own is the customer themselves.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No use breaking law or connected service terms
    text: use the Service in a way that breaks the law or the terms of a connected service, or that could lead Intuit, Plaid, Stripe or another provider to restrict our access
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
name: Peich Technologies Inc.
provenance_date: '2026-11-09'
provider_name: Peich Technologies Inc.
provider_slug: caribooks-com
slug: caribooks-com-eligibility
source_date: '2026-11-09'
source_filename: caribooks-com-eligibility.yml
source_heading: Eligibility
source_page: https://caribooks.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Peich Technologies Inc.\naid: caribooks-com\nurl: https://caribooks.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The person who opens an account accepts these terms on behalf of the organization they work for, and confirms\n    they have the authority to bind it. That organization is the customer.\n- type: individual\n  text: A person working on their own is the customer themselves.\nrestricted_uses:\n- summary: No use breaking law or connected service terms\n  text: use the Service in a way that breaks the law or the\
  \ terms of a connected service, or that could lead Intuit,\n    Plaid, Stripe or another provider to restrict our access\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/caribooks-com/eligibility/caribooks-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Peich Technologies Inc.'s own page on 2026-11-09.
synthetic: false
tags:
- Accounting
- Artificial Intelligence
- Integration
- QuickBooks
- Software-as-a-Service
---
