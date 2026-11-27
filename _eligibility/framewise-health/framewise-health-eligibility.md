---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: SMS program enrollment
    text: Enrollment is not open to the general public.
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
name: Framewise Health
provenance_date: '2026-11-09'
provider_name: Framewise Health
provider_slug: framewise-health
slug: framewise-health-eligibility
source_date: '2026-11-09'
source_filename: framewise-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.framewisehealth.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Framewise Health\naid: framewise-health\nurl: https://www.framewisehealth.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: SMS program enrollment\n  text: Enrollment is not open to the general public.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/framewise-health/eligibility/framewise-health-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Framewise Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Patient Engagement
- Patient Education
- FHIR
- EHR Integration
- Health Literacy
- Artificial Intelligence
- HIPAA
- SOC 2
---
