---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: reside in the United States of America
  entity_types:
  - text: If you use the Services on behalf of an entity, you represent and warrant that you have the authority to bind that entity
    type: business
  minimum_age:
    text: at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No emergency, legal, or financial advice via HearthAI
    text: Use the Services or HearthAI to provide emergency instructions, legal advice, financial advice, or any regulated professional guidance
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
name: Hearth
provenance_date: '2026-11-09'
provider_name: Hearth
provider_slug: hearth
slug: hearth-eligibility
source_date: '2026-11-09'
source_filename: hearth-eligibility.yml
source_heading: Eligibility
source_page: https://gethearth.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hearth\naid: hearth\nurl: https://gethearth.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: reside in the United States of America\nentity_types:\n- type: business\n  text: If you use the Services on behalf of an entity, you represent and warrant that you have the authority to\n    bind that entity\nrestricted_uses:\n- summary: No emergency, legal, or financial advice via HearthAI\n  text: Use the Services or HearthAI to provide emergency instructions, legal advice, financial advice, or any regulated\n    professional guidance\nverification:\n \
  \ kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/hearth/eligibility/hearth-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Hearth's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Contractors
- Home Improvement
- Financing
- Payments
- Invoicing
- Scheduling
- Field Service Management
- AI Assistant
- Software-as-a-Service
---
