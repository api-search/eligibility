---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals, companies, or other entities located in the United States. You may not use the Service if you are a resident of a country embargoed by the United States
  entity_types:
  - text: You may use the Bleacher Report Service only if you can form a binding contract with Bleacher Report
    type: individual
  minimum_age:
    text: By signing up to receive texts, you represent that you are thirteen (13) years of age or older
    value: '13'
  restricted_uses:
  - summary: Commercial use prohibited
    text: You may not use the Service for any commercial purposes.
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
name: Bleacher Report
provenance_date: '2026-11-09'
provider_name: Bleacher Report
provider_slug: bleacher-report
slug: bleacher-report-eligibility
source_date: '2026-11-09'
source_filename: bleacher-report-eligibility.yml
source_heading: Eligibility
source_page: https://bleacherreport.com/pages/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bleacher Report\naid: bleacher-report\nurl: https://bleacherreport.com/pages/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals,\n    companies, or other entities located in the United States. You may not use the Service if you are a resident\n    of a country embargoed by the United States\nentity_types:\n- type: individual\n  text: You may use the Bleacher Report Service only if you can form a binding contract with Bleacher Report\nrestricted_uses:\n-\
  \ summary: Commercial use prohibited\n  text: You may not use the Service for any commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: By signing up to receive texts, you represent that you are thirteen (13) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/bleacher-report/eligibility/bleacher-report-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bleacher Report's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sports
- Media
- Sports News
- Content
- Entertainment
---
