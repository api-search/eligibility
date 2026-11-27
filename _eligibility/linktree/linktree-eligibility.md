---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you must reside in an eligible country for the relevant Monetization Program as defined by us on the Platform and as may be modified by us from time to time
  entity_types:
  - text: If you’re using Linktree on behalf of a business or individual, you confirm that you’re authorized by them to agree to these Terms on their behalf.
    type: business
  minimum_age:
    text: Certain features and services are intended for users who are 18 years of age and older.
    value: null
  restricted_uses:
  - summary: US restricted parties and embargoed countries (app)
    text: You’re not on a US government restricted parties list and you don’t live in a country which is subject to a US government embargo or designated as "terrorist supporting country"
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
name: Linktree
provenance_date: '2026-11-09'
provider_name: Linktree
provider_slug: linktree
slug: linktree-eligibility
source_date: '2026-11-09'
source_filename: linktree-eligibility.yml
source_heading: Eligibility
source_page: https://linktr.ee/s/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Linktree\naid: linktree\nurl: https://linktr.ee/s/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you must reside in an eligible country for the relevant Monetization Program as defined by us on the Platform\n    and as may be modified by us from time to time\nentity_types:\n- type: business\n  text: If you’re using Linktree on behalf of a business or individual, you confirm that you’re authorized by them\n    to agree to these Terms on their behalf.\nrestricted_uses:\n- summary: US restricted parties and embargoed countries (app)\n  text: You’re not on a US government restricted\
  \ parties list and you don’t live in a country which is subject to\n    a US government embargo or designated as \"terrorist supporting country\"\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Certain features and services are intended for users who are 18 years of age and older.\n"
source_yaml_url: https://artifacts.apis.io/linktree/eligibility/linktree-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Linktree's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Media
- Link-in-bio
- Creator Economy
- Social Media
- Marketing
- Analytics
- MCP
- Agents
- Developer Tools
- Australia
---
