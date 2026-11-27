---
api_specs:
- filename: nucleus-security-vulnerability-intelligence-api-openapi.yml
  format: yaml
  label: Nucleus Security Vulnerability Intelligence API
  slug: nucleus-security-vulnerability-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nucleus-security/openapi/nucleus-security-vulnerability-intelligence-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If acquired by or on behalf of any the Department of Defense or any component thereof, the U.S. Government acquires this commercial computer software
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control compliance
    text: Customer is solely responsible for complying with all such laws, regulations and orders
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All Purchase Orders are subject to credit approval by Nucleus.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nucleus Security
provenance_date: '2026-11-10'
provider_name: Nucleus Security
provider_slug: nucleus-security
slug: nucleus-security-eligibility
source_date: '2026-11-10'
source_filename: nucleus-security-eligibility.yml
source_heading: Eligibility
source_page: https://nucleussec.com/legal/msa/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nucleus Security\naid: nucleus-security\nurl: https://nucleussec.com/legal/msa/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: If acquired by or on behalf of any the Department of Defense or any component thereof, the U.S. Government\n    acquires this commercial computer software\nrestricted_uses:\n- summary: Export control compliance\n  text: Customer is solely responsible for complying with all such laws, regulations and orders\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All Purchase Orders are\
  \ subject to credit approval by Nucleus.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nucleus-security/eligibility/nucleus-security-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Nucleus Security's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Vulnerability Management
- Exposure Management
- Risk Management
- Threat Intelligence
- Compliance
- DevSecOps
- MCP
---
