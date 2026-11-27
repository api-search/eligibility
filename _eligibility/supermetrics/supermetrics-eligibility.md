---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - BY
    - RU
    - VE
    served: []
    text: As at the date of this Agreement prohibited countries or territories include Cuba, Iran, North Korea, Syria, the Crimea, Donetsk, and Luhansk regions of Ukraine, Belarus, Russia and Venezuela.
  entity_types:
  - text: the entity that has entered into an Order Form or otherwise subscribes for or accesses the Service
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No direct agency client logins
    text: Marketing Agency Customer shall not grant direct access or log in credentials to the Service to Marketing Agency Clients.
  - summary: No special category data on self-serve
    text: Where Customer has a Self-Serve Subscription, Customer shall not submit Special Categories of Personal Data to the Service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
- BY
- RU
- VE
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Supermetrics
provenance_date: '2026-11-10'
provider_name: Supermetrics
provider_slug: supermetrics
slug: supermetrics-eligibility
source_date: '2026-11-10'
source_filename: supermetrics-eligibility.yml
source_heading: Eligibility
source_page: https://supermetrics.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Supermetrics\naid: supermetrics\nurl: https://supermetrics.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - BY\n  - RU\n  - VE\n  text: As at the date of this Agreement prohibited countries or territories include Cuba, Iran, North Korea, Syria,\n    the Crimea, Donetsk, and Luhansk regions of Ukraine, Belarus, Russia and Venezuela.\nentity_types:\n- type: business\n  text: the entity that has entered into an Order Form or otherwise subscribes for or accesses the Service\nrestricted_uses:\n- summary: No direct agency\
  \ client logins\n  text: Marketing Agency Customer shall not grant direct access or log in credentials to the Service to Marketing\n    Agency Clients.\n- summary: No special category data on self-serve\n  text: Where Customer has a Self-Serve Subscription, Customer shall not submit Special Categories of Personal Data\n    to the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/supermetrics/eligibility/supermetrics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Supermetrics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Analytics
- Advertising
- Data
- Reporting
- Business Intelligence
- Data Warehouse
---
