---
api_specs:
- filename: impulse-dynamics-mcp-api-openapi.yml
  format: yaml
  label: Impulse Dynamics MCP API
  slug: impulse-dynamics-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/impulse-dynamics/openapi/impulse-dynamics-mcp-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  entity_types:
  - text: we reserve the right to limit access to certain areas of the Website to medical professionals who register and meet the qualifications imposed by us.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use
    text: You must not access or use for any commercial purposes any part of the Website or any services or materials available through the Website.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To register, a medical professional must provide us with certain personal information, including their name, profession, email address, postal address, title, and clinical affiliation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Impulse Dynamics
provenance_date: '2026-11-09'
provider_name: Impulse Dynamics
provider_slug: impulse-dynamics
slug: impulse-dynamics-eligibility
source_date: '2026-11-09'
source_filename: impulse-dynamics-eligibility.yml
source_heading: Eligibility
source_page: https://impulse-dynamics.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Impulse Dynamics\naid: impulse-dynamics\nurl: https://impulse-dynamics.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: we reserve the right to limit access to certain areas of the Website to medical professionals who register\n    and meet the qualifications imposed by us.\nrestricted_uses:\n- summary: No commercial use\n  text: You must not access or use for any commercial purposes any part of the Website or any services or materials\n\
  \    available through the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To register, a medical professional must provide us with certain personal information, including their name,\n    profession, email address, postal address, title, and clinical affiliation.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/impulse-dynamics/eligibility/impulse-dynamics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Impulse Dynamics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Medical Devices
- Healthcare
- Cardiology
- Heart Failure
- Implantable Devices
- Health Tech
- Life Sciences
- Clinical Trials
- MCP
- WordPress
---
