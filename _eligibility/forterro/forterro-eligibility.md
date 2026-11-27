---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Our Website is directed to people residing in the countries in which we sell our products and services.
  entity_types:
  - text: We do not target our products or services, including this Website nor any content, towards consumers. Our customers are business customers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No damaging or overburdening servers
    text: You may not use the Websites in any manner that could damage, disable, overburden, or impair any Forterro owned or rented server
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
name: Forterro
provenance_date: '2026-11-09'
provider_name: Forterro
provider_slug: forterro
slug: forterro-eligibility
source_date: '2026-11-09'
source_filename: forterro-eligibility.yml
source_heading: Eligibility
source_page: https://www.forterro.com/en/company/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Forterro\naid: forterro\nurl: https://www.forterro.com/en/company/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Our Website is directed to people residing in the countries in which we sell our products and services.\nentity_types:\n- type: business\n  text: We do not target our products or services, including this Website nor any content, towards consumers. Our\n    customers are business customers.\nrestricted_uses:\n- summary: No damaging or overburdening servers\n  text: You may not use the Websites in any manner that could damage, disable, overburden, or impair\
  \ any Forterro\n    owned or rented server\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/forterro/eligibility/forterro-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Forterro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- ERP
- Industrial Software
- Manufacturing
- Warehouse Management
- Business Intelligence
- Supply Chain
---
