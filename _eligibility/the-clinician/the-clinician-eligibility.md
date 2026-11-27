---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By accepting these Terms and accessing our Services, you are confirming to being over 18 years of age and therefore, eligible to give your explicit consent. If you are less than 18 years of age, you must have your parent or legal guardian's permission
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You may use the Services only as permitted by law
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
name: The Clinician
provenance_date: '2026-11-10'
provider_name: The Clinician
provider_slug: the-clinician
slug: the-clinician-eligibility
source_date: '2026-11-10'
source_filename: the-clinician-eligibility.yml
source_heading: Eligibility
source_page: https://theclinician.com/#/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The Clinician\naid: the-clinician\nurl: https://theclinician.com/#/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: You may use the Services only as permitted by law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By accepting these Terms and accessing our Services, you are confirming to being over 18 years of age and\n    therefore, eligible to give your explicit consent. If you are less than 18 years of age, you must have\
  \ your\n    parent or legal guardian's permission\n"
source_yaml_url: https://artifacts.apis.io/the-clinician/eligibility/the-clinician-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from The Clinician's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health IT
- Patient Reported Outcomes
- PROMs
- Value-Based Care
- Clinical Data
- Interoperability
- FHIR
- openEHR
- Digital Health
- New Zealand
---
