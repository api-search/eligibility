---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: 'You must not use the Platform: if you are under the age of 18 unless, if you are a Client, the Practitioner has obtained the consent of your parent or guardian to provide Services to you;'
    value: '18'
  restricted_uses:
  - summary: Self-diagnosis
    text: to attempt to clinically diagnose yourself
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
name: Big Picture Medical
provenance_date: '2026-11-09'
provider_name: Big Picture Medical
provider_slug: big-picture-medical
slug: big-picture-medical-eligibility
source_date: '2026-11-09'
source_filename: big-picture-medical-eligibility.yml
source_heading: Eligibility
source_page: https://www.bigpicturemedical.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Big Picture Medical\naid: big-picture-medical\nurl: https://www.bigpicturemedical.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Self-diagnosis\n  text: to attempt to clinically diagnose yourself\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'You must not use the Platform: if you are under the age of 18 unless, if you are a Client, the Practitioner\n    has obtained the consent of your parent or guardian to provide Services to you;'\n"
source_yaml_url: https://artifacts.apis.io/big-picture-medical/eligibility/big-picture-medical-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Big Picture Medical's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Electronic Health Records
- openEHR
- FHIR
- HL7
- Interoperability
- Clinical Data
- Care Pathways
- Workflows
- Orchestration
- No-Code
- NHS
- United Kingdom
---
