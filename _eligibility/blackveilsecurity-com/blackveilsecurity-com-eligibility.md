---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept these Terms on behalf of an organisation, you represent that you have authority to bind that organisation
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Active testing requires authorisation
    text: Active or authenticated testing requires verified control of the target or explicit authorisation from its owner.
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
name: BlackVeil
provenance_date: '2026-11-09'
provider_name: BlackVeil
provider_slug: blackveilsecurity-com
slug: blackveilsecurity-com-eligibility
source_date: '2026-11-09'
source_filename: blackveilsecurity-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.blackveilsecurity.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlackVeil\naid: blackveilsecurity-com\nurl: https://www.blackveilsecurity.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept these Terms on behalf of an organisation, you represent that you have authority to bind that\n    organisation\nrestricted_uses:\n- summary: Active testing requires authorisation\n  text: Active or authenticated testing requires verified control of the target or explicit authorisation from its\n    owner.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blackveilsecurity-com/eligibility/blackveilsecurity-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from BlackVeil's own page on 2026-11-09.
synthetic: false
tags:
- Security
- DNS
- Email Authentication
- Domain Monitoring
- Software-as-a-Service
---
