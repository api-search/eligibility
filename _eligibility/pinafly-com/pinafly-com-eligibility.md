---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing on behalf of an organisation, you confirm you have authority to bind it.
    type: business
  minimum_age:
    text: You must be old enough to form a binding contract where you live.
    value: null
  restricted_uses:
  - summary: Material without rights or lawful basis
    text: capture or share material you have no right to capture or share
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
name: pinafly-com
provenance_date: '2026-11-10'
provider_name: pinafly-com
provider_slug: pinafly-com
slug: pinafly-com-eligibility
source_date: '2026-11-10'
source_filename: pinafly-com-eligibility.yml
source_heading: Eligibility
source_page: https://pinafly.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pinafly-com\naid: pinafly-com\nurl: https://pinafly.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are agreeing on behalf of an organisation, you confirm you have authority to bind it.\nrestricted_uses:\n- summary: Material without rights or lawful basis\n  text: capture or share material you have no right to capture or share\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be old enough to form a binding contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/pinafly-com/eligibility/pinafly-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from pinafly-com's own page on 2026-11-10.
synthetic: false
tags:
- Review
- Artificial Intelligence
- Collaboration
- Feedback
- Web App
---
