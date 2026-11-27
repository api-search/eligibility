---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: THE ACEISS PLATFORM IS OFFERED AND MADE AVAILABLE TO, AND INTENDED FOR USE SOLELY BY , RESIDENTS OF THE UNITED STATES OF AMERICA
  entity_types:
  - text: IF THE INDIVIDUAL TAKING SUCH ACTION IS ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY
    type: individual
  minimum_age:
    text: AT LEAST 18 YEARS OF AGE
    value: '18'
  restricted_uses:
  - summary: Fraudulent or illegal activity
    text: Customer, or any Permitted User, is using the Services for fraudulent or illegal activities
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
name: Aceiss
provenance_date: '2026-11-09'
provider_name: Aceiss
provider_slug: aceiss
slug: aceiss-eligibility
source_date: '2026-11-09'
source_filename: aceiss-eligibility.yml
source_heading: Eligibility
source_page: https://aceiss-app-public.s3.us-east-1.amazonaws.com/assets/documents/AFG/Aceiss+Platform+-+Master+Terms+of+Use+-+2025.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aceiss\naid: aceiss\nurl: https://aceiss-app-public.s3.us-east-1.amazonaws.com/assets/documents/AFG/Aceiss+Platform+-+Master+Terms+of+Use+-+2025.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: THE ACEISS PLATFORM IS OFFERED AND MADE AVAILABLE TO, AND INTENDED FOR USE SOLELY BY , RESIDENTS OF THE\n    UNITED STATES OF AMERICA\nentity_types:\n- type: individual\n  text: IF THE INDIVIDUAL TAKING SUCH ACTION IS ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL\n    ENTITY\nrestricted_uses:\n- summary: Fraudulent or illegal activity\n  text: Customer, or any\
  \ Permitted User, is using the Services for fraudulent or illegal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: AT LEAST 18 YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/aceiss/eligibility/aceiss-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Aceiss's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Identity and Access Management
- Access Control
- Governance
- Compliance
- Monitoring
- GitHub
- Insider Threat
- Zero Trust
---
