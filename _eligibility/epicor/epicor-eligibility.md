---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Although this Site is accessible worldwide, not all services discussed or referenced in this Site are available to all persons or in all geographic locations or jurisdictions.
  entity_types:
  - text: By registering for an account, a password and the right to use the protection portions of the Site, you are certifying that you are an authorized representative of your company with the right to bind your company to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export controls and embargoed parties
    text: Software and other Content made accessible under these Terms may be subject to United States export control laws and regulations
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
name: Epicor
provenance_date: '2026-11-09'
provider_name: Epicor
provider_slug: epicor
slug: epicor-eligibility
source_date: '2026-11-09'
source_filename: epicor-eligibility.yml
source_heading: Eligibility
source_page: https://www.epicor.com/en-us/company/compliance/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Epicor\naid: epicor\nurl: https://www.epicor.com/en-us/company/compliance/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Although this Site is accessible worldwide, not all services discussed or referenced in this Site are available\n    to all persons or in all geographic locations or jurisdictions.\nentity_types:\n- type: business\n  text: By registering for an account, a password and the right to use the protection portions of the Site, you\n    are certifying that you are an authorized representative of your company with the right to bind your company\n    to these Terms\n\
  restricted_uses:\n- summary: Export controls and embargoed parties\n  text: Software and other Content made accessible under these Terms may be subject to United States export control\n    laws and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/epicor/eligibility/epicor-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Epicor's own page on 2026-11-09.
synthetic: false
tags:
- ERP
- Manufacturing
- Distribution
- Enterprise
- REST
- Fortune 500
---
