---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally capable of entering into a binding agreement to use the Site or purchase services from us.
    type: individual
  - text: If you use the Site on behalf of a corporation, nonprofit organization, association, or other entity, you represent that you have authority to bind that entity to these Terms.
    type: nonprofit
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited activity
    text: 'You may not: use the Site to violate any law, regulation, court order, agency rule, or third-party right'
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
name: 501c3.HELP
provenance_date: '2026-11-09'
provider_name: 501c3.HELP
provider_slug: 501c3-help
slug: 501c3-help-eligibility
source_date: '2026-11-09'
source_filename: 501c3-help-eligibility.yml
source_heading: Eligibility
source_page: https://501c3.help/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 501c3.HELP\naid: 501c3-help\nurl: https://501c3.help/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally capable of entering into a binding agreement to use the Site\n    or purchase services from us.\n- type: nonprofit\n  text: If you use the Site on behalf of a corporation, nonprofit organization, association, or other entity, you\n    represent that you have authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Unlawful or prohibited activity\n  text: 'You may\
  \ not: use the Site to violate any law, regulation, court order, agency rule, or third-party right'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/501c3-help/eligibility/501c3-help-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from 501c3.HELP's own page on 2026-11-09.
synthetic: false
tags:
- Non-Profit
- Legal
- Funding
- Education
---
