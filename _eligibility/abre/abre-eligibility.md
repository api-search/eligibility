---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: not a person barred from accessing the Services under the laws of the United States or other applicable jurisdiction.
  entity_types:
  - text: If you are using the Services on behalf of a business or organization, you are expressly representing that you have the full right and authority to use the Services and to take any actions on or related to the Services.
    type: business
  minimum_age:
    text: If you are under 18 years of age, or the age of majority in your place of residence, you may not use or access the Services for any reason.
    value: '18'
  restricted_uses:
  - summary: Code of Conduct prohibitions
    text: 'You agree not to do any of the following: Restrict or inhibit any other user from using and enjoying the Services.'
  - summary: Unlawful or inaccurate content
    text: Post, upload to, transmit, distribute, store, create or otherwise publish any knowingly inaccurate or misleading personal or financial information or any Content that you do not have the full right and authority to upload.
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
name: Abre
provenance_date: '2026-11-09'
provider_name: Abre
provider_slug: abre
slug: abre-eligibility
source_date: '2026-11-09'
source_filename: abre-eligibility.yml
source_heading: Eligibility
source_page: https://abre.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Abre\naid: abre\nurl: https://abre.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: not a person barred from accessing the Services under the laws of the United States or other applicable\n    jurisdiction.\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of a business or organization, you are expressly representing that\n    you have the full right and authority to use the Services and to take any actions on or related to the Services.\nrestricted_uses:\n- summary: Code of Conduct prohibitions\n  text: 'You agree not to\
  \ do any of the following: Restrict or inhibit any other user from using and enjoying the\n    Services.'\n- summary: Unlawful or inaccurate content\n  text: Post, upload to, transmit, distribute, store, create or otherwise publish any knowingly inaccurate or misleading\n    personal or financial information or any Content that you do not have the full right and authority to upload.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, or the age of majority in your place of residence, you may not use or\n    access the Services for any reason.\n"
source_yaml_url: https://artifacts.apis.io/abre/eligibility/abre-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Abre's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- K-12
- EdTech
- Education Data
- Student Information Systems
- Rostering
- Interoperability
- OneRoster
- Analytics
- Dashboards
- SSO
---
