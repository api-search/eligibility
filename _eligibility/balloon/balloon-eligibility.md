---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using our Services on behalf of a business or employer, that business or employer accepts these terms.
    type: business
  minimum_age:
    text: Our Services are diverse, so sometimes additional terms or product requirements (including age requirements) may apply.
    value: null
  restricted_uses:
  - summary: Use only as permitted by law
    text: You may use our Services only as permitted by law, including applicable export and re-export control laws and regulations.
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
name: Balloon
provenance_date: '2026-11-09'
provider_name: Balloon
provider_slug: balloon
slug: balloon-eligibility
source_date: '2026-11-09'
source_filename: balloon-eligibility.yml
source_heading: Eligibility
source_page: https://getballoon.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Balloon\naid: balloon\nurl: https://getballoon.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using our Services on behalf of a business or employer, that business or employer accepts these\n    terms.\nrestricted_uses:\n- summary: Use only as permitted by law\n  text: You may use our Services only as permitted by law, including applicable export and re-export control laws\n    and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ Our Services are diverse, so sometimes additional terms or product requirements (including age requirements)\n    may apply.\n"
source_yaml_url: https://artifacts.apis.io/balloon/eligibility/balloon-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Balloon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Collaboration
- Team Collaboration
- Decision-Making
- Employee Engagement
- Meetings
- Productivity
- Anonymous Feedback
---
