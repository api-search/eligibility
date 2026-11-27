---
api_specs:
- filename: highnoteplatform-com-openapi-generated.yml
  format: yaml
  label: Highnote API
  slug: highnoteplatform-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/highnoteplatform-com/openapi/_ae-authored/highnoteplatform-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be acting on behalf of a commercial entity operating in the U.S.
  entity_types:
  - text: You must be acting on behalf of a commercial entity operating in the U.S.
    type: business
  minimum_age:
    text: You are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Illegal or illicit activity
    text: You are using the Platform Services and Highnote Content for legitimate purposes, are not participating in illegal or illicit activity, and are not circumventing applicable laws and/or regulations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Highnote may contact you as part of our due diligence process when reviewing User Information provided to request further documentation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Highnote
provenance_date: '2026-11-09'
provider_name: Highnote
provider_slug: highnoteplatform-com
slug: highnoteplatform-com-eligibility
source_date: '2026-11-09'
source_filename: highnoteplatform-com-eligibility.yml
source_heading: Eligibility
source_page: https://highnote.com/agreements/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Highnote\naid: highnoteplatform-com\nurl: https://highnote.com/agreements/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be acting on behalf of a commercial entity operating in the U.S.\nentity_types:\n- type: business\n  text: You must be acting on behalf of a commercial entity operating in the U.S.\nrestricted_uses:\n- summary: Illegal or illicit activity\n  text: You are using the Platform Services and Highnote Content for legitimate purposes, are not participating\n    in illegal or illicit activity, and are not circumventing applicable laws and/or regulations\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Highnote may contact you as part of our due diligence process when reviewing User Information provided to\n    request further documentation.\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/highnoteplatform-com/eligibility/highnoteplatform-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Highnote's own page on 2026-11-09.
synthetic: false
tags:
- Issuing
- Acquiring
- Credit
- Money Movement
- Embedded Finance
- Spend Management
- Fleet Management
- Travel
---
