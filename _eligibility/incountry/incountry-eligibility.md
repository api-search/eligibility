---
api_specs:
- filename: RestAPI_Demo_oAuth.postman_collection-e8b012cac5488563ba466e6ea44c309c.json
  format: json
  label: InCountry REST API
  slug: incountry-rest-api
  spec_type: Postman
  url: https://docs.incountry.com/assets/files/RestAPI_Demo_oAuth.postman_collection-e8b012cac5488563ba466e6ea44c309c.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ACCESSING AND USING THE SERVICE ON BEHALF OF A COMPANY (SUCH AS YOUR EMPLOYER) OR OTHER LEGAL ENTITY, YOU REPRESENT AND WARRANT THAT YOU HAVE THE AUTHORITY TO BIND THAT COMPANY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control and ITAR
    text: Customer shall not submit to the Service any information that is controlled under the U.S. International Traffic in Arms Regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You will need to register and create an account with InCountry to access the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: InCountry
provenance_date: '2026-11-09'
provider_name: InCountry
provider_slug: incountry
slug: incountry-eligibility
source_date: '2026-11-09'
source_filename: incountry-eligibility.yml
source_heading: Eligibility
source_page: https://incountry.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: InCountry\naid: incountry\nurl: https://incountry.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ACCESSING AND USING THE SERVICE ON BEHALF OF A COMPANY (SUCH AS YOUR EMPLOYER) OR OTHER LEGAL\n    ENTITY, YOU REPRESENT AND WARRANT THAT YOU HAVE THE AUTHORITY TO BIND THAT COMPANY\nrestricted_uses:\n- summary: Export control and ITAR\n  text: Customer shall not submit to the Service any information that is controlled under the U.S. International\n    Traffic in Arms Regulations.\nverification:\n \
  \ kyc: null\n  kyb: null\n  approval_required: null\n  text: You will need to register and create an account with InCountry to access the Service.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/incountry/eligibility/incountry-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from InCountry's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Residency
- Data Localization
- Compliance
- Privacy
- Data Security
- Encryption
- PII
- GDPR
- Data Sovereignty
- MCP
---
