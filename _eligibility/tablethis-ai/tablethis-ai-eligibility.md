---
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - GB
    - CH
    served:
    - US
    text: TableThis is operated by Second Coffee, LLC from the United States and is intended for users in the United States. The Service is not directed to individuals in the European Economic Area, the United Kingdom, or Switzerland, and we do not market or offer it to individuals in those regions.
  entity_types:
  - text: You must be at least 16 years old to use the Service.
    type: individual
  - text: You may use the Service on behalf of an organization only if you are authorized to do so.
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  restricted_uses:
  - summary: HIPAA-regulated PHI
    text: Do not use the Service to create, receive, maintain, or transmit protected health information regulated by HIPAA on behalf of a covered entity or business associate unless TableThis has expressly agreed in writing to that use
  - summary: Payment-card data
    text: Do not store credit-card numbers, card security codes, PINs, magnetic-stripe data, or other payment-card information that would require TableThis to operate as a PCI DSS cardholder-data environment.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide accurate account information and keep it reasonably up to date.
excluded_countries:
- GB
- CH
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: tablethis-ai
provenance_date: '2026-11-10'
provider_name: tablethis-ai
provider_slug: tablethis-ai
slug: tablethis-ai-eligibility
source_date: '2026-11-10'
source_filename: tablethis-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.tablethis.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tablethis-ai\naid: tablethis-ai\nurl: https://www.tablethis.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded:\n  - GB\n  - CH\n  text: TableThis is operated by Second Coffee, LLC from the United States and is intended for users in the United\n    States. The Service is not directed to individuals in the European Economic Area, the United Kingdom, or Switzerland,\n    and we do not market or offer it to individuals in those regions.\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to use the Service.\n- type: business\n  text: You may use the Service on\
  \ behalf of an organization only if you are authorized to do so.\nrestricted_uses:\n- summary: HIPAA-regulated PHI\n  text: Do not use the Service to create, receive, maintain, or transmit protected health information regulated\n    by HIPAA on behalf of a covered entity or business associate unless TableThis has expressly agreed in writing\n    to that use\n- summary: Payment-card data\n  text: Do not store credit-card numbers, card security codes, PINs, magnetic-stripe data, or other payment-card\n    information that would require TableThis to operate as a PCI DSS cardholder-data environment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide accurate account information and keep it reasonably up to date.\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/tablethis-ai/eligibility/tablethis-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from tablethis-ai's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Database
- Collaboration
- Internal Apps
- Low-Code
---
