---
api_specs:
- filename: capy-inc-verification-api-openapi.yml
  format: yaml
  label: Capy Inc. Verification API
  slug: capy-inc-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy-inc/openapi/capy-inc-verification-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept these Terms of Service and use the Services on behalf of a company, organization, or other legal entity, you represent and warrant to the Company that you have full power and authority to do so.
    type: business
  minimum_age:
    text: YOUR REPRESENTATION THAT YOU ARE AT LEAST 16 YEARS OF AGE OR OLDER.
    value: '16'
  restricted_uses:
  - summary: No HIPAA protected health information
    text: The Services and this Website are not intended to be used to communicate protected health information, nor comply with HIPAA.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may verify your provided information, as required for your use of and access to the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Capy Inc.
provenance_date: '2026-11-09'
provider_name: Capy Inc.
provider_slug: capy-inc
slug: capy-inc-eligibility
source_date: '2026-11-09'
source_filename: capy-inc-eligibility.yml
source_heading: Eligibility
source_page: https://www.leminnow.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Capy Inc.\naid: capy-inc\nurl: https://www.leminnow.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept these Terms of Service and use the Services on behalf of a company, organization, or other\n    legal entity, you represent and warrant to the Company that you have full power and authority to do so.\nrestricted_uses:\n- summary: No HIPAA protected health information\n  text: The Services and this Website are not intended to be used to communicate protected health information, nor\n    comply with HIPAA.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may verify your provided information, as required for your use of and access to the Services.\nminimum_age:\n  value: '16'\n  text: YOUR REPRESENTATION THAT YOU ARE AT LEAST 16 YEARS OF AGE OR OLDER.\n"
source_yaml_url: https://artifacts.apis.io/capy-inc/eligibility/capy-inc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Capy Inc.'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- CAPTCHA
- Bot Detection
- Bot Prevention
- Fraud Prevention
- Account Takeover
- Authentication
- Web Security
- Developer Tools
---
