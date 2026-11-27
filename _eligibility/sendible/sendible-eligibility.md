---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms that may apply to our site or any content on it.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consumer commercial use
    text: You agree not to use our site for any commercial or business purposes
  - summary: Sanctions and export restrictions
    text: You warrant that the Services shall not be used by or for the benefit of any entity or individual on a sanction list, or any entity owned/controlled by such parties.
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
name: Sendible
provenance_date: '2026-11-10'
provider_name: Sendible
provider_slug: sendible
slug: sendible-eligibility
source_date: '2026-11-10'
source_filename: sendible-eligibility.yml
source_heading: Eligibility
source_page: https://www.sendible.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sendible\naid: sendible\nurl: https://www.sendible.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms\n    that may apply to our site or any content on it.'\nrestricted_uses:\n- summary: Consumer commercial use\n  text: You agree not to use our site for any commercial or business purposes\n- summary: Sanctions and export restrictions\n  text: You warrant that the Services shall not be used by or for the benefit of any entity\
  \ or individual on a sanction\n    list, or any entity owned/controlled by such parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sendible/eligibility/sendible-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Sendible's own page on 2026-11-10.
synthetic: false
tags:
- Social Media
- Social Media Management
- Agencies
- Scheduling
- Analytics
- Monitoring
---
