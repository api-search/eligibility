---
api_specs:
- filename: keeper-security-bi-api-api-openapi.yml
  format: yaml
  label: Keeper Security Bi API
  slug: keeper-security-bi-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keeper-security/openapi/keeper-security-bi-api-api-openapi.yml
- filename: keeper-security-health-api-openapi.yml
  format: yaml
  label: Keeper Security Health API
  slug: keeper-security-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keeper-security/openapi/keeper-security-health-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF SUCH PURCHASE IS ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY
    type: business
  minimum_age:
    text: The Website is intended for individuals who are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: Customer shall not use, export or transfer the Services in violation of U.S. or other applicable export laws
  - summary: Restricted Persons
    text: Customer shall not utilize the Services to conduct or facilitate any transaction with any Restricted Person
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: for which the Partner has been approved by Keeper via the Partner Portal
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Keeper Security
provenance_date: '2026-11-09'
provider_name: Keeper Security
provider_slug: keeper-security
slug: keeper-security-eligibility
source_date: '2026-11-09'
source_filename: keeper-security-eligibility.yml
source_heading: Eligibility
source_page: https://www.keepersecurity.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Keeper Security\naid: keeper-security\nurl: https://www.keepersecurity.com/legal/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF SUCH PURCHASE IS ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: Customer shall not use, export or transfer the Services in violation of U.S. or other applicable export\n    laws\n- summary: Restricted Persons\n  text: Customer shall not utilize the Services to conduct or facilitate any transaction with\
  \ any Restricted Person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: for which the Partner has been approved by Keeper via the Partner Portal\nminimum_age:\n  value: '18'\n  text: The Website is intended for individuals who are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/keeper-security/eligibility/keeper-security-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Keeper Security's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Secrets Management
- Password Manager
- Privileged Access Management
- Zero Knowledge
- Security
- SDK
---
