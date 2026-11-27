---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This website is for your personal and non-commercial use only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial use only
    text: This website is for your personal and non-commercial use only.
  - source: https://developer.veradigm.com/Content/fhir/Allscripts_FHIR_API_License_2017.2.pdf
    summary: No unlawful use
    text: use any portion of the Allscripts SDK or any Developer App for any unlawful or illegal activity
  - source: https://developer.veradigm.com/Content/fhir/Allscripts_FHIR_API_License_2017.2.pdf
    summary: Compliance with HIPAA and FTC Act
    text: Developer shall strictly comply with all applicable laws, regulations and governmental orders
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
name: Veradigm (Allscripts)
provenance_date: '2026-11-10'
provider_name: Veradigm (Allscripts)
provider_slug: veradigm
slug: veradigm-eligibility
source_date: '2026-11-10'
source_filename: veradigm-eligibility.yml
source_heading: Eligibility
source_page: https://veradigm.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Veradigm (Allscripts)\naid: veradigm\nurl: https://veradigm.com/legal/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://developer.veradigm.com/Content/fhir/Allscripts_FHIR_API_License_2017.2.pdf\n  - https://veradigm.com/legal/terms-of-use/\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This website is for your personal and non-commercial use only.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: This website is for your personal and non-commercial use only.\n- summary: No unlawful use\n  text: use any portion of the Allscripts\
  \ SDK or any Developer App for any unlawful or illegal activity\n  source: https://developer.veradigm.com/Content/fhir/Allscripts_FHIR_API_License_2017.2.pdf\n- summary: Compliance with HIPAA and FTC Act\n  text: Developer shall strictly comply with all applicable laws, regulations and governmental orders\n  source: https://developer.veradigm.com/Content/fhir/Allscripts_FHIR_API_License_2017.2.pdf\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/veradigm/eligibility/veradigm-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Veradigm (Allscripts)'s own page on 2026-11-10.
synthetic: false
tags:
- Healthcare IT
- Electronic Health Records
- FHIR
- Clinical Data
- Practice Management
- HL7
---
