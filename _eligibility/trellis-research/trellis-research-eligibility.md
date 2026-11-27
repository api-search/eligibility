---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not access Trellis outside of the United States.
  entity_types:
  - text: the entity (e.g. company, corporation, partnership, sole proprietor, etc.) using the Online Services or entering into a Subscription Agreement with Trellis.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No consumer eligibility determinations
    text: 'No user may use information included in the Online Services to make any determination regarding an individual consumer''s eligibility for: Credit or insurance for personal, family, or household purposes; Employment; or A government license or benefit.'
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
name: Trellis Research
provenance_date: '2026-11-10'
provider_name: Trellis Research
provider_slug: trellis-research
slug: trellis-research-eligibility
source_date: '2026-11-10'
source_filename: trellis-research-eligibility.yml
source_heading: Eligibility
source_page: https://trellis.law/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trellis Research\naid: trellis-research\nurl: https://trellis.law/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not access Trellis outside of the United States.\nentity_types:\n- type: business\n  text: the entity (e.g. company, corporation, partnership, sole proprietor, etc.) using the Online Services or\n    entering into a Subscription Agreement with Trellis.\nrestricted_uses:\n- summary: No consumer eligibility determinations\n  text: 'No user may use information included in the Online Services to make any determination regarding an individual\n   \
  \ consumer''s eligibility for: Credit or insurance for personal, family, or household purposes; Employment; or\n    A government license or benefit.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trellis-research/eligibility/trellis-research-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Trellis Research's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal
- Legal Research
- Court Records
- Litigation Analytics
- Judicial Analytics
- Legal Data
- MCP
---
