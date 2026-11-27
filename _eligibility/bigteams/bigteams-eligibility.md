---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: are under the age of 18
    value: '18'
  restricted_uses:
  - summary: Users under 18 may not post content
    text: Post content or edit our content, the Websites, tools, or other aspects or features of the Services if you are not able to form legally binding contracts, are under the age of 18
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
name: BigTeams
provenance_date: '2026-11-09'
provider_name: BigTeams
provider_slug: bigteams
slug: bigteams-eligibility
source_date: '2026-11-09'
source_filename: bigteams-eligibility.yml
source_heading: Eligibility
source_page: https://www.bigteams.com/terms-conditions-big-teams/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BigTeams\naid: bigteams\nurl: https://www.bigteams.com/terms-conditions-big-teams/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Users under 18 may not post content\n  text: Post content or edit our content, the Websites, tools, or other aspects or features of the Services if you\n    are not able to form legally binding contracts, are under the age of 18\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: are under the age of 18\n"
source_yaml_url: https://artifacts.apis.io/bigteams/eligibility/bigteams-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from BigTeams's own page on 2026-11-09.
synthetic: false
tags:
- Athletic Software
- K-12
- Scheduling
- Team Management
- USA
- Canada
---
