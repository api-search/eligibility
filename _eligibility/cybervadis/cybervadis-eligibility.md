---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - RU
    served: []
    text: will not use, and will not allow any party to use, any services provided by CyberVadis or its Affiliates (including, but not limited to, the Services and the Solution) in connection with doing business with or involving, Cuba, Iran, North Korea, Syria, or Russian Federation
  entity_types:
  - text: any professional business entity entering into a contract with CyberVadis by accepting the present General Terms & Conditions
    type: business
  - text: Individual persons not acting for a professional purpose and/or consumers are expressly excluded from the Services.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned Person or sanctioned-country business
    text: it will not use, and will not allow any party to use, any services provided by CyberVadis or its Affiliates (including, but not limited to, the Services and the Solution) in connection with doing business with any Sanctioned Person
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: may, in the case of such a potential match, require the User to provide information or documentation necessary to confirm its identity.
excluded_countries:
- CU
- IR
- KP
- SY
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CyberVadis
provenance_date: '2026-11-09'
provider_name: CyberVadis
provider_slug: cybervadis
slug: cybervadis-eligibility
source_date: '2026-11-09'
source_filename: cybervadis-eligibility.yml
source_heading: Eligibility
source_page: https://app.cybervadis.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CyberVadis\naid: cybervadis\nurl: https://app.cybervadis.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - RU\n  text: will not use, and will not allow any party to use, any services provided by CyberVadis or its Affiliates\n    (including, but not limited to, the Services and the Solution) in connection with doing business with or involving,\n    Cuba, Iran, North Korea, Syria, or Russian Federation\nentity_types:\n- type: business\n  text: any professional business entity entering into a contract with CyberVadis by accepting the present\
  \ General\n    Terms & Conditions\n- type: individual\n  text: Individual persons not acting for a professional purpose and/or consumers are expressly excluded from the\n    Services.\nrestricted_uses:\n- summary: Sanctioned Person or sanctioned-country business\n  text: it will not use, and will not allow any party to use, any services provided by CyberVadis or its Affiliates\n    (including, but not limited to, the Services and the Solution) in connection with doing business with any Sanctioned\n    Person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: may, in the case of such a potential match, require the User to provide information or documentation necessary\n    to confirm its identity.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cybervadis/eligibility/cybervadis-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from CyberVadis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Third-Party Risk Management
- Security Ratings
- Governance Risk Compliance
- Infrastructure Saas
---
