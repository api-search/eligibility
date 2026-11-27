---
api_specs:
- filename: synthego-order-api-openapi.yml
  format: yaml
  label: Synthego Order API
  slug: synthego-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synthego/openapi/synthego-order-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to the Web Service may not be legal by certain persons or in certain countries.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-clinical research only
    text: The Web Service is for NON-CLINICAL RESEARCH USE ONLY, AND NOT FOR HUMAN OR ANIMAL THERAPEUTIC, DIAGNOSTIC, PROPHYLACTIC, OR OTHER MEDICAL USE.
  - summary: Compliance with law
    text: You represent and warrant that you will use the Web Service and the Analytic Results in compliance with all applicable laws, regulations and governmental policies.
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
name: Synthego
provenance_date: '2026-11-10'
provider_name: Synthego
provider_slug: synthego
slug: synthego-eligibility
source_date: '2026-11-10'
source_filename: synthego-eligibility.yml
source_heading: Eligibility
source_page: https://www.synthego.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Synthego\naid: synthego\nurl: https://www.synthego.com/legal/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to the Web Service may not be legal by certain persons or in certain countries.\nentity_types: []\nrestricted_uses:\n- summary: Non-clinical research only\n  text: The Web Service is for NON-CLINICAL RESEARCH USE ONLY, AND NOT FOR HUMAN OR ANIMAL THERAPEUTIC, DIAGNOSTIC,\n    PROPHYLACTIC, OR OTHER MEDICAL USE.\n- summary: Compliance with law\n  text: You represent and warrant that you will use the Web Service and the Analytic Results in compliance with\n\
  \    all applicable laws, regulations and governmental policies.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/synthego/eligibility/synthego-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Synthego's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health Tech
- Genomics
- CRISPR
- Biotechnology
- Life Sciences
- Synthetic Biology
- Ordering
---
