---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF AN INDIVIDUAL IS ENTERING INTO THIS AGREEMENT ON BEHALF OF A LEGAL ENTITY, SUCH PERSON REPRESENTS AND WARRANTS THAT IT HAS THE LEGAL AUTHORITY TO BIND SUCH LEGAL ENTITY
    type: business
  minimum_age:
    text: THE SERVICE IS INTENDED FOR THE CUSTOMER AND ITS AUTHORIZED USERS ONLY AND IS NOT FOR USE BY CHILDREN UNDER 13 YEARS OF AGE.
    value: '13'
  restricted_uses:
  - summary: Prohibited Use
    text: use the Service to conduct any fraudulent, malicious, or illegal activities
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
name: Fable
provenance_date: '2026-11-09'
provider_name: Fable
provider_slug: fable
slug: fable-eligibility
source_date: '2026-11-09'
source_filename: fable-eligibility.yml
source_heading: Eligibility
source_page: https://fablesecurity.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fable\naid: fable\nurl: https://fablesecurity.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF AN INDIVIDUAL IS ENTERING INTO THIS AGREEMENT ON BEHALF OF A LEGAL ENTITY, SUCH PERSON REPRESENTS AND\n    WARRANTS THAT IT HAS THE LEGAL AUTHORITY TO BIND SUCH LEGAL ENTITY\nrestricted_uses:\n- summary: Prohibited Use\n  text: use the Service to conduct any fraudulent, malicious, or illegal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text:\
  \ THE SERVICE IS INTENDED FOR THE CUSTOMER AND ITS AUTHORIZED USERS ONLY AND IS NOT FOR USE BY CHILDREN UNDER\n    13 YEARS OF AGE.\n"
source_yaml_url: https://artifacts.apis.io/fable/eligibility/fable-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Security Awareness
- Human Risk Management
- Phishing Simulation
- Security Training
- Compliance
- Artificial Intelligence
---
