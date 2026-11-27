---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our services are to provide a software platform for use by Healthcare Practitioners, Healthcare Students and healthcare organisations.
    type: other
  minimum_age:
    text: To be eligible to use Medall you must be over the age of 18
    value: '18'
  restricted_uses:
  - summary: Prohibited content
    text: you may not upload, store or transmit via Medall any content
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: we don’t vet our Users and so can’t guarantee that Users are who they claim to be
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MedAll
provenance_date: '2026-11-10'
provider_name: MedAll
provider_slug: medall
slug: medall-eligibility
source_date: '2026-11-10'
source_filename: medall-eligibility.yml
source_heading: Eligibility
source_page: https://medall.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MedAll\naid: medall\nurl: https://medall.org/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: Our services are to provide a software platform for use by Healthcare Practitioners, Healthcare Students\n    and healthcare organisations.\nrestricted_uses:\n- summary: Prohibited content\n  text: you may not upload, store or transmit via Medall any content\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: we don’t vet our Users and so can’t guarantee that Users are who they claim to be\nminimum_age:\n\
  \  value: '18'\n  text: To be eligible to use Medall you must be over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/medall/eligibility/medall-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from MedAll's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Medical Education
- Education
- Training
- Event
- Continuing Medical Education
- Health Tech
---
