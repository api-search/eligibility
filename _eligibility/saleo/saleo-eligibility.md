---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  - text: in the case of an individual accepting this Agreement on such individual’s own behalf, such individual
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Direct competitors barred
    text: Customer may not access the Services if Customer is direct competitor of Consensus, except with Consensus’ prior written consent.
  - summary: Excluded regulated data
    text: Customer shall not provide Consensus with any Customer Data that is subject to heightened security requirements by law, regulation or contract
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
name: Saleo
provenance_date: '2026-11-10'
provider_name: Saleo
provider_slug: saleo
slug: saleo-eligibility
source_date: '2026-11-10'
source_filename: saleo-eligibility.yml
source_heading: Eligibility
source_page: https://goconsensus.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Saleo\naid: saleo\nurl: https://goconsensus.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\n- type: individual\n  text: in the case of an individual accepting this Agreement on such individual’s own behalf, such individual\nrestricted_uses:\n- summary: Direct competitors barred\n  text: Customer may not access the Services if Customer is direct\
  \ competitor of Consensus, except with Consensus’\n    prior written consent.\n- summary: Excluded regulated data\n  text: Customer shall not provide Consensus with any Customer Data that is subject to heightened security requirements\n    by law, regulation or contract\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/saleo/eligibility/saleo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Saleo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales Tech
- Demo Automation
- Sales Enablement
- Presales
- Go-To-Market
- AI Agents
- SCIM
- Identity Provisioning
- SSO
- Interactive Demos
- Product Tours
---
