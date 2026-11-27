---
api_specs:
- filename: 2sAYQZJYMC
  format: yaml
  label: GreyMatter API
  slug: greymatter-api
  spec_type: Postman
  url: https://apidocs.myreliaquest.com/api/collections/39440280/2sAYQZJYMC?segregateAuth=true&versionTag=latest
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents and warrants that Customer is not located in, or under the control of, or a national or resident of, an Embargoed Country or Designated National.
  entity_types:
  - text: ON BEHALF OF YOURSELF AND THE COMPANY OR OTHER LEGAL ENTITY FOR WHICH YOU ARE ACTING
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal, harmful, or fraudulent purposes
    text: use the ReliaQuest Platform for any illegal, harmful, or fraudulent purposes
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
name: ReliaQuest
provenance_date: '2026-11-10'
provider_name: ReliaQuest
provider_slug: reliaquest
slug: reliaquest-eligibility
source_date: '2026-11-10'
source_filename: reliaquest-eligibility.yml
source_heading: Eligibility
source_page: https://reliaquest.com/greymatter-psa/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ReliaQuest\naid: reliaquest\nurl: https://reliaquest.com/greymatter-psa/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents and warrants that Customer is not located in, or under the control of, or a national\n    or resident of, an Embargoed Country or Designated National.\nentity_types:\n- type: business\n  text: ON BEHALF OF YOURSELF AND THE COMPANY OR OTHER LEGAL ENTITY FOR WHICH YOU ARE ACTING\nrestricted_uses:\n- summary: Illegal, harmful, or fraudulent purposes\n  text: use the ReliaQuest Platform for any illegal, harmful, or fraudulent\
  \ purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/reliaquest/eligibility/reliaquest-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from ReliaQuest's own page on 2026-11-10.
synthetic: false
tags:
- Cybersecurity
- Security Operations
- Threat Detection
- Incident Response
- Threat Intelligence
- Digital Risk Protection
- AI Agents
- GraphQL
---
