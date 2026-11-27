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
    served: []
    text: Customer shall not export ... to any country or region subject to comprehensive economic sanctions (i.e., currently Cuba, Iran, North Korea, Syria, and the Crimea Region of Ukraine)
  entity_types:
  - text: This Agreement is a legal agreement between the entity identified in the applicable Order Form as the customer (“Customer”) and Imprivata, Inc.
    type: business
  - text: IF CUSTOMER IS A CORPORATION, GOVERNMENTAL ORGANIZATION, OR OTHER LEGAL ENTITY, THEN THE INDIVIDUAL ACCEPTING THESE TERMS HEREBY REPRESENTS AND WARRANTS THAT THEY HAVE THE RIGHT, POWER, AND AUTHORITY
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: The Cloud Service is not fault-tolerant and is not developed or intended for use - including evaluation or trial use –in hazardous environments requiring fail-safe performance
  - summary: Export restrictions for military-intelligence and proliferation uses
    text: Customer shall not export, re-export, release, or transfer the Services, Hardware, or any part thereof, including technical data and services, to any party, if Customer knows or has reason to know that the products, data, or services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Imprivata
provenance_date: '2026-11-09'
provider_name: Imprivata
provider_slug: imprivata
slug: imprivata-eligibility
source_date: '2026-11-09'
source_filename: imprivata-eligibility.yml
source_heading: Eligibility
source_page: https://www.imprivata.com/legal/imprivata-master-cloud-services-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Imprivata\naid: imprivata\nurl: https://www.imprivata.com/legal/imprivata-master-cloud-services-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: Customer shall not export ... to any country or region subject to comprehensive economic sanctions (i.e.,\n    currently Cuba, Iran, North Korea, Syria, and the Crimea Region of Ukraine)\nentity_types:\n- type: business\n  text: This Agreement is a legal agreement between the entity identified in the applicable Order Form as the customer\n    (“Customer”) and Imprivata, Inc.\n- type: government\n  text:\
  \ IF CUSTOMER IS A CORPORATION, GOVERNMENTAL ORGANIZATION, OR OTHER LEGAL ENTITY, THEN THE INDIVIDUAL ACCEPTING\n    THESE TERMS HEREBY REPRESENTS AND WARRANTS THAT THEY HAVE THE RIGHT, POWER, AND AUTHORITY\nrestricted_uses:\n- summary: High-risk activities\n  text: The Cloud Service is not fault-tolerant and is not developed or intended for use - including evaluation\n    or trial use –in hazardous environments requiring fail-safe performance\n- summary: Export restrictions for military-intelligence and proliferation uses\n  text: Customer shall not export, re-export, release, or transfer the Services, Hardware, or any part thereof,\n    including technical data and services, to any party, if Customer knows or has reason to know that the products,\n    data, or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/imprivata/eligibility/imprivata-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Imprivata's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Identity
- Identity and Access Management
- Authentication
- SSO
- Privileged Access Management
- Healthcare
- Security
- Passwordless
---
