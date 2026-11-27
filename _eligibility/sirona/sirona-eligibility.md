---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Sirona's cloud-native platform serves U.S.-based radiology practices today, with international availability expanding across the UK, Ireland, Europe, Australia, New Zealand, South Africa, and the UAE.
  minimum_age:
    text: null
    value: null
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
name: Sirona Medical
provenance_date: '2026-11-10'
provider_name: Sirona Medical
provider_slug: sirona
slug: sirona-eligibility
source_date: '2026-11-10'
source_filename: sirona-eligibility.yml
source_heading: Eligibility
source_page: https://sironamedical.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sirona Medical\naid: sirona\nurl: https://sironamedical.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Sirona's cloud-native platform serves U.S.-based radiology practices today, with international availability\n    expanding across the UK, Ireland, Europe, Australia, New Zealand, South Africa, and the UAE.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sirona/eligibility/sirona-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Sirona Medical's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Medical Imaging
- Radiology
- PACS
- DICOM
- HL7
- FHIR
- Cloud
- Artificial Intelligence
- Health IT
---
