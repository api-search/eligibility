---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'if registering as a private individual: name, surname, gender, date of birth, email address'
    type: individual
  - text: 'if registering as a company: name, surname, gender, date of birth, email address, organization name, Country (where the company is headquartered), VAT number and Tax Code'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Violating laws or third-party rights
    text: Violate laws, third-party rights or articles contained in these Terms of Service and in the other Legal Documents
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
name: Openbridge
provenance_date: '2026-11-09'
provider_name: Openbridge
provider_slug: airpim
slug: airpim-eligibility
source_date: '2026-11-09'
source_filename: airpim-eligibility.yml
source_heading: Eligibility
source_page: https://www.airpim.com/en/documents/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Openbridge\naid: airpim\nurl: https://www.airpim.com/en/documents/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'if registering as a private individual: name, surname, gender, date of birth, email address'\n- type: business\n  text: 'if registering as a company: name, surname, gender, date of birth, email address, organization name, Country\n    (where the company is headquartered), VAT number and Tax Code'\nrestricted_uses:\n- summary: Violating laws or third-party rights\n  text: Violate laws, third-party rights\
  \ or articles contained in these Terms of Service and in the other Legal\n    Documents\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/airpim/eligibility/airpim-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Openbridge's own page on 2026-11-09.
synthetic: false
tags:
- Data Integration
- Automation
- Analytics
- Modular Software
- Openbridge
---
