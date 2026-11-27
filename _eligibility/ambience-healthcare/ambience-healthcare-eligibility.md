---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: United States residents
  entity_types:
  - text: physician, nurse, nurse practitioner, or similar
    type: individual
  minimum_age:
    text: at least 18 years of age
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must register to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ambience Healthcare
provenance_date: '2026-11-09'
provider_name: Ambience Healthcare
provider_slug: ambience-healthcare
slug: ambience-healthcare-eligibility
source_date: '2026-11-09'
source_filename: ambience-healthcare-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.prod.website-files.com/65be6ed75db0972f744bb6b1/65c1a3f7d8cbb7b2397bd541_63fd4608cf1aa8041a98d378_terms.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ambience Healthcare\naid: ambience-healthcare\nurl: https://cdn.prod.website-files.com/65be6ed75db0972f744bb6b1/65c1a3f7d8cbb7b2397bd541_63fd4608cf1aa8041a98d378_terms.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: United States residents\nentity_types:\n- type: individual\n  text: physician, nurse, nurse practitioner, or similar\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must register to use the Services.\nminimum_age:\n  value: '18'\n  text: at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/ambience-healthcare/eligibility/ambience-healthcare-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Ambience Healthcare's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Clinical Documentation
- Ambient AI
- Medical Coding
- Electronic Health Records
- FHIR
- Health IT
- Speech Recognition
---
