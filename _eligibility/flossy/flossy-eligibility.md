---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Flossy Service is intended for visitors located within the United States.
  entity_types:
  - text: You must be at least 18 years old to use the Flossy Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Flossy Service.
    value: '18'
  restricted_uses:
  - summary: Protected health information
    text: unless you have entered into Business Associate Addendum
  - summary: Illegal or fraudulent use
    text: use the Flossy Service for any illegal purpose or in violation of any local, state, national, or international law
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
name: Flossy
provenance_date: '2026-11-09'
provider_name: Flossy
provider_slug: flossy
slug: flossy-eligibility
source_date: '2026-11-09'
source_filename: flossy-eligibility.yml
source_heading: Eligibility
source_page: https://www.flossy.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flossy\naid: flossy\nurl: https://www.flossy.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Flossy Service is intended for visitors located within the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Flossy Service.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: Protected health information\n  text: unless you have entered\
  \ into Business Associate Addendum\n- summary: Illegal or fraudulent use\n  text: use the Flossy Service for any illegal purpose or in violation of any local, state, national, or international\n    law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Flossy Service.\n"
source_yaml_url: https://artifacts.apis.io/flossy/eligibility/flossy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Flossy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Healthcare
- Dental
- Veterinary
- Scheduling
- Voice
- Practice Management
- Revenue Cycle
---
