---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Website and Services.
    type: individual
  - text: If you are entering into this Agreement on behalf of a business or other legal entity, you represent that you have the authority to bind such entity to this Agreement
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Website and Services.
    value: '18'
  restricted_uses:
  - summary: Prohibited uses list
    text: 'you are prohibited from using the Website and Services or Content: (a) for any unlawful purpose;'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We may monitor and review new accounts before you may sign in and start using the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sudowrite
provenance_date: '2026-11-10'
provider_name: Sudowrite
provider_slug: sudowrite
slug: sudowrite-eligibility
source_date: '2026-11-10'
source_filename: sudowrite-eligibility.yml
source_heading: Eligibility
source_page: https://sudowrite.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sudowrite\naid: sudowrite\nurl: https://sudowrite.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Website and Services.\n- type: business\n  text: If you are entering into this Agreement on behalf of a business or other legal entity, you represent that\n    you have the authority to bind such entity to this Agreement\nrestricted_uses:\n- summary: Prohibited uses list\n  text: 'you are prohibited from using the Website and Services or Content: (a) for any unlawful\
  \ purpose;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We may monitor and review new accounts before you may sign in and start using the Services.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Website and Services.\n"
source_yaml_url: https://artifacts.apis.io/sudowrite/eligibility/sudowrite-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Sudowrite's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Writing
- Fiction
- Creative Writing
- Generative AI
- Content Generation
- Authoring
- Publishing
- Productivity
---
