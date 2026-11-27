---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use our Services, you must be at least 18 years of age and have the legal capacity to enter into binding contracts.
    type: individual
  - text: If you are using the Services on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: To use our Services, you must be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You agree to use the Services only for lawful purposes and in accordance with all applicable laws and regulations, including healthcare privacy and security laws.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to certain features of the Services may require registration for an Account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aumet
provenance_date: '2026-11-09'
provider_name: Aumet
provider_slug: aumet
slug: aumet-eligibility
source_date: '2026-11-09'
source_filename: aumet-eligibility.yml
source_heading: Eligibility
source_page: https://aumet.com/en/terms-conditions-en/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aumet\naid: aumet\nurl: https://aumet.com/en/terms-conditions-en/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use our Services, you must be at least 18 years of age and have the legal capacity to enter into binding\n    contracts.\n- type: business\n  text: If you are using the Services on behalf of an organization, you represent and warrant that you have the\n    authority to bind that organization to these Terms\nrestricted_uses:\n- summary: Lawful use only\n  text: You agree to use the Services only for lawful purposes and\
  \ in accordance with all applicable laws and regulations,\n    including healthcare privacy and security laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Access to certain features of the Services may require registration for an Account.\nminimum_age:\n  value: '18'\n  text: To use our Services, you must be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/aumet/eligibility/aumet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Aumet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Pharmacy
- Pharmaceuticals
- Procurement
- Marketplace
- Supply Chain
- Health Tech
- ERP
- MENA
---
