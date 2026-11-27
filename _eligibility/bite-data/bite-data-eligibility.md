---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By using the Services, you represent and warrant that you are of legal age to form a binding contract and meet all eligibility requirements.
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: You may use the Application only for lawful purposes and in accordance with these Terms of Use.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Customer is required to enter into a separate agreement in order to receive white label access, authorized by company personnel with authorization levels to do so.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BITE Data
provenance_date: '2026-11-09'
provider_name: BITE Data
provider_slug: bite-data
slug: bite-data-eligibility
source_date: '2026-11-09'
source_filename: bite-data-eligibility.yml
source_heading: Eligibility
source_page: https://bitedata.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BITE Data\naid: bite-data\nurl: https://bitedata.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: You may use the Application only for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Customer is required to enter into a separate agreement in order to receive white label access, authorized\n    by company personnel with authorization levels to do so.\nminimum_age:\n  value: null\n  text: By using the Services,\
  \ you represent and warrant that you are of legal age to form a binding contract and\n    meet all eligibility requirements.\n"
source_yaml_url: https://artifacts.apis.io/bite-data/eligibility/bite-data-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from BITE Data's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Trade Compliance
- Customs
- Tariffs
- HTS Classification
- Export Control
- Sanctions Screening
- Supply Chain
- Risk Management
- Artificial Intelligence
---
