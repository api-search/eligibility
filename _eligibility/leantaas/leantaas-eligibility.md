---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: LeanTaaS makes no claim that the Service may be used or accessed outside the United States.
  entity_types:
  - text: If you accept these Terms on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that legal entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Patient data compliance
    text: You will comply with all applicable laws regarding any use of the Services to store or transmit any Patient Data.
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
name: LeanTaaS
provenance_date: '2026-11-09'
provider_name: LeanTaaS
provider_slug: leantaas
slug: leantaas-eligibility
source_date: '2026-11-09'
source_filename: leantaas-eligibility.yml
source_heading: Eligibility
source_page: https://leantaas.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LeanTaaS\naid: leantaas\nurl: https://leantaas.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: LeanTaaS makes no claim that the Service may be used or accessed outside the United States.\nentity_types:\n- type: business\n  text: If you accept these Terms on behalf of a company or other legal entity, you represent and warrant that you\n    have the authority to bind that legal entity\nrestricted_uses:\n- summary: Patient data compliance\n  text: You will comply with all applicable laws regarding any use of the Services to store or transmit any Patient\n    Data.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/leantaas/eligibility/leantaas-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from LeanTaaS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Systems
- Hospital Operations
- Capacity Management
- Artificial Intelligence
- Machine Learning
- Predictive Analytics
- Scheduling
- Software-as-a-Service
---
