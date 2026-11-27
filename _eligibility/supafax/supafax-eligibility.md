---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    type: individual
  minimum_age:
    text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: The Service may only be used in accordance with these Terms and all applicable laws
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
name: Supafax
provenance_date: '2026-11-10'
provider_name: Supafax
provider_slug: supafax
slug: supafax-eligibility
source_date: '2026-11-10'
source_filename: supafax-eligibility.yml
source_heading: Eligibility
source_page: https://www.supafax.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Supafax\naid: supafax\nurl: https://www.supafax.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Service is intended only for access and use by individuals at least eighteen (18) years old.\nrestricted_uses:\n- summary: Unlawful use\n  text: The Service may only be used in accordance with these Terms and all applicable laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Service is intended only for access and use by individuals at least eighteen (18)\
  \ years old.\n"
source_yaml_url: https://artifacts.apis.io/supafax/eligibility/supafax-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Supafax's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email
- Calendar
- AI Assistant
- AI Agents
- Email Automation
- Productivity
- Y Combinator
---
