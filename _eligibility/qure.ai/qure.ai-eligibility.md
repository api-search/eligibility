---
api_specs:
- filename: qure.ai-fetch-results-api-openapi.yml
  format: yaml
  label: Qure.ai Fetch Results API
  slug: qure.ai-fetch-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qure.ai/openapi/qure.ai-fetch-results-api-openapi.yml
- filename: qure.ai-initiate-computation-api-openapi.yml
  format: yaml
  label: Qure.ai Initiate Computation API
  slug: qure.ai-initiate-computation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qure.ai/openapi/qure.ai-initiate-computation-api-openapi.yml
- filename: qure.ai-upload-dicoms-api-openapi.yml
  format: yaml
  label: Qure.ai Upload DICOMs API
  slug: qure.ai-upload-dicoms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qure.ai/openapi/qure.ai-upload-dicoms-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are of legal age to enter into and form a legally binding contract with Qure
    type: individual
  - text: in the event You are entering into these Terms on behalf of any entity/company or its group or affiliates, You do not possess the requisite authority to bind such entities
    type: business
  minimum_age:
    text: You are of legal age to enter into and form a legally binding contract with Qure
    value: legal age (unspecified)
  restricted_uses:
  - summary: Medical use by qualified personnel only
    text: are intended for use only by appropriately qualified and trained medical personnel, which are board-certified radiologists with a valid license to practice
  - summary: Not for primary diagnosis
    text: are intended for use only as a supplement to standard methods of interpreting radiological images and are not intended for primary diagnosis
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
name: Qure.ai
provenance_date: '2026-11-10'
provider_name: Qure.ai
provider_slug: qure.ai
slug: qure.ai-eligibility
source_date: '2026-11-10'
source_filename: qure.ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.qure.ai/us/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qure.ai\naid: qure.ai\nurl: https://www.qure.ai/us/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are of legal age to enter into and form a legally binding contract with Qure\n- type: business\n  text: in the event You are entering into these Terms on behalf of any entity/company or its group or affiliates,\n    You do not possess the requisite authority to bind such entities\nrestricted_uses:\n- summary: Medical use by qualified personnel only\n  text: are intended for use only by appropriately qualified and trained medical\
  \ personnel, which are board-certified\n    radiologists with a valid license to practice\n- summary: Not for primary diagnosis\n  text: are intended for use only as a supplement to standard methods of interpreting radiological images and are\n    not intended for primary diagnosis\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age (unspecified)\n  text: You are of legal age to enter into and form a legally binding contract with Qure\n"
source_yaml_url: https://artifacts.apis.io/qure.ai/eligibility/qure.ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Qure.ai's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Healthcare
- Medical Imaging
- Radiology
- Machine Learning
- DICOM
- Diagnostics
- Clinical Decision Support
- Health Tech
- Company
---
