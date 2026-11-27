---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: يجب ألا يقل عمر المستخدم عن 18 عاماً لإنشاء حساب.
    type: individual
  minimum_age:
    text: يجب ألا يقل عمر المستخدم عن 18 عاماً لإنشاء حساب.
    value: '18'
  restricted_uses:
  - summary: Illegal or restricted goods and services
    text: 'المنتجات أو الأنشطة غير القانونية أو المقيدة : مثل المخدرات والأسلحة غير المصرح بها'
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
name: Fatora
provenance_date: '2026-11-09'
provider_name: Fatora
provider_slug: fatora
slug: fatora-eligibility
source_date: '2026-11-09'
source_filename: fatora-eligibility.yml
source_heading: Eligibility
source_page: https://fatora.io/ar/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fatora\naid: fatora\nurl: https://fatora.io/ar/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: يجب ألا يقل عمر المستخدم عن 18 عاماً لإنشاء حساب.\nrestricted_uses:\n- summary: Illegal or restricted goods and services\n  text: 'المنتجات أو الأنشطة غير القانونية أو المقيدة : مثل المخدرات والأسلحة غير المصرح بها'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: يجب ألا يقل عمر المستخدم عن 18 عاماً لإنشاء حساب.\n"
source_yaml_url: https://artifacts.apis.io/fatora/eligibility/fatora-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fatora's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Invoicing
- Payment Gateway
- E-Commerce
- Billing
- Fintech
- Checkout
- MENA
- Qatar
- Software-as-a-Service
---
