---
api_specs:
- filename: a2-biotherapeutics-mcp-api-openapi.yml
  format: yaml
  label: A2 Biotherapeutics MCP API
  slug: a2-biotherapeutics-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a2-biotherapeutics/openapi/a2-biotherapeutics-mcp-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The product information provided on our website is intended for residents of the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Medical advice reliance
    text: You should not rely on this website or any other service offered by or through this website for medical diagnosis or treatment.
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
name: A2 Biotherapeutics
provenance_date: '2026-11-09'
provider_name: A2 Biotherapeutics
provider_slug: a2-biotherapeutics
slug: a2-biotherapeutics-eligibility
source_date: '2026-11-09'
source_filename: a2-biotherapeutics-eligibility.yml
source_heading: Eligibility
source_page: https://www.a2bio.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: A2 Biotherapeutics\naid: a2-biotherapeutics\nurl: https://www.a2bio.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The product information provided on our website is intended for residents of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Medical advice reliance\n  text: You should not rely on this website or any other service offered by or through this website for medical\n    diagnosis or treatment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/a2-biotherapeutics/eligibility/a2-biotherapeutics-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from A2 Biotherapeutics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Life Sciences
- Cell Therapy
- Immuno-Oncology
- Oncology
- Pharmaceuticals
- Clinical Trials
- Healthcare
- MCP
- WordPress
---
