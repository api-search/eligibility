---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The page refers to export restrictions on 'U.S. embargoed countries' and 'unsupported locations' but does not name specific countries.
  entity_types:
  - text: if you are using the Service for an organization, company or other entity, the organization, company, or other entity that you represent
    type: business
  minimum_age:
    text: You must be at least 18 years old or the minimum age required to consent to use the Services in your location, whichever is higher.
    value: '18'
  restricted_uses:
  - summary: Life-critical uses
    text: you will not use the Services for activities where use or failure of the Services could lead to death, personal injury, or environmental damage, including life support systems, emergency services, nuclear facilities, autonomous vehicles, or air traffic control.
  - summary: High-risk domains require human review
    text: when using our Services to provide advice, recommendations, or subjective decisions that directly impact individuals in high-risk domains, a qualified professional in that field must review the content or decision prior to dissemination or finalization.
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
name: Vercept
provenance_date: '2026-11-10'
provider_name: Vercept
provider_slug: vercept
slug: vercept-eligibility
source_date: '2026-11-10'
source_filename: vercept-eligibility.yml
source_heading: Eligibility
source_page: https://vercept.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vercept\naid: vercept\nurl: https://vercept.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The page refers to export restrictions on 'U.S. embargoed countries' and 'unsupported locations' but does\n    not name specific countries.\nentity_types:\n- type: business\n  text: if you are using the Service for an organization, company or other entity, the organization, company, or\n    other entity that you represent\nrestricted_uses:\n- summary: Life-critical uses\n  text: you will not use the Services for activities where use or failure of the Services could lead to death,\
  \ personal\n    injury, or environmental damage, including life support systems, emergency services, nuclear facilities, autonomous\n    vehicles, or air traffic control.\n- summary: High-risk domains require human review\n  text: when using our Services to provide advice, recommendations, or subjective decisions that directly impact\n    individuals in high-risk domains, a qualified professional in that field must review the content or decision\n    prior to dissemination or finalization.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or the minimum age required to consent to use the Services in your location,\n    whichever is higher.\n"
source_yaml_url: https://artifacts.apis.io/vercept/eligibility/vercept-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Vercept's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Computer Use
- Desktop Automation
- Productivity
---
