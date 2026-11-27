---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use this Site on behalf of an organization, such as a health provider, references in these Terms of Use to “you” and “your” are intended to be references to you individually and to your organization, both of which are to be bound.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: HIPAA-violating use of site information
    text: you agree not to use, access, combine, or disclose the information available on the Site in such a way that would violate the Health Insurance Portability and Accountability Act (“HIPAA”), its regulations or other applicable law.
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
name: Cohere Health
provenance_date: '2026-11-09'
provider_name: Cohere Health
provider_slug: cohere-health
slug: cohere-health-eligibility
source_date: '2026-11-09'
source_filename: cohere-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.coherehealth.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cohere Health\naid: cohere-health\nurl: https://www.coherehealth.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use this Site on behalf of an organization, such as a health provider, references in these Terms\n    of Use to “you” and “your” are intended to be references to you individually and to your organization, both\n    of which are to be bound.\nrestricted_uses:\n- summary: HIPAA-violating use of site information\n  text: you agree not to use, access, combine, or disclose the information available\
  \ on the Site in such a way that\n    would violate the Health Insurance Portability and Accountability Act (“HIPAA”), its regulations or other applicable\n    law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cohere-health/eligibility/cohere-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Cohere Health's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- United States
- Prior Authorization
- Utilization Management
- Payers
- FHIR
- HL7
- Da Vinci
- SMART on FHIR
- Interoperability
---
