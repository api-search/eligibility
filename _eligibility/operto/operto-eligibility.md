---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Offerings are offered and controlled by Operto from its facilities in Canada. Operto makes no representations that the Offerings are appropriate or available for use in other locations.
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity to these terms and conditions
    type: business
  minimum_age:
    text: null
    value: null
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
name: Operto
provenance_date: '2026-11-10'
provider_name: Operto
provider_slug: operto
slug: operto-eligibility
source_date: '2026-11-10'
source_filename: operto-eligibility.yml
source_heading: Eligibility
source_page: https://operto.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Operto\naid: operto\nurl: https://operto.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Offerings are offered and controlled by Operto from its facilities in Canada. Operto makes no representations\n    that the Offerings are appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such entity to these terms and conditions\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/operto/eligibility/operto-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Operto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hospitality
- Property Management
- Guest Experience
- Automation
---
