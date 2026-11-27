---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are only available to users who can form legally binding contracts under applicable law.
    type: individual
  - text: If you are using the Services on behalf of an entity, you represent and warrant that you are authorized to accept these Terms on such entity’s behalf.
    type: business
  minimum_age:
    text: By accessing or using the Services, you represent that you are at least eighteen (18) years of age, or over the age of majority in the state or country where you are a resident or citizen.
    value: '18'
  restricted_uses:
  - summary: Uses beyond described purposes
    text: Use of the Services or Content for any purpose other than what is described in this Section is prohibited.
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
name: CareStack
provenance_date: '2026-11-09'
provider_name: CareStack
provider_slug: carestack
slug: carestack-eligibility
source_date: '2026-11-09'
source_filename: carestack-eligibility.yml
source_heading: Eligibility
source_page: https://carestack.com/legal/2020-1/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CareStack\naid: carestack\nurl: https://carestack.com/legal/2020-1/termsofuse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are only available to users who can form legally binding contracts under applicable law.\n- type: business\n  text: If you are using the Services on behalf of an entity, you represent and warrant that you are authorized\n    to accept these Terms on such entity’s behalf.\nrestricted_uses:\n- summary: Uses beyond described purposes\n  text: Use of the Services or Content for any purpose other than\
  \ what is described in this Section is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By accessing or using the Services, you represent that you are at least eighteen (18) years of age, or over\n    the age of majority in the state or country where you are a resident or citizen.\n"
source_yaml_url: https://artifacts.apis.io/carestack/eligibility/carestack-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CareStack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Dental
- Practice Management
- Electronic Health Records
- Revenue Cycle Management
- Patient Engagement
- Payments
- Software-as-a-Service
---
