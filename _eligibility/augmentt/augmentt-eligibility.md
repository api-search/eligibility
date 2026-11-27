---
api_specs:
- filename: augmentt-customers-api-openapi.yml
  format: yaml
  label: Augmentt Customers API
  slug: augmentt-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/augmentt/openapi/augmentt-customers-api-openapi.yml
- filename: augmentt-licensing-api-openapi.yml
  format: yaml
  label: Augmentt Licensing API
  slug: augmentt-licensing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/augmentt/openapi/augmentt-licensing-api-openapi.yml
- filename: augmentt-security-reports-api-openapi.yml
  format: yaml
  label: Augmentt Security Reports API
  slug: augmentt-security-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/augmentt/openapi/augmentt-security-reports-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: You shall not permit Users to access or use any Service in a Canada or U.S.-embargoed country (currently Cuba, Iran, North Korea, Sudan or Syria)
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Hazardous or safety-critical use
    text: access or use the Services or Documentation in, or in association with, the design, construction, maintenance or operation of any hazardous environments, systems, applications or products, any safety response systems or other safety-critical applications
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Augmentt
provenance_date: '2026-11-09'
provider_name: Augmentt
provider_slug: augmentt
slug: augmentt-eligibility
source_date: '2026-11-09'
source_filename: augmentt-eligibility.yml
source_heading: Eligibility
source_page: https://www.augmentt.com/subscription-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Augmentt\naid: augmentt\nurl: https://www.augmentt.com/subscription-agreement/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: You shall not permit Users to access or use any Service in a Canada or U.S.-embargoed country (currently\n    Cuba, Iran, North Korea, Sudan or Syria)\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: Hazardous or safety-critical use\n  text: access\
  \ or use the Services or Documentation in, or in association with, the design, construction, maintenance\n    or operation of any hazardous environments, systems, applications or products, any safety response systems or\n    other safety-critical applications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/augmentt/eligibility/augmentt-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Augmentt's own page on 2026-11-09.
synthetic: false
tags:
- MSP
- Microsoft 365
- SaaS Management
- SaaS Security
- Shadow IT
- Security Posture
- Compliance
- License Management
- Multi-Tenant
- Reporting
---
