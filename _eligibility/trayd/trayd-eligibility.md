---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: YOU AGREE THAT YOU ARE AT LEAST 18 YEARS OLD AND THAT YOU ARE LEGALLY ABLE TO AGREE TO THESE TERMS.
    value: '18'
  restricted_uses:
  - summary: Harassment and unlawful content
    text: Harassment in any manner or form on the Site, including via e-mail, chat, or by use of obscene or abusive language, is strictly forbidden.
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
name: Trayd
provenance_date: '2026-11-10'
provider_name: Trayd
provider_slug: trayd
slug: trayd-eligibility
source_date: '2026-11-10'
source_filename: trayd-eligibility.yml
source_heading: Eligibility
source_page: https://www.buildtrayd.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trayd\naid: trayd\nurl: https://www.buildtrayd.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harassment and unlawful content\n  text: Harassment in any manner or form on the Site, including via e-mail, chat, or by use of obscene or abusive\n    language, is strictly forbidden.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU AGREE THAT YOU ARE AT LEAST 18 YEARS OLD AND THAT YOU ARE LEGALLY ABLE TO AGREE TO THESE TERMS.\n"
source_yaml_url: https://artifacts.apis.io/trayd/eligibility/trayd-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Trayd's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Construction
- Payroll
- Human Resources
- Compliance
- Fintech
- Workforce Management
---
