---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If Customer is based in the EU/EEA, disputes go to the ordinary courts of Oslo; if based outside the EU/EEA, disputes go to arbitration in Oslo.
  entity_types:
  - text: The Service is available for individuals aged 13 years or older.
    type: individual
  - text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: The Service is available for individuals aged 13 years or older.
    value: '13'
  restricted_uses:
  - summary: Abuse or breach allows suspension
    text: Vev can with immediate effect close or suspend access to the Service if Customer abuses the Service or if Customer otherwise is in breach of its obligations pursuant to this Agreement.
  - summary: Sanctioned-business link allows termination
    text: is linked to business that have been sanctioned for any reason
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
name: Vev
provenance_date: '2026-11-10'
provider_name: Vev
provider_slug: vev
slug: vev-eligibility
source_date: '2026-11-10'
source_filename: vev-eligibility.yml
source_heading: Eligibility
source_page: https://www.vev.design/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vev\naid: vev\nurl: https://www.vev.design/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If Customer is based in the EU/EEA, disputes go to the ordinary courts of Oslo; if based outside the EU/EEA,\n    disputes go to arbitration in Oslo.\nentity_types:\n- type: individual\n  text: The Service is available for individuals aged 13 years or older.\n- type: business\n  text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such entity\nrestricted_uses:\n- summary: Abuse or\
  \ breach allows suspension\n  text: Vev can with immediate effect close or suspend access to the Service if Customer abuses the Service or if\n    Customer otherwise is in breach of its obligations pursuant to this Agreement.\n- summary: Sanctioned-business link allows termination\n  text: is linked to business that have been sanctioned for any reason\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Service is available for individuals aged 13 years or older.\n"
source_yaml_url: https://artifacts.apis.io/vev/eligibility/vev-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Vev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Design Tech
- No-Code
- Web Design
- CMS
- Website Builder
- Webhook
- React Components
- Developer Tools
---
