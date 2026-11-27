---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: to use the Software solely for the Customer’s business purposes and that of its Entities
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful or harmful material
    text: the Customer shall not store, distribute or transmit any material through the Hosting Services that is unlawful, harmful, threatening, defamatory, obscene, harassing or racially or ethnically offensive
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
name: AccountsIQ
provenance_date: '2026-11-09'
provider_name: AccountsIQ
provider_slug: accountsiq
slug: accountsiq-eligibility
source_date: '2026-11-09'
source_filename: accountsiq-eligibility.yml
source_heading: Eligibility
source_page: https://www.accountsiq.com/legal/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AccountsIQ\naid: accountsiq\nurl: https://www.accountsiq.com/legal/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: to use the Software solely for the Customer’s business purposes and that of its Entities\nrestricted_uses:\n- summary: No unlawful or harmful material\n  text: the Customer shall not store, distribute or transmit any material through the Hosting Services that is unlawful,\n    harmful, threatening, defamatory, obscene, harassing or racially or ethnically offensive\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/accountsiq/eligibility/accountsiq-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from AccountsIQ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accounting
- Financial Management
- Cloud Accounting
- ERP
- Consolidation
- General Ledger
- Business Intelligence
- SOAP
- Ireland
---
