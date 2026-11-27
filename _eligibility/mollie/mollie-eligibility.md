---
api_specs:
- filename: mollie-openapi-original.yml
  format: yaml
  label: Mollie API
  slug: mollie-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mollie/openapi/mollie-openapi-original.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Services are only available to legal entities and organisations acting in a commercial capacity, and explicitly not to consumers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited activities list
    text: Mollie keeps a list of prohibited activities, which is available on its website.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Mollie decides to accept or decline your application to receive full access to the Services after a full verification as described in Article 2.2.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mollie
provenance_date: '2026-11-10'
provider_name: Mollie
provider_slug: mollie
slug: mollie-eligibility
source_date: '2026-11-10'
source_filename: mollie-eligibility.yml
source_heading: Eligibility
source_page: https://www.mollie.com/legal/user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mollie\naid: mollie\nurl: https://www.mollie.com/legal/user-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Services are only available to legal entities and organisations acting in a commercial capacity, and explicitly\n    not to consumers.\nrestricted_uses:\n- summary: Prohibited activities list\n  text: Mollie keeps a list of prohibited activities, which is available on its website.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Mollie decides to accept or decline your application\
  \ to receive full access to the Services after a full\n    verification as described in Article 2.2.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mollie/eligibility/mollie-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Mollie's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Fintech
- Financial Services
- Checkout
- E-Commerce
- Subscription
- Point-of-Sale
- Europe
- Netherlands
- Payment Processing
---
