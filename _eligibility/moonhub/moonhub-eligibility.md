---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service may not be imported, exported, transferred, licensed, released, or accessed into any countries that are subject to U.S. economic sanctions
  entity_types:
  - text: IF YOU ARE USING THE SERVICES AS AN EMPLOYER, YOU ACKNOWLEDGE THAT YOU ARE NOT MISREPRESENTING ANY INFORMATION REGARDING YOUR TALENT ACQUISITION NEEDS
    type: business
  - text: IF YOU ARE USING THE SERVICES AS AN INDIVIDUAL, YOU ACKNOWLEDGE THAT YOU ARE NOT MISREPRESENTING ANY INFORMATION DURING YOUR ENROLLMENT OR USE OF THE SERVICE
    type: individual
  minimum_age:
    text: YOU MUST BE AT LEAST 18 YEARS OLD TO USE THIS SERVICE.
    value: '18'
  restricted_uses:
  - summary: Employer use limited to talent acquisition
    text: WILL ONLY BE UTILIZING THE SERVICE FOR TALENT ACQUISITION PURPOSES.
  - summary: Individual account limited to one person
    text: Access to the Services as an individual account is limited to a single individual person.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You understand that you must pass the required identity verification protocols each time you attempt to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Moonhub
provenance_date: '2026-11-10'
provider_name: Moonhub
provider_slug: moonhub
slug: moonhub-eligibility
source_date: '2026-11-10'
source_filename: moonhub-eligibility.yml
source_heading: Eligibility
source_page: https://www.moonhub.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moonhub\naid: moonhub\nurl: https://www.moonhub.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service may not be imported, exported, transferred, licensed, released, or accessed into any countries\n    that are subject to U.S. economic sanctions\nentity_types:\n- type: business\n  text: IF YOU ARE USING THE SERVICES AS AN EMPLOYER, YOU ACKNOWLEDGE THAT YOU ARE NOT MISREPRESENTING ANY INFORMATION\n    REGARDING YOUR TALENT ACQUISITION NEEDS\n- type: individual\n  text: IF YOU ARE USING THE SERVICES AS AN INDIVIDUAL, YOU ACKNOWLEDGE THAT YOU ARE NOT MISREPRESENTING ANY\
  \ INFORMATION\n    DURING YOUR ENROLLMENT OR USE OF THE SERVICE\nrestricted_uses:\n- summary: Employer use limited to talent acquisition\n  text: WILL ONLY BE UTILIZING THE SERVICE FOR TALENT ACQUISITION PURPOSES.\n- summary: Individual account limited to one person\n  text: Access to the Services as an individual account is limited to a single individual person.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You understand that you must pass the required identity verification protocols each time you attempt to\n    use the Services.\nminimum_age:\n  value: '18'\n  text: YOU MUST BE AT LEAST 18 YEARS OLD TO USE THIS SERVICE.\n"
source_yaml_url: https://artifacts.apis.io/moonhub/eligibility/moonhub-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Moonhub's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Recruiting
- Talent Acquisition
- Hiring
- AI Agents
- Human Resources
- Sourcing
---
