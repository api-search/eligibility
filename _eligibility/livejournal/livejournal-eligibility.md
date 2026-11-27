---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service may be used only by individuals aged 14 and above.
    type: individual
  - text: 'The User may not: register a legal entity as a User;'
    type: business
  minimum_age:
    text: The Service may be used only by individuals aged 14 and above.
    value: '14'
  restricted_uses:
  - summary: Political solicitation
    text: post political solicitation materials unless otherwise directly specified in a separate agreement between User and the Administration;
  verification:
    approval_required: null
    kyb: false
    kyc: false
    text: The Administration does not verify that Accounts belong to specific individuals.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LiveJournal
provenance_date: '2026-11-09'
provider_name: LiveJournal
provider_slug: livejournal
slug: livejournal-eligibility
source_date: '2026-11-09'
source_filename: livejournal-eligibility.yml
source_heading: Eligibility
source_page: https://www.livejournal.com/legal/tos-en.bml
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LiveJournal\naid: livejournal\nurl: https://www.livejournal.com/legal/tos-en.bml\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service may be used only by individuals aged 14 and above.\n- type: business\n  text: 'The User may not: register a legal entity as a User;'\nrestricted_uses:\n- summary: Political solicitation\n  text: post political solicitation materials unless otherwise directly specified in a separate agreement between\n    User and the Administration;\nverification:\n  kyc: false\n  kyb: false\n  approval_required:\
  \ null\n  text: The Administration does not verify that Accounts belong to specific individuals.\nminimum_age:\n  value: '14'\n  text: The Service may be used only by individuals aged 14 and above.\n"
source_yaml_url: https://artifacts.apis.io/livejournal/eligibility/livejournal-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from LiveJournal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Blogging
- Social
- Community
---
