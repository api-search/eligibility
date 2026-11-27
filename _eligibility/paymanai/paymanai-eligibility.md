---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.
    type: individual
  - text: The Service enables you to create your own AI agents to pay real people, both individuals and businesses
    type: business
  minimum_age:
    text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.
    value: '18'
  restricted_uses:
  - summary: Restricted industries
    text: Casinos, gambling, or gaming (online or physical)
  - summary: Competitors barred
    text: No employee, independent contractor, agent, or affiliate of any company that provides AI-to-human payment infrastructure or automated payment agent services is permitted to view, access, or use any portion of the Service without express written permission from Payman.
  - summary: Prohibited activities
    text: Use any data mining, robots, scraping, or similar data gathering methods.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: As part of the registration process, you must submit a Statement of Use describing your intended use of the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Payman AI, Inc
provenance_date: '2026-11-10'
provider_name: Payman AI, Inc
provider_slug: paymanai
slug: paymanai-eligibility
source_date: '2026-11-10'
source_filename: paymanai-eligibility.yml
source_heading: Eligibility
source_page: https://paymanai.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Payman AI, Inc\naid: paymanai\nurl: https://paymanai.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.\n- type: business\n  text: The Service enables you to create your own AI agents to pay real people, both individuals and businesses\nrestricted_uses:\n- summary: Restricted industries\n  text: Casinos, gambling, or gaming (online or physical)\n- summary: Competitors barred\n  text: No employee, independent contractor,\
  \ agent, or affiliate of any company that provides AI-to-human payment\n    infrastructure or automated payment agent services is permitted to view, access, or use any portion of the Service\n    without express written permission from Payman.\n- summary: Prohibited activities\n  text: Use any data mining, robots, scraping, or similar data gathering methods.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: As part of the registration process, you must submit a Statement of Use describing your intended use of\n    the Services.\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/paymanai/eligibility/paymanai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Payman AI, Inc's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Banking
- Fintech
- AI Agents
---
