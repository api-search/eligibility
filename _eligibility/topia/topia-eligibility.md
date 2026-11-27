---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent, warrant and covenant that you are not (a) located in, or a resident or a national of, any country subject to a U.S. government embargo or other restriction, or that has been designated by the U.S. government as a "terrorist supporting" country
  entity_types:
  - text: If your Employer has not provided you with access to the Services and has not directed you to use the Services, you are not allowed to use the Services.
    type: individual
  - text: To use the Services, your employer (Employer) must have entered into a contract with Topia to provide its employees with access to the Services (Employer Contract).
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control restrictions
    text: You are responsible for complying with United States export controls and for any violation of such controls, including any United States embargoes or other federal rules and regulations restricting exports.
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
name: Topia
provenance_date: '2026-11-10'
provider_name: Topia
provider_slug: topia
slug: topia-eligibility
source_date: '2026-11-10'
source_filename: topia-eligibility.yml
source_heading: Eligibility
source_page: https://www.topia.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Topia\naid: topia\nurl: https://www.topia.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent, warrant and covenant that you are not (a) located in, or a resident or a national of, any\n    country subject to a U.S. government embargo or other restriction, or that has been designated by the U.S. government\n    as a \"terrorist supporting\" country\nentity_types:\n- type: individual\n  text: If your Employer has not provided you with access to the Services and has not directed you to use the Services,\n    you are not allowed to use the Services.\n\
  - type: business\n  text: To use the Services, your employer (Employer) must have entered into a contract with Topia to provide its\n    employees with access to the Services (Employer Contract).\nrestricted_uses:\n- summary: Export control restrictions\n  text: You are responsible for complying with United States export controls and for any violation of such controls,\n    including any United States embargoes or other federal rules and regulations restricting exports.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/topia/eligibility/topia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Topia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Global Mobility
- Human Resources
- Relocation
- Tax Compliance
- Immigration
- Business Travel
- Workforce Management
- Remote Work
- Enterprise Software
---
