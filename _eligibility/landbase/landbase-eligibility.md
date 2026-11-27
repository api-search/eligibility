---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: Customer will not permit any User to access or use any Service or Content in a U.S.-embargoed country or region (currently the Crimea, Luhansk or Donetsk regions, Cuba, Iran, North Korea, Sudan or Syria)
  entity_types:
  - text: the individual, company, organization, or other entity that accepts this Agreement
    type: individual
  - text: If Customer is a company, organization, or other entity, the individual accepting this Agreement on Customer’s behalf represents and warrants that they have authority to bind Customer to this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No discriminatory or hateful promotion
    text: (d) promote or engage in discrimination, harassment or hate speech.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Landbase
provenance_date: '2026-11-09'
provider_name: Landbase
provider_slug: landbase
slug: landbase-eligibility
source_date: '2026-11-09'
source_filename: landbase-eligibility.yml
source_heading: Eligibility
source_page: https://www.landbase.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Landbase\naid: landbase\nurl: https://www.landbase.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Customer will not permit any User to access or use any Service or Content in a U.S.-embargoed country or\n    region (currently the Crimea, Luhansk or Donetsk regions, Cuba, Iran, North Korea, Sudan or Syria)\nentity_types:\n- type: individual\n  text: the individual, company, organization, or other entity that accepts this Agreement\n- type: business\n  text: If Customer is a company, organization, or other entity, the\
  \ individual accepting this Agreement on Customer’s\n    behalf represents and warrants that they have authority to bind Customer to this Agreement.\nrestricted_uses:\n- summary: No discriminatory or hateful promotion\n  text: (d) promote or engage in discrimination, harassment or hate speech.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/landbase/eligibility/landbase-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Landbase's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Go-To-Market
- Sales
- Marketing
- B2B Data
- Data Enrichment
- Artificial Intelligence
- Agents
- Command Line Interface
- Lead Generation
---
