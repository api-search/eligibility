---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: outside the United Kingdom the Fertifa Services may be limited to navigation and wellbeing support, educational content, and Reimbursement Services
  entity_types:
  - text: You may only purchase products or participate in the Fertifa Services if you are at least 18 years old.
    type: individual
  minimum_age:
    text: You may only purchase products or participate in the Fertifa Services if you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Private use only
    text: We only supply the Fertifa Services and/or products for your private use. If you use the Fertifa Services for any commercial, business or re-sale purpose we will have no liability to you for any loss of profit
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to the Payment Plan is subject to eligibility and affordability checks.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fertifa
provenance_date: '2026-11-09'
provider_name: Fertifa
provider_slug: fertifa
slug: fertifa-eligibility
source_date: '2026-11-09'
source_filename: fertifa-eligibility.yml
source_heading: Eligibility
source_page: https://www.fertifa.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fertifa\naid: fertifa\nurl: https://www.fertifa.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: outside the United Kingdom the Fertifa Services may be limited to navigation and wellbeing support, educational\n    content, and Reimbursement Services\nentity_types:\n- type: individual\n  text: You may only purchase products or participate in the Fertifa Services if you are at least 18 years old.\nrestricted_uses:\n- summary: Private use only\n  text: We only supply the Fertifa Services and/or products for your private use. If you use the Fertifa Services\n\
  \    for any commercial, business or re-sale purpose we will have no liability to you for any loss of profit\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Access to the Payment Plan is subject to eligibility and affordability checks.\nminimum_age:\n  value: '18'\n  text: You may only purchase products or participate in the Fertifa Services if you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/fertifa/eligibility/fertifa-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Fertifa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fertility
- Reproductive Health
- Employee Benefits
- Healthcare
- Femtech
- Human Resources
- Menopause
- Family Forming
- Digital Health
---
