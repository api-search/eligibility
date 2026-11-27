---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing or using the Services on behalf of an entity, you represent that you are authorized to accept this Agreement on behalf of that entity
    type: business
  - text: If you are accessing or using the Service in your individual capacity, all references to “User” herein mean you individually.
    type: individual
  - text: If the user or licensee of the Service is an agency, department, or other entity of the United States Government
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Private Health Information only with BAA and Module
    text: Customer agrees not to Submit to the Service any Private Health Information unless (i) the Order Form specifies that customer may do so and includes an applicable Module and (ii) Customer has entered into a Business Associate Agreement (“BAA”) with Prudentia.
  - summary: Export control restrictions
    text: Customer shall not (and shall not permit any of its users to) access or use the Service in violation of any U.S. export embargo, prohibition or restriction
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
name: Prudentia Sciences
provenance_date: '2026-11-10'
provider_name: Prudentia Sciences
provider_slug: prudentia-sciences
slug: prudentia-sciences-eligibility
source_date: '2026-11-10'
source_filename: prudentia-sciences-eligibility.yml
source_heading: Eligibility
source_page: https://www.prudentiasciences.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prudentia Sciences\naid: prudentia-sciences\nurl: https://www.prudentiasciences.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing or using the Services on behalf of an entity, you represent that you are authorized\n    to accept this Agreement on behalf of that entity\n- type: individual\n  text: If you are accessing or using the Service in your individual capacity, all references to “User” herein mean\n    you individually.\n- type: government\n  text: If the user or licensee of the Service is an agency,\
  \ department, or other entity of the United States Government\nrestricted_uses:\n- summary: Private Health Information only with BAA and Module\n  text: Customer agrees not to Submit to the Service any Private Health Information unless (i) the Order Form specifies\n    that customer may do so and includes an applicable Module and (ii) Customer has entered into a Business Associate\n    Agreement (“BAA”) with Prudentia.\n- summary: Export control restrictions\n  text: Customer shall not (and shall not permit any of its users to) access or use the Service in violation of\n    any U.S. export embargo, prohibition or restriction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/prudentia-sciences/eligibility/prudentia-sciences-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Prudentia Sciences's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Life Sciences
- Pharmaceuticals
- Biotechnology
- Mergers and Acquisitions
- Artificial Intelligence
- Data
- Due Diligence
---
