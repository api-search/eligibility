---
api_specs:
- filename: google-vault-matters-api-openapi.yml
  format: yaml
  label: Google Vault Matters API
  slug: google-vault-matters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-vault/openapi/google-vault-matters-api-openapi.yml
- filename: google-vault-operations-api-openapi.yml
  format: yaml
  label: Google Vault Operations API
  slug: google-vault-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-vault/openapi/google-vault-operations-api-openapi.yml
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the APIs and may not accept the Terms if (a) you are not of legal age to form a binding contract with Google, or (b) you are a person barred from using or receiving the APIs under the applicable laws of the United States or other countries
  entity_types:
  - text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind that entity to the Terms
    type: business
  - text: If you are accepting the Terms on behalf of a United States federal government entity
    type: government
  minimum_age:
    text: you are not of legal age to form a binding contract with Google
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
  - summary: ITAR-controlled data
    text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations maintained by the U.S. Department of State.
  - summary: Protected health information
    text: you will not use the APIs for any purpose or in any manner involving transmitting protected health information to Google unless you have received prior written consent to such use from Google.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to access certain APIs you may be required to provide certain information (such as identification or contact details) as part of the registration process
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Google Vault
provenance_date: '2026-11-09'
provider_name: Google Vault
provider_slug: google-vault
slug: google-vault-eligibility
source_date: '2026-11-09'
source_filename: google-vault-eligibility.yml
source_heading: Eligibility
source_page: https://developers.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Vault\naid: google-vault\nurl: https://developers.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the APIs and may not accept the Terms if (a) you are not of legal age to form a binding\n    contract with Google, or (b) you are a person barred from using or receiving the APIs under the applicable laws\n    of the United States or other countries\nentity_types:\n- type: business\n  text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind\n    that entity to the Terms\n- type: government\n\
  \  text: If you are accepting the Terms on behalf of a United States federal government entity\nrestricted_uses:\n- summary: High-risk activities\n  text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\n- summary: ITAR-controlled data\n  text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations\n    maintained by the U.S. Department of State.\n- summary: Protected health information\n  text: you will not use the APIs for any purpose or in any manner involving transmitting protected health information\n    to Google unless you have received prior written consent to such use from Google.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to access certain APIs you may be required to provide certain information (such as identification\n    or contact details) as part of the registration process\nminimum_age:\n  value:\
  \ null\n  text: you are not of legal age to form a binding contract with Google\n"
source_yaml_url: https://artifacts.apis.io/google-vault/eligibility/google-vault-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Google Vault's own page on 2026-11-09.
synthetic: false
tags:
- eDiscovery
- Legal Hold
- Information Governance
- Compliance
- Archiving
- Retention
- Google Workspace
- Audit
---
