---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF CUSTOMER IS USING THE SERVICES ON BEHALF OF ANOTHER PERSON OR ENTITY, CUSTOMER HEREBY REPRESENTS AND WARRANTS TO MOTION THAT CUSTOMER HAS THE AUTHORITY TO BIND SUCH PERSON OR SUCH ENTITY TO THIS AGREEMENT.
    type: business
  minimum_age:
    text: YOU HAVE REACHED THE LEGAL AGE OF MAJORITY IN YOUR JURISDICTION
    value: legal age of majority in your jurisdiction
  restricted_uses:
  - summary: Direct competitors barred
    text: MOTION’S DIRECT COMPETITORS ARE PROHIBITED FROM ACCESSING THE SERVICES, EXCEPT WITH MOTION’S PRIOR WRITTEN CONSENT.
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
name: Motion
provenance_date: '2026-11-10'
provider_name: Motion
provider_slug: motion
slug: motion-eligibility
source_date: '2026-11-10'
source_filename: motion-eligibility.yml
source_heading: Eligibility
source_page: https://motionapp.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Motion\naid: motion\nurl: https://motionapp.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF CUSTOMER IS USING THE SERVICES ON BEHALF OF ANOTHER PERSON OR ENTITY, CUSTOMER HEREBY REPRESENTS AND\n    WARRANTS TO MOTION THAT CUSTOMER HAS THE AUTHORITY TO BIND SUCH PERSON OR SUCH ENTITY TO THIS AGREEMENT.\nrestricted_uses:\n- summary: Direct competitors barred\n  text: MOTION’S DIRECT COMPETITORS ARE PROHIBITED FROM ACCESSING THE SERVICES, EXCEPT WITH MOTION’S PRIOR WRITTEN\n    CONSENT.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age of majority in your jurisdiction\n  text: YOU HAVE REACHED THE LEGAL AGE OF MAJORITY IN YOUR JURISDICTION\n"
source_yaml_url: https://artifacts.apis.io/motion/eligibility/motion-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Motion's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Creative Analytics
- Advertising
- Marketing Analytics
- Performance Marketing
- Ad Reporting
- Creative Strategy
- Software-as-a-Service
- MCP
- Agent Surface
---
