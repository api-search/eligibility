---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the DevInsight Services only if you can form a binding contract with us
    type: individual
  - text: 'If you open a DevInsight Account on behalf of a company, organization, or other entity, then: (a) “you” includes you and that entity'
    type: business
  minimum_age:
    text: Any use or access to the DevInsight Services by anyone under eighteen (18) years of age is strictly prohibited
    value: '18'
  restricted_uses:
  - summary: Direct competitors of Merico
    text: access the DevInsight Services if you are a direct competitor of Merico, except with our prior written consent
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
name: Merico
provenance_date: '2026-11-10'
provider_name: Merico
provider_slug: merico
slug: merico-eligibility
source_date: '2026-11-10'
source_filename: merico-eligibility.yml
source_heading: Eligibility
source_page: https://www.devinsight.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Merico\naid: merico\nurl: https://www.devinsight.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the DevInsight Services only if you can form a binding contract with us\n- type: business\n  text: 'If you open a DevInsight Account on behalf of a company, organization, or other entity, then: (a) “you”\n    includes you and that entity'\nrestricted_uses:\n- summary: Direct competitors of Merico\n  text: access the DevInsight Services if you are a direct competitor of Merico, except with our prior written\
  \ consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Any use or access to the DevInsight Services by anyone under eighteen (18) years of age is strictly prohibited\n"
source_yaml_url: https://artifacts.apis.io/merico/eligibility/merico-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Merico's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Developer Tools
- Engineering Intelligence
- DevOps
- DORA Metrics
- Software Analytics
- Open Source
- Data Platform
- Technology
- Analytics
- Software Engineering
---
