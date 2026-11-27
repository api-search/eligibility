---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are cloud-based software for businesses only; there is no public sign-up.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Regulated uses require prior notice
    text: The Customer must notify us in writing before using the Services for debt collection, financial services, gambling, healthcare, government or other regulated activity
  - summary: Acceptable use restrictions
    text: send spam or contact anyone without a lawful basis or after an opt-out
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Access is granted after our review of the Customer and its use case, which may include know-your-customer and sanctions checks.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MaiCall
provenance_date: '2026-11-10'
provider_name: MaiCall
provider_slug: maicall
slug: maicall-eligibility
source_date: '2026-11-10'
source_filename: maicall-eligibility.yml
source_heading: Eligibility
source_page: https://maicall.ai/terms-condition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MaiCall\naid: maicall\nurl: https://maicall.ai/terms-condition\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are cloud-based software for businesses only; there is no public sign-up.\nrestricted_uses:\n- summary: Regulated uses require prior notice\n  text: The Customer must notify us in writing before using the Services for debt collection, financial services,\n    gambling, healthcare, government or other regulated activity\n- summary: Acceptable use restrictions\n  text: send spam or contact anyone without a lawful\
  \ basis or after an opt-out\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Access is granted after our review of the Customer and its use case, which may include know-your-customer\n    and sanctions checks.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/maicall/eligibility/maicall-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from MaiCall's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Debt Collection
- Collection
- Voice AI
- Conversational AI
- Fintech
- Payments
---
