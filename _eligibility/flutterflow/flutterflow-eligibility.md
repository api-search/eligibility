---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Service is controlled and operated from facilities in the United States. You may not use the Service if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
  entity_types:
  - text: If you desire to use our services for or on behalf of any companies, organizations, or other persons or entities with $10 million or more in aggregate revenue, then you must purchase access to our FlutterFlow Enterprise service offering
    type: business
  minimum_age:
    text: You must be at least 13 years old to use the Service, or 16 Europe.
    value: 13 (16 in Europe)
  restricted_uses:
  - summary: Sensitive data
    text: 'The Service is not designed for, and you agree not to submit, store or process through it, any of the following (“ Sensitive Data ”): health information protected by the Health Insurance Portability and Accountability Act (HIPAA)'
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
name: FlutterFlow
provenance_date: '2026-11-09'
provider_name: FlutterFlow
provider_slug: flutterflow
slug: flutterflow-eligibility
source_date: '2026-11-09'
source_filename: flutterflow-eligibility.yml
source_heading: Eligibility
source_page: https://www.flutterflow.io/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FlutterFlow\naid: flutterflow\nurl: https://www.flutterflow.io/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Service is controlled and operated from facilities in the United States. You may not use the Service if\n    you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or\n    denied by the United States government.\nentity_types:\n- type: business\n  text: If you desire to use our services for or on behalf of any companies, organizations, or other persons or\n    entities with $10 million or more in aggregate\
  \ revenue, then you must purchase access to our FlutterFlow Enterprise\n    service offering\nrestricted_uses:\n- summary: Sensitive data\n  text: 'The Service is not designed for, and you agree not to submit, store or process through it, any of the following\n    (“ Sensitive Data ”): health information protected by the Health Insurance Portability and Accountability Act\n    (HIPAA)'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 13 (16 in Europe)\n  text: You must be at least 13 years old to use the Service, or 16 Europe.\n"
source_yaml_url: https://artifacts.apis.io/flutterflow/eligibility/flutterflow-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from FlutterFlow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- Low-Code
- No-Code
- App Builder
- Flutter
- Mobile Development
- Visual Development
- CLI
- MCP
---
