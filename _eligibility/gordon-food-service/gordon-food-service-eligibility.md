---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: GFS operates the Services from the United States and Canada and makes no representation that content and materials are legal or appropriate for use outside the United States.
  entity_types:
  - text: These Services are available only to individuals who are at least 18 years old.
    type: individual
  - text: If you are accessing or using the Services on behalf of your company, you represent that you are authorized to accept these Terms of Use on behalf of your company
    type: business
  minimum_age:
    text: These Services are available only to individuals who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Use in violation of export/sanctions laws
    text: You may not use the Services in violation of United States export laws and regulations.
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
name: Gordon Food Service
provenance_date: '2026-11-09'
provider_name: Gordon Food Service
provider_slug: gordon-food-service
slug: gordon-food-service-eligibility
source_date: '2026-11-09'
source_filename: gordon-food-service-eligibility.yml
source_heading: Eligibility
source_page: https://gfs.com/en-us/terms-of-use-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gordon Food Service\naid: gordon-food-service\nurl: https://gfs.com/en-us/terms-of-use-agreement/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: GFS operates the Services from the United States and Canada and makes no representation that content and\n    materials are legal or appropriate for use outside the United States.\nentity_types:\n- type: individual\n  text: These Services are available only to individuals who are at least 18 years old.\n- type: business\n  text: If you are accessing or using the Services on behalf of your company, you represent that you are\
  \ authorized\n    to accept these Terms of Use on behalf of your company\nrestricted_uses:\n- summary: Use in violation of export/sanctions laws\n  text: You may not use the Services in violation of United States export laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: These Services are available only to individuals who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/gordon-food-service/eligibility/gordon-food-service-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Gordon Food Service's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food Distribution
- B2B
- Logistics
- North America
---
