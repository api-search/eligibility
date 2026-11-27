---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is operated from the U.S. and is intended for U.S. residents only. The Site is not approved for distribution outside of the U.S.
  entity_types:
  - text: You must be at least eighteen (18) years of age or, if under 18, have your parent or legal guardian’s permission
    type: individual
  minimum_age:
    text: You must be at least eighteen (18) years of age or, if under 18, have your parent or legal guardian’s permission (“Minimum Age”) to use the Site and Services.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Your eligibility for particular products and services is subject to final Old National determination and acceptance.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Old National Bank
provenance_date: '2026-11-10'
provider_name: Old National Bank
provider_slug: old-national-bank
slug: old-national-bank-eligibility
source_date: '2026-11-10'
source_filename: old-national-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.oldnational.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Old National Bank\naid: old-national-bank\nurl: https://www.oldnational.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is operated from the U.S. and is intended for U.S. residents only. The Site is not approved for\n    distribution outside of the U.S.\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years of age or, if under 18, have your parent or legal guardian’s permission\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Your eligibility for particular products and\
  \ services is subject to final Old National determination and\n    acceptance.\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age or, if under 18, have your parent or legal guardian’s permission\n    (“Minimum Age”) to use the Site and Services.\n"
source_yaml_url: https://artifacts.apis.io/old-national-bank/eligibility/old-national-bank-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Old National Bank's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Regional Bank
- Commercial Banking
- Treasury Management
- Open Finance
---
