---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with Growth Hackers and are not barred from using the Services under applicable law.
    type: individual
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Services only if you are 18 years or older
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you may need to provide additional information to verify your identity before completing your Transaction
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GrowthHackers
provenance_date: '2026-11-09'
provider_name: GrowthHackers
provider_slug: growthhackers
slug: growthhackers-eligibility
source_date: '2026-11-09'
source_filename: growthhackers-eligibility.yml
source_heading: Eligibility
source_page: https://growthhackers.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GrowthHackers\naid: growthhackers\nurl: https://growthhackers.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with\n    Growth Hackers and are not barred from using the Services under applicable law.\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that company\
  \ or other legal entity to\n    these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you may need to provide additional information to verify your identity before completing your Transaction\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/growthhackers/eligibility/growthhackers-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from GrowthHackers's own page on 2026-11-09.
synthetic: false
tags:
- Community
- Growth Hacking
- Marketing
- Growth Marketing
- Experimentation
- Content Marketing
- Event
- Education
- Agency Services
- AI Marketing
---
