---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a business entity, financial institution, employer or other organisation that accesses the Technology Solutions pursuant to a commercial or licensing arrangement with Tartan and acts as the data fiduciary in respect of End User personal data
    type: business
  minimum_age:
    text: the User or the entity on whose behalf access is sought is at least eighteen (18) years of age and duly authorised to contract
    value: '18'
  restricted_uses:
  - summary: No unlawful use
    text: The User shall not directly or indirectly use the Technology Solutions for any unlawful purpose or in breach of Applicable Laws.
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
name: TartanHQ
provenance_date: '2026-11-10'
provider_name: TartanHQ
provider_slug: tartanhq
slug: tartanhq-eligibility
source_date: '2026-11-10'
source_filename: tartanhq-eligibility.yml
source_heading: Eligibility
source_page: https://www.tartanhq.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TartanHQ\naid: tartanhq\nurl: https://www.tartanhq.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: a business entity, financial institution, employer or other organisation that accesses the Technology Solutions\n    pursuant to a commercial or licensing arrangement with Tartan and acts as the data fiduciary in respect of End\n    User personal data\nrestricted_uses:\n- summary: No unlawful use\n  text: The User shall not directly or indirectly use the Technology Solutions for any unlawful purpose or\
  \ in breach\n    of Applicable Laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the User or the entity on whose behalf access is sought is at least eighteen (18) years of age and duly\n    authorised to contract\n"
source_yaml_url: https://artifacts.apis.io/tartanhq/eligibility/tartanhq-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from TartanHQ's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Verification
- Identity
- KYC
- KYB
- Financial Services
- Insurance
- Human Resources
- Lending
- API Infrastructure
- Fintech
- India
---
