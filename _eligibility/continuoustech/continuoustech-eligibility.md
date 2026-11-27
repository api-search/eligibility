---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the individual accepting these terms is accepting on behalf of a company or other legal entity, such individual represents that they have the authority to bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and weapons restrictions
    text: The Products are further restricted from being used for the design or development of nuclear, chemical, or biological weapons or missile technology, or for terrorist activity, without the prior permission of the United States government.
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
name: Continuous
provenance_date: '2026-11-09'
provider_name: Continuous
provider_slug: continuoustech
slug: continuoustech-eligibility
source_date: '2026-11-09'
source_filename: continuoustech-eligibility.yml
source_heading: Eligibility
source_page: https://www.continuoustech.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Continuous\naid: continuoustech\nurl: https://www.continuoustech.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If the individual accepting these terms is accepting on behalf of a company or other legal entity, such\n    individual represents that they have the authority to bind such entity\nrestricted_uses:\n- summary: Export and weapons restrictions\n  text: The Products are further restricted from being used for the design or development of nuclear, chemical,\n    or biological weapons or missile technology,\
  \ or for terrorist activity, without the prior permission of the\n    United States government.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/continuoustech/eligibility/continuoustech-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Continuous's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Software-as-a-Service
- Integration
- Automation
- Revenue
---
