---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: We provide the Service for use only by persons located within the jurisdictions of the United States and Canada.
  entity_types:
  - text: you hereby represent that you are of legal age, and are otherwise fully able and competent, to enter into a binding agreement
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent that you have the right to bind such organization to this Agreement
    type: business
  minimum_age:
    text: If you are under the age of 13, you are not permitted to register as a User or to send personal information to Company.
    value: '13'
  restricted_uses:
  - summary: Users under 13
    text: If you are under the age of 13, you are not permitted to register as a User or to send personal information to Company.
  - summary: Competitive development
    text: use the Service in the development, directly or indirectly, of any product, software or service that offers any functionality substantially similar to, or competitive with, the Service.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: you may be required to provide us with your first name, last name, email address, telephone number, provide a photograph of your drivers license or other form of identification, take a selfie
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Voatz
provenance_date: '2026-11-10'
provider_name: Voatz
provider_slug: voatz
slug: voatz-eligibility
source_date: '2026-11-10'
source_filename: voatz-eligibility.yml
source_heading: Eligibility
source_page: https://voatz.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Voatz\naid: voatz\nurl: https://voatz.com/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: We provide the Service for use only by persons located within the jurisdictions of the United States and\n    Canada.\nentity_types:\n- type: individual\n  text: you hereby represent that you are of legal age, and are otherwise fully able and competent, to enter into\n    a binding agreement\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have the right to bind\n    such organization to this Agreement\nrestricted_uses:\n\
  - summary: Users under 13\n  text: If you are under the age of 13, you are not permitted to register as a User or to send personal information\n    to Company.\n- summary: Competitive development\n  text: use the Service in the development, directly or indirectly, of any product, software or service that offers\n    any functionality substantially similar to, or competitive with, the Service.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: you may be required to provide us with your first name, last name, email address, telephone number, provide\n    a photograph of your drivers license or other form of identification, take a selfie\nminimum_age:\n  value: '13'\n  text: If you are under the age of 13, you are not permitted to register as a User or to send personal information\n    to Company.\n"
source_yaml_url: https://artifacts.apis.io/voatz/eligibility/voatz-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Voatz's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Voting
- Elections
- Mobile Voting
- Blockchain
- Government
- Civic Technology
- Security
- Identity Verification
---
