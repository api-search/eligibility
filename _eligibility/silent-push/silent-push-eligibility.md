---
api_specs:
- filename: silent-push-web-scanner.postman_collection.json
  format: json
  label: Silent Push API
  slug: silent-push-api
  spec_type: Postman
  url: https://artifacts.apis.io/silent-push/postman/silent-push-web-scanner.postman_collection.json
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you access Silent Push from outside of the United States, you do so at your own risk and are responsible for compliance with the laws of your jurisdiction.
  entity_types:
  - text: You must be at least eighteen (18) years of age.
    type: individual
  minimum_age:
    text: You must be at least eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Production use on Community Edition
    text: You agree that you will not use the Service to support any Production-related business operations, provide access to external users, or perform real transactions.
  - summary: Use to make decisions affecting real customers
    text: You will not (i) deploy agents/connectors from the Service into systems designed, intended or used for Production Use; (ii) integrate the Service with payment flows or messaging designed, intended or used for Production Use; (iii) use the Service to make decisions affecting real customers or employees
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
name: Silent Push
provenance_date: '2026-11-10'
provider_name: Silent Push
provider_slug: silent-push
slug: silent-push-eligibility
source_date: '2026-11-10'
source_filename: silent-push-eligibility.yml
source_heading: Eligibility
source_page: https://www.silentpush.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Silent Push\naid: silent-push\nurl: https://www.silentpush.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you access Silent Push from outside of the United States, you do so at your own risk and are responsible\n    for compliance with the laws of your jurisdiction.\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years of age.\nrestricted_uses:\n- summary: Production use on Community Edition\n  text: You agree that you will not use the Service to support any Production-related business operations, provide\n    access to external\
  \ users, or perform real transactions.\n- summary: Use to make decisions affecting real customers\n  text: You will not (i) deploy agents/connectors from the Service into systems designed, intended or used for Production\n    Use; (ii) integrate the Service with payment flows or messaging designed, intended or used for Production Use;\n    (iii) use the Service to make decisions affecting real customers or employees\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/silent-push/eligibility/silent-push-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Silent Push's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Threat Intelligence
- Cybersecurity
- DNS
- Domain Intelligence
- Passive DNS
- Data Enrichment
- Threat Feeds
- WHOIS
- MCP
---
