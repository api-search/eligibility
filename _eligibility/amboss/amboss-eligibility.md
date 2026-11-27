---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: AMBOSS Membership is a digital companion for medical students, doctors, nurses and other professionals working in the healthcare sector or related educational fields.
    type: individual
  - text: AMBOSS concludes paid contracts with universities, clinics or other institutions in the healthcare sector (" Institutional Partners ")
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for patients
    text: The AMBOSS Program is not intended to be used by patients.
  - summary: AI Mode clinical care for healthcare professionals only
    text: This feature is for use by physicians and other healthcare professionals only (and may not be used by patients).
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: AMBOSS expressly reserves the right to refuse registration requests by not activating the corresponding user account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AMBOSS
provenance_date: '2026-11-09'
provider_name: AMBOSS
provider_slug: amboss
slug: amboss-eligibility
source_date: '2026-11-09'
source_filename: amboss-eligibility.yml
source_heading: Eligibility
source_page: https://www.amboss.com/us/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AMBOSS\naid: amboss\nurl: https://www.amboss.com/us/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: AMBOSS Membership is a digital companion for medical students, doctors, nurses and other professionals working\n    in the healthcare sector or related educational fields.\n- type: other\n  text: AMBOSS concludes paid contracts with universities, clinics or other institutions in the healthcare sector\n    (\" Institutional Partners \")\nrestricted_uses:\n- summary: Not for patients\n  text: The AMBOSS Program is not intended\
  \ to be used by patients.\n- summary: AI Mode clinical care for healthcare professionals only\n  text: This feature is for use by physicians and other healthcare professionals only (and may not be used by patients).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: AMBOSS expressly reserves the right to refuse registration requests by not activating the corresponding\n    user account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amboss/eligibility/amboss-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from AMBOSS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medical Education
- Medical Knowledge
- Clinical Reference
- Physicians
- EdTech
---
