---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of a local government, municipality, agency, or other legal entity, you represent that you have the authority to bind such entity to these Terms.
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Access limited to authorized personnel
    text: Access to the Platform is restricted to personnel authorized by the Customer ("Authorized Users").
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
name: Verdant
provenance_date: '2026-11-10'
provider_name: Verdant
provider_slug: verdant
slug: verdant-eligibility
source_date: '2026-11-10'
source_filename: verdant-eligibility.yml
source_heading: Eligibility
source_page: https://www.verdantapp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Verdant\naid: verdant\nurl: https://www.verdantapp.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: If you are entering into these Terms on behalf of a local government, municipality, agency, or other legal\n    entity, you represent that you have the authority to bind such entity to these Terms.\nrestricted_uses:\n- summary: Access limited to authorized personnel\n  text: Access to the Platform is restricted to personnel authorized by the Customer (\"Authorized Users\").\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/verdant/eligibility/verdant-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Verdant's own page on 2026-11-10.
synthetic: false
tags:
- Company
- GovTech
- Permitting
- Local Government
- Land Use Planning
- Artificial Intelligence
- Software-as-a-Service
---
