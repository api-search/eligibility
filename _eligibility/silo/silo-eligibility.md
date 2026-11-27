---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity identified as a customer on the applicable Silo Technologies Commercial Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Platform role limits
    text: Silo does not act as, and shall not be deemed to be, a buyer, seller, broker, freight broker, carrier, employer, co-employer, payroll processor, fiduciary, financial institution, or agent of Customer for any purpose.
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
name: Silo
provenance_date: '2026-11-10'
provider_name: Silo
provider_slug: silo
slug: silo-eligibility
source_date: '2026-11-10'
source_filename: silo-eligibility.yml
source_heading: Eligibility
source_page: https://www.usesilo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Silo\naid: silo\nurl: https://www.usesilo.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity identified as a customer on the applicable Silo Technologies Commercial Agreement\nrestricted_uses:\n- summary: Platform role limits\n  text: Silo does not act as, and shall not be deemed to be, a buyer, seller, broker, freight broker, carrier, employer,\n    co-employer, payroll processor, fiduciary, financial institution, or agent of Customer for any purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/silo/eligibility/silo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Silo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- ERP
- Produce
- Supply Chain
- Agriculture
- Payments
- EDI
- Traceability
- Food
- Food and Beverage
---
