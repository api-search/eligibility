---
api_specs:
- filename: joinbunch-com-files-api-openapi.yml
  format: yaml
  label: Bunch Files API
  slug: joinbunch-com-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bunch/openapi/joinbunch-com-files-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use of the Digital Platform and the services offered through the Digital Platform is strictly limited to persons who are not considered to be consumers under governing law
    type: other
  minimum_age:
    text: You may generally only open an Account if you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Entrepreneurs only, consumers excluded
    text: Consumers are explicitly excluded from the use of the Digital Platform and the services offered through the Digital Platform.
  - summary: No illegal, malicious or fraudulent purposes
    text: You may not use the Digital Platform for any purpose that is illegal, malicious or fraudulent.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: You may only open an Account once you have provided such minimum information and completed our know-your-customer identification and verification process (“ KYC ”) to bunch’s satisfaction, in its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bunch
provenance_date: '2026-11-09'
provider_name: Bunch
provider_slug: bunch
slug: bunch-eligibility
source_date: '2026-11-09'
source_filename: bunch-eligibility.yml
source_heading: Eligibility
source_page: https://www.bunch.capital/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bunch\naid: bunch\nurl: https://www.bunch.capital/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: Use of the Digital Platform and the services offered through the Digital Platform is strictly limited to\n    persons who are not considered to be consumers under governing law\nrestricted_uses:\n- summary: Entrepreneurs only, consumers excluded\n  text: Consumers are explicitly excluded from the use of the Digital Platform and the services offered through\n    the Digital Platform.\n- summary: No illegal, malicious\
  \ or fraudulent purposes\n  text: You may not use the Digital Platform for any purpose that is illegal, malicious or fraudulent.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: You may only open an Account once you have provided such minimum information and completed our know-your-customer\n    identification and verification process (“ KYC ”) to bunch’s satisfaction, in its sole discretion.\nminimum_age:\n  value: '18'\n  text: You may generally only open an Account if you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/bunch/eligibility/bunch-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Bunch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Private Markets
- Fund Administration
- Fund Operations
- Venture Capital
- Private Equity
- SPV
- Artificial Intelligence
- Fund Management
---
