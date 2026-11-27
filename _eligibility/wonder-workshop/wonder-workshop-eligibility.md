---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: MORAVIA Education makes no claims that the Services may be lawfully viewed, downloaded, or accessed outside of the United States.
  entity_types:
  - text: You must be 18 years of age or older and have a valid credit card number to purchase any Wonder Workshop Products on Our Website.
    type: individual
  - text: Paid accounts are licensed to individuals and institutions that paid for the service.
    type: business
  minimum_age:
    text: By creating an Account, You represent and warrant that You are at least 13 years of age and, if You are a minor, You have Your parent’s permission to access or use the Services and to create an Account.
    value: '13'
  restricted_uses:
  - summary: For-profit uses need written approval
    text: For Profit Uses include, but is not limited to, the use any Services in any in-person or virtual class, workshop, webinar, bootcamp or other for-profit educational setting where participants are charged fees for their participation.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Entities or individuals who would like to use any Services for a For Profit Use may submit a proposal to us detailing the nature of the intended use
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wonder Workshop
provenance_date: '2026-11-10'
provider_name: Wonder Workshop
provider_slug: wonder-workshop
slug: wonder-workshop-eligibility
source_date: '2026-11-10'
source_filename: wonder-workshop-eligibility.yml
source_heading: Eligibility
source_page: https://www.makewonder.com:443/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wonder Workshop\naid: wonder-workshop\nurl: https://www.makewonder.com:443/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: MORAVIA Education makes no claims that the Services may be lawfully viewed, downloaded, or accessed outside\n    of the United States.\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older and have a valid credit card number to purchase any Wonder Workshop\n    Products on Our Website.\n- type: business\n  text: Paid accounts are licensed to individuals and institutions that paid for the service.\nrestricted_uses:\n- summary: For-profit\
  \ uses need written approval\n  text: For Profit Uses include, but is not limited to, the use any Services in any in-person or virtual class,\n    workshop, webinar, bootcamp or other for-profit educational setting where participants are charged fees for\n    their participation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Entities or individuals who would like to use any Services for a For Profit Use may submit a proposal to\n    us detailing the nature of the intended use\nminimum_age:\n  value: '13'\n  text: By creating an Account, You represent and warrant that You are at least 13 years of age and, if You are\n    a minor, You have Your parent’s permission to access or use the Services and to create an Account.\n"
source_yaml_url: https://artifacts.apis.io/wonder-workshop/eligibility/wonder-workshop-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Wonder Workshop's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Frontier Tech
- Education
- EdTech
- Robotics
- Coding
- STEM
- SDK
---
