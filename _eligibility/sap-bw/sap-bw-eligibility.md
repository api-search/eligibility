---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - IR
    - CU
    - KP
    - SY
    served: []
    text: SAP Websites may not be accessed or used by any national or certain countries or groups against which the United States and/or European Union have instituted sanctions (including Iran, Cuba, North Korea, Syria
  entity_types:
  - text: Purchasing or licensing of any SAP Software offered on the SAP Store is NOT available for consumers, but solely for merchants/corporations and might require an existing SAP system.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted end-use
    text: You will not utilize Content provided on an SAP Website for any restricted end-use (e.g. in the design, development, or production of nuclear, chemical, or biological weapons,)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- IR
- CU
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SAP BW
provenance_date: '2026-11-10'
provider_name: SAP BW
provider_slug: sap-bw
slug: sap-bw-eligibility
source_date: '2026-11-10'
source_filename: sap-bw-eligibility.yml
source_heading: Eligibility
source_page: https://www.sap.com/about/legal/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SAP BW\naid: sap-bw\nurl: https://www.sap.com/about/legal/terms-of-use.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - IR\n  - CU\n  - KP\n  - SY\n  text: SAP Websites may not be accessed or used by any national or certain countries or groups against which the\n    United States and/or European Union have instituted sanctions (including Iran, Cuba, North Korea, Syria\nentity_types:\n- type: business\n  text: Purchasing or licensing of any SAP Software offered on the SAP Store is NOT available for consumers, but\n    solely for merchants/corporations and might require an existing SAP\
  \ system.\nrestricted_uses:\n- summary: Restricted end-use\n  text: You will not utilize Content provided on an SAP Website for any restricted end-use (e.g. in the design,\n    development, or production of nuclear, chemical, or biological weapons,)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sap-bw/eligibility/sap-bw-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from SAP BW's own page on 2026-11-10.
synthetic: false
tags:
- Business Intelligence
- Data Warehousing
- Enterprise
- ETL
- SAP
---
