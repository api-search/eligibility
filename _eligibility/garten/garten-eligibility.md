---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accessing or using the Site, and/or using a Service, (i) you agree to these Terms and (ii) you represent that you are at least 18 years old.
    type: individual
  minimum_age:
    text: you represent that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No PHI upload
    text: under no circumstances will you upload to the Site or otherwise provide to Garten any data or information which may qualify as protected health information (or any similar information) regulated under the Health Insurance Portability and Accountability Act of 1996
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
name: Garten
provenance_date: '2026-11-09'
provider_name: Garten
provider_slug: garten
slug: garten-eligibility
source_date: '2026-11-09'
source_filename: garten-eligibility.yml
source_heading: Eligibility
source_page: https://garten.co/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Garten\naid: garten\nurl: https://garten.co/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By accessing or using the Site, and/or using a Service, (i) you agree to these Terms and (ii) you represent\n    that you are at least 18 years old.\nrestricted_uses:\n- summary: No PHI upload\n  text: under no circumstances will you upload to the Site or otherwise provide to Garten any data or information\n    which may qualify as protected health information (or any similar information) regulated under the Health Insurance\n\
  \    Portability and Accountability Act of 1996\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent that you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/garten/eligibility/garten-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Garten's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food Service
- Corporate Wellness
- Workplace
- Catering
- Employee Benefits
- Micro Market
- Facilities Management
- Hospitality
- Streaming Video
- MCP
---
