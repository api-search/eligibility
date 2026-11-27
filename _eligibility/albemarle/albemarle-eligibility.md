---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: THE SITE IS INTENDED ONLY FOR BUSINESSES OF THE UNITED STATES.
  entity_types:
  - text: THIS SITE IS FOR BUSINESS USE ONLY AND IS NOT INTENDED FOR CONSUMER SALES FOR PERSONAL, HOUSEHOLD, OR INDIVIDUAL USE.
    type: business
  minimum_age:
    text: YOU ATTEST THAT YOU ARE AT LEAST THE AGE OF MAJORITY IN YOUR STATE, PROVINCE, OR COUNTRY OF RESIDENCE
    value: null
  restricted_uses:
  - summary: Consumer personal or household use
    text: THIS SITE IS FOR BUSINESS USE ONLY AND IS NOT INTENDED FOR CONSUMER SALES FOR PERSONAL, HOUSEHOLD, OR INDIVIDUAL USE.
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
name: Albemarle
provenance_date: '2026-11-09'
provider_name: Albemarle
provider_slug: albemarle
slug: albemarle-eligibility
source_date: '2026-11-09'
source_filename: albemarle-eligibility.yml
source_heading: Eligibility
source_page: https://www.albemarle.com/us/en/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Albemarle\naid: albemarle\nurl: https://www.albemarle.com/us/en/terms-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: THE SITE IS INTENDED ONLY FOR BUSINESSES OF THE UNITED STATES.\nentity_types:\n- type: business\n  text: THIS SITE IS FOR BUSINESS USE ONLY AND IS NOT INTENDED FOR CONSUMER SALES FOR PERSONAL, HOUSEHOLD, OR INDIVIDUAL\n    USE.\nrestricted_uses:\n- summary: Consumer personal or household use\n  text: THIS SITE IS FOR BUSINESS USE ONLY AND IS NOT INTENDED FOR CONSUMER SALES FOR PERSONAL, HOUSEHOLD, OR INDIVIDUAL\n    USE.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: YOU ATTEST THAT YOU ARE AT LEAST THE AGE OF MAJORITY IN YOUR STATE, PROVINCE, OR COUNTRY OF RESIDENCE\n"
source_yaml_url: https://artifacts.apis.io/albemarle/eligibility/albemarle-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Albemarle's own page on 2026-11-09.
synthetic: false
tags:
- Chemicals
- Lithium
- Bromine
- Energy Storage
- Electric Vehicles
- Specialty Chemicals
- Pharmaceuticals
- Sustainability
- Materials Science
- Manufacturing
- Fortune 1000
---
