---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Site on behalf of an entity, you represent and warrant that you have the authority to bind that entity
    type: business
  minimum_age:
    text: To use the Site, you must be over the age of seventeen (17).
    value: '17'
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: use the Content and/or the Site for any illegal, immoral, or unauthorized purpose
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
name: Pontera
provenance_date: '2026-11-10'
provider_name: Pontera
provider_slug: pontera
slug: pontera-eligibility
source_date: '2026-11-10'
source_filename: pontera-eligibility.yml
source_heading: Eligibility
source_page: https://www.pontera.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pontera\naid: pontera\nurl: https://www.pontera.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Site on behalf of an entity, you represent and warrant that you have the authority to bind\n    that entity\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: use the Content and/or the Site for any illegal, immoral, or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '17'\n  text: To use the Site, you must be over\
  \ the age of seventeen (17).\n"
source_yaml_url: https://artifacts.apis.io/pontera/eligibility/pontera-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Pontera's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- WealthTech
- Retirement
- 401k
- Financial Advisors
- Retirement Planning
- Security
---
