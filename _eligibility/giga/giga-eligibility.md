---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'You represent and warrant that: You are not located in a country that is subject to the United States government embargo, or that has been designated by the United States government as a “terrorist supporting” country'
  entity_types:
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: business
  minimum_age:
    text: You represent that You are over the age of 18. The Company does not permit those under 18 to use the Service.
    value: '18'
  restricted_uses:
  - summary: Prohibited uses per separate policy
    text: 'Prohibited Use Policy : describes the uses of the Giga Platform and Giga Services that are not permitted.'
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
name: Giga
provenance_date: '2026-11-09'
provider_name: Giga
provider_slug: giga
slug: giga-eligibility
source_date: '2026-11-09'
source_filename: giga-eligibility.yml
source_heading: Eligibility
source_page: https://giga.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Giga\naid: giga\nurl: https://giga.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'You represent and warrant that: You are not located in a country that is subject to the United States government\n    embargo, or that has been designated by the United States government as a “terrorist supporting” country'\nentity_types:\n- type: business\n  text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service\nrestricted_uses:\n- summary: Prohibited uses per\
  \ separate policy\n  text: 'Prohibited Use Policy : describes the uses of the Giga Platform and Giga Services that are not permitted.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that You are over the age of 18. The Company does not permit those under 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/giga/eligibility/giga-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Giga's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Voice AI
- Customer Service
- Conversational AI
- Contact Center
- Enterprise
---
