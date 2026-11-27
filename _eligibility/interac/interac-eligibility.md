---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: 'You represent and warrant that you: (a) have reached the age of majority in your province or territory of residence; (b) are a resident of Canada'
  entity_types:
  - text: To use the Interac e-Transfer service, you must have reached the age of majority in your province or territory of residence
    type: individual
  minimum_age:
    text: eighteen (18) years old in Alberta, Manitoba, Ontario, Prince Edward Island, Quebec and Saskatchewan), and nineteen (19) years old in British Columbia
    value: 18 or 19, depending on province
  restricted_uses:
  - summary: Lawful use only
    text: You agree to use the Interac e-Transfer service and the Sites only for lawful purposes.
  - summary: No collecting for others
    text: You may not use the service to collect transactions where you are not the intended recipient.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: your personal or business information cannot be verified
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Interac
provenance_date: '2026-11-09'
provider_name: Interac
provider_slug: interac
slug: interac-eligibility
source_date: '2026-11-09'
source_filename: interac-eligibility.yml
source_heading: Eligibility
source_page: https://www.interac.ca/en/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Interac\naid: interac\nurl: https://www.interac.ca/en/legal/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: 'You represent and warrant that you: (a) have reached the age of majority in your province or territory\n    of residence; (b) are a resident of Canada'\nentity_types:\n- type: individual\n  text: To use the Interac e-Transfer service, you must have reached the age of majority in your province or territory\n    of residence\nrestricted_uses:\n- summary: Lawful use only\n  text: You agree to use the Interac e-Transfer service and the Sites only for lawful\
  \ purposes.\n- summary: No collecting for others\n  text: You may not use the service to collect transactions where you are not the intended recipient.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: your personal or business information cannot be verified\nminimum_age:\n  value: 18 or 19, depending on province\n  text: eighteen (18) years old in Alberta, Manitoba, Ontario, Prince Edward Island, Quebec and Saskatchewan), and\n    nineteen (19) years old in British Columbia\n"
source_yaml_url: https://artifacts.apis.io/interac/eligibility/interac-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Interac's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Payments
- Canada
- Interac
- Digital Identity
- Verification
- Open Banking
- Consumer-Driven Banking
- Infrastructure
---
