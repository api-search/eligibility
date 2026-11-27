---
api_specs:
- filename: fasten-health-bridge-api-openapi.yml
  format: yaml
  label: Fasten Health Bridge API
  slug: fasten-health-bridge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fasten-health/openapi/fasten-health-bridge-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: In order to create an Instance, you must be at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Not medical advice
    text: The Software and Services are not intended to provide medical advice.
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
name: Fasten Health
provenance_date: '2026-11-09'
provider_name: Fasten Health
provider_slug: fasten-health
slug: fasten-health-eligibility
source_date: '2026-11-09'
source_filename: fasten-health-eligibility.yml
source_heading: Eligibility
source_page: https://policy.fastenhealth.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fasten Health\naid: fasten-health\nurl: https://policy.fastenhealth.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not medical advice\n  text: The Software and Services are not intended to provide medical advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In order to create an Instance, you must be at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/fasten-health/eligibility/fasten-health-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Fasten Health's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- FHIR
- Personal Health Record
- Electronic Medical Record
- Health Data Interoperability
- TEFCA
- EHI Export
- Patient Consent
- Self-Hosted
- Open Source
- HL7
- Healthcare Connectivity
- A2A
---
