---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Client is the owner, manager, and/or operator of the business(es) set forth in the Basic Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Reasonable Use Policy messaging limits
    text: i) unsolicited communications; ii) telemarketing or any other mass-texting for marketing purposes unless included in Client's Services
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
name: Akia
provenance_date: '2026-11-09'
provider_name: Akia
provider_slug: akia
slug: akia-eligibility
source_date: '2026-11-09'
source_filename: akia-eligibility.yml
source_heading: Eligibility
source_page: https://www.akia.com/msa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Akia\naid: akia\nurl: https://www.akia.com/msa\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Client is the owner, manager, and/or operator of the business(es) set forth in the Basic Terms\nrestricted_uses:\n- summary: Reasonable Use Policy messaging limits\n  text: i) unsolicited communications; ii) telemarketing or any other mass-texting for marketing purposes unless\n    included in Client's Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/akia/eligibility/akia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Akia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hospitality
- Hotels
- Vacation Rentals
- Guest Experience
- Messaging
- Artificial Intelligence
- Agents
- Property Management
- Check-in
---
